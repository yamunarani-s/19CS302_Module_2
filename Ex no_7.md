# EX 7 C Program to Print a right triangle star Pattern
## DATE:19/05/2025
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
Analyze the question
Follow the algorithm
Try the code
Check for error
Run & Display the output

## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

void multiply(); void divide();

int main() { multiply(); divide(); return 0; }

void multiply() { int a, b, result; scanf("%d %d", &a, &b); result = a * b; printf("Multiplication = %d\n", result); }

void divide() { float a, b, result; scanf("%f %f", &a, &b); if(b != 0) result = a / b; else { printf("Division by zero is not allowed.\n"); return; } printf("Division = %.2f\n", result); }

## Output:
Multiplication = 24 Division = 4.00


## Result:
Thus the program was executed and the output was verified successfully.
