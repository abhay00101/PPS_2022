## Programe 36: Write a code using selection sort.
```
#include <stdio.h>
int main()
{
int a[100], n, i, j, position, swap;
printf("Enter number of elements\n");
scanf("%d", &n);
printf("Enter %d Numbers\nn", n);
for (i = 0; i < n; i++)
scanf("%d", &a[i]);
for(i = 0; i < n - 1; i++)
{
position=i;
for(j = i + 1; j < n; j++)
{
if(a[position] > a[j])
position=j;
}
if(position != i)
{
swap=a[i];
a[i]=a[position];
a[position]=swap;
}
}
printf("Sorted Array:\n");
for(i = 0; i < n; i++)
printf("%d\nn", a[i]);
return 0;
}
```
Output:
```
Enter number of elements
5
Enter 5 Numbers
4
8
1
50
7
Sorted Array:
1
4
7
8
50
