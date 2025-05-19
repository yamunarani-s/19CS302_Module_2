# EX 6 C Program to print the string "KEYBOARD" n number of times.
## DATE:19.5.25
## AIM:
To write a C Program to print the string "KEYBOARD" n number of times.

## Algorithm
Analyze the question
Follow the algorithm
Try the code
Check for error
Run & Display the output   

## Program:
```
/*
Program to print the string "KEYBOARD" n number of times.
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int main() { int i, j, rows;

printf("Enter the number of rows: ");
scanf("%d", &rows);

for(i = 1; i <= rows; i++) {
    for(j = 1; j <= i; j++) {
        printf("*");
    }
    printf("\n");
}

return 0;
}

## Output:

**

## Result:
Thus the program was executed and the output was verified successfully.
