What will happen to parent process in the code?
  pid_t pid;
  pid = fork ();
  if (pid == −1)
    perror ("fork");
  /* the child ... */
  if (!pid) {
  const char *args[] = { "windlass", NULL };
  int ret;
  ret = execv ("/bin/windlass", args);
    if (ret == −1) {
      perror ("execv");
      exit (EXIT_FAILURE);
    } 
  }

The parent process continues running with change
The parent process will not continue
+The parent process continues running with no change
output will be error
