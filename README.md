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
Developed by: VIJAY R
RegisterNumber:  23013759
def sqrt(b,initial=1.0,tolerance=1e-10,max=100):
    x=initial
  
    for _ in range(max):
        y=0.5*(x+b/x)
        
         
        if abs(y-x)< tolerance:
            return y
        x=y
    return x
b=int(input())
result=sqrt(b)

print("Square root of the number:",result)

*/
```

## Output:
![Screenshot 2023-12-01 003759](https://github.com/vijayr21/Square-root-of-a-number/assets/149347607/d71fe669-82fc-455e-aa39-f8cf81347294)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
