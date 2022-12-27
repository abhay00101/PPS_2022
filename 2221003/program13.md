## Program 13: Write a code using switch statement
```
#include<stdio.h>
int main()
{
	char a;
	printf("Enter no.:");
	scanf("%d",&a);
	switch (a)
	{
	case(1):
	printf("FAN ON");
	break;
	case(2):
	printf("LIGHT ON");
	break;
	case(3):
	printf("BULB ON");
	break;
	case(4):
	printf("AC ON");
	break;
	
	default:
	printf("Sorry wrong IP");		
	}
	return 0; 
}
```
**output**
```
Enter no.:2
LIGHT ON
```
