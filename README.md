# Find the GCD of two numbers

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
/*
Program to find the gcd of two number using function.
Developed by: MOHAMED RIDWAN A
RegisterNumber:  23003133
*/
def gcd():
    a=int(input())
    b=int(input())
    while b:
       a,b= b,a%b
    print("GCD of two numbers is:",a)
```

## Output:
![image](https://github.com/MOHAMEDRIDWAN/GCD-of-two-numbers/assets/146993368/a9d4a81b-6cab-4538-8443-38cedee28b47)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
