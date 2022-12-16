## Program 24: Program to check prime number
```c
#include <stdio.h>

int main(){
    int num,factors;

    printf("Enter a number to check -> ");
    scanf("%d",&num);

    if(n<2)return 0;
    for(int i=2; i<n/2; i++){
        if(n%i==0)factors++;
    }
    if(factors>0)printf("%d is a prime number.\n",num);
    else printf("%d is not a prime number\n",num);

    return 0;
}
```
### Output:
```
Enter a number : 12
12 is not a prime number.
```
