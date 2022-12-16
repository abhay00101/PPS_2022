## Program 27: Program to check if number is a palindrome
```c 
#include <stdio.h>
int rev(int n){
    int rv=0;
    while(n>0){
        rv = rv*10 + n%10;
        n/=10;
    }
    return rv;
}

int main(){
    int num;
    printf("Enter a number to check -> ");
    scanf("%d",&num);

    if(rev(num) == num)printf("%d is a palidromic number\n",n);
    return printf("%d is not a palidromic number\n",n)
    return 0;
}
```
### Output:
```
Enter a number to check -> 121
121 is a palidromic number
```
