# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. 	Start. 
2.	Declare three variable value of type int for marks. 
3.	Prompt the user to enter a value. 
4.	Read the value using scanf. 
5.	Find total and average. 
6.	Print the result
7.	 End. 

## Program:
```
#include <stdio.h>
int main() { 
int sub1, sub2, sub3, total;
float average; 
scanf("%d %d %d", &sub1,&sub2,&sub3); 
total = sub1 + sub2 + sub3;
average = total / 3.0;
 printf("\nTotal : %d\n", total);
 printf("Average : %.2f\n", average);
return 0; 
} 

```

## Output:
![image](https://github.com/user-attachments/assets/66d1a968-d9dd-4519-943b-77a28949b289)




## Result:
Thus the program was executed and the output was verified successfully.
