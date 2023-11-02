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
Developed by: DEEPAK RAJ S
RegisterNumber: 212222240023
*/
```
```
def gcd():
    a=int(input())
    b=int(input())
    if a<b:
        c=a
    else:
        c=b
    for i in range(1,c+1):
        if a%i==0 and b%i==0:
            gcd=i
    print("GCD of two numbers is:",gcd)
```
## Output:
![WhatsApp Image 2023-11-02 at 16 10 20_bab29eff](https://github.com/DEEPAK2200233/GCD-of-two-numbers/assets/118707676/160480fa-2cd9-40be-a13d-8e1b79ceda6a)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
