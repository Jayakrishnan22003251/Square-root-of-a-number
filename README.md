# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: JAYAKRISHNAN L B L
RegisterNumber:  22003251
def nm(n,ni=100):
    a=float(n)
    for i in range (ni):
        n=0.5*(n+a/n)
    return n
a = int(input())
print("Square root of the number:",nm(a))
*/
```

## Output:
![MergedImages (1)](https://user-images.githubusercontent.com/120232371/210379386-0b8744a3-7e46-423c-a08d-3792d3747eb5.png)

   
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
