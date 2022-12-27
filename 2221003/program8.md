## Program 8: write a program using continue statement.
```
#include <stdio.h>
int main()
{
int i=10;
for(i; i<20 ; i++)
{
    if(i==15)
    {
        continue;
    }
    printf("%d\n",i);
}
return 0;
}
```
**output
```
10
11
12
13
14
16
17
18
19
```
