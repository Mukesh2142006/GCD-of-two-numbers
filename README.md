## DATE:
# EX NO-4 Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
Program to find the gcd of two number using function. 
Developed by: MUKESH.B
RegisterNumber:  212223230128


    def gcd(): 
    a,b=int(input()), int (input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            hcf =i
    print("GCD of two numbers is:",hcf)
```

## Output:
![Screenshot 2024-09-04 170835](https://github.com/user-attachments/assets/0d560ae5-3c49-48b1-9149-a008593d7d81)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
