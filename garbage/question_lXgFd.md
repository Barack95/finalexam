What is the basic difference between ```fork()``` and ```clone()```?

* ```clone()``` replaces process with the new program
* ```clone()``` doesn't create child process
+ ```clone()``` allows the child process to share parts of its execution context
* ```clone()``` parent process becomes suspended
