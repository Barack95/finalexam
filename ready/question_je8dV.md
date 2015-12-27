Assume the below code is saved in `final.c`, compiled and run from the commands line as `./a.out`. What will be the last line output to the screen?

```C
#include <sys/types.h>
#include <sys/stat.h>
#include <fcntl.h>
#include <stdio.h>
#include <unistd.h>
int main(){
  int fd=open("final.c",O_RDONLY);
  dup2(fd,0);
  close(fd);
  execlp("grep","","--color=auto","<.*>",NULL);
}
```

* ``#include <sys/types.h>``
* ``#include <sys/stat.h>``
* ``}``
* ``#include <unistd.h>``
+ `execlp("grep","","--color=auto","<.*>",NULL);`
+ none option is correct
