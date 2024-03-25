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
def newtonmtd(num,iter=100):
   a=float(num)
   for i in range(iter):
        num=0.5*(num+a/num)
   return num
a=int(input())
print("Square root of the number:",newtonmtd(a))
```

## Output:
![exp 5 python](https://github.com/Ratheesh28/Square-root-of-a-number/assets/138849186/8c2d8256-7d09-4d22-92d5-10aee792a99f)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
