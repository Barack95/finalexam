How many times `"surprise"` will be printed to console?

```C
#include <stdio.h>
#include <unistd.h>
int main()
{
  fork(); printf("surprise\n");
  fork(); printf("surprise\n");
  return 0;
}
```
* 2
* 3
* 4
+ 5
* 6
* 7
