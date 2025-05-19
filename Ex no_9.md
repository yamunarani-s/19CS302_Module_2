# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:19/05/25
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
Analyze the question
Follow the algorithm
Try the code
Check for error
Run & Display the output

## Program:
```
/*
Program to find the sum of odd digits using do while loop.
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int main() {
    int num, digit, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    if(num == 0) {
        sum = 0;
    } else {
        do {
            digit = num % 10;
            if (digit % 2 != 0) {
                sum += digit;
            }
            num = num / 10;
        } while (num != 0);
    }

    printf("Sum of odd digits = %d\n", sum);

    return 0;
}


## Output:
Enter a number: 13524
Sum of odd digits = 9


## Result:
Thus the program was executed and the output was verified successfully.
