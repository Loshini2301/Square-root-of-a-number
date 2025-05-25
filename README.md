
# Find the square root of a number
## NAME:LOSHINI G
## REGISTER NO:212223220051
## DEPARTMENT:IT
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
#program to find the square root for the given number(newton's method) using function.
#Developed by:Loshini G
#Reg No:23012268
def square_root(a):
    x=0.5*a
    y=0.5*(x+a/x)
    while y!=x:
        x=y
        y=0.5*(x+a/x)
    return x
n=int(input())  
result=square_root(n)
print("Square root of the number:",result)
```

## Output:
![Screenshot 2025-05-25 171006](https://github.com/user-attachments/assets/7d05e77a-9481-4a03-a22c-ab3ced3987c0)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
