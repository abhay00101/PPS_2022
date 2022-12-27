## Program 30: Wirte a code to check prime number.
```
#include<stdio.h>
int main()
{
int a,pr=1,i;
printf("Enter the value of a:");
scanf("%d",&a);
for(i=2;i<a;i++) 
{
if(a%i==0)
{
pr=0;
break;
} 
}
if (pr==1)
{
printf("It is prime number");
}
else
{
printf("It is not a prime number");
}
return 0;
}
```
**Output :**
```
Enter the value of a:19
It is prime number
```
