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
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber:  22008369
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input()):
print("Square root of the number:",newton_method(a))
*/
```

## Output:

![WhatsApp Image 2023-01-22 at 16 19 15](https://user-images.githubusercontent.com/119395610/213912020-f4fb5bcf-aa6b-4fe1-b153-2fe45652ad1c.jpg)
![WhatsApp Image 2023-01-22 at 16 19 25](https://user-images.githubusercontent.com/119395610/213912031-10080b81-24e7-470c-92dd-4264da72de78.jpg)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
