## Program 25: Program to print fibonacci series

```c 
#include <stdio.h>

int fibonacci(int n);

int main(){
    int n;
    printf("Enter number of items to print: ");
    scanf("%d",&n);
    for(int i=0;i<n;i++){
        printf("%d ",fibonacci(i));
    }
    printf("\n");
    return 0;
}

int fibonacci(int n){
    if(n<2)return n;
    else return (fibonacci(n-1) + fibonacci(n-2));
}
```
```
Enter number of elements to print -> 10
0 1 1 2 3 5 8 13 21 34
```
