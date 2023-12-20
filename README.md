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
Developed by: PRAVEEN K
RegisterNumber:  23014148
def square_root_newton(number):
    
    x=number/2.0
    iterations=100
    for _ in range (iterations):
        x=0.5*(x+number/x)
    return x
a=int(input())
result=square_root_newton(a)
print("Square root of the number:",result)
*/
```

## Output:
 ![image](https://github.com/K-PRAVEEN-2005/Square-root-of-a-number/assets/145742724/e35e53dc-98d2-4cbb-82e9-caa1649e85f5)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
