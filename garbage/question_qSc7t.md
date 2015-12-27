How many times printf() will be executed in the below mentioned program?
```
	main() {
       int i;
		for (i = 0; i < 4; i++){
        	fork();
        }
   		printf("my pid = %d\n", getpid());
    }
  ```
* 8
+ 16
* 12
* 4
* 32
