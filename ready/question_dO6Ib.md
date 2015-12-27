How many system calls to find out process ppid will actually be issued by the program?
```C
#include <sys/types.h>
#include <unistd.h>
#include <stdio.h>
int main(){
  int i;
  for(i=0;i<10;i++) printf("%d\n",getppid());
}
```
* 5
* 9
+ 10
* 11
* 1
* 0
