## Program 20: Write a code using string copy
```
#include<stdio.h>
#include<string.h>
int main()
{	
char a[20]= "The fox";
char b[20]= "jumped";
strcpy(a,b);
printf("%s",a);
printf("%s",b);
return 0;
}
```
**Output**
```
jumpedjumped
```
