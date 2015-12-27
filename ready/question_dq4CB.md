How many processes including the parent will be created by the following code?

```C
#include <unistd.h>
int main(){
  if (!fork()){
    fork();
  }
  fork()
}
```

* 3
* 4
* 5
+ 6
* 7
* 8
