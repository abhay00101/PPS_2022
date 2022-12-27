## Program 5: Write a program using conditional operators 
```
# include <stdio.h>
int main()
{ 
 int T=95,PT=95,C;
 C=(T>80&&PT>80)?1000:(PT>80)?500:0;
 printf("%d", C);
 return 0;
}
 
 
output : 1000
```
