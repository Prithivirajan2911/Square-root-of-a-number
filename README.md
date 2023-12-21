# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get a number as input as n
3. Enter the While Loop.
4. Formula = 0.5 * (a + n / a).
5. Print the result.

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: PRITHIVIRAJAN V
RegisterNumber: 23003859
*/
def sq_root(n):
    a=0.5*n
    b=0.5*(a+n/a)
    while(b!=a):
        a=b
        b=0.5*(a+n/a)
    print("Square root of the number:",a)
n=int(input())
sq_root(n)
```

## Output:
![OUTPUT](https://github.com/Prithivirajan2911/Square-root-of-a-number/assets/147020085/f8712de5-7b64-48ef-965e-652d9336a8bb)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
