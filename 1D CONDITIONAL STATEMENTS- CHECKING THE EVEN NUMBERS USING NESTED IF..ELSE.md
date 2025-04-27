## Experiment No: 1d – Conditional Statements- check whether the given number is Even number and it is lesser than or equal to 30 or not using nested if..else.

## AIM  
To Write a Python program to check whether the given number is Even number or not using nested if else.
## ALGORITHM  
Algorithm to check if a number is Even and ≤ 30:

1. Start

2. Input an integer a.

3. Check if a is divisible by 2:

If yes, print "a is an Even number".

Then, check if a is greater than 30:

If yes, print "a is greater than 30".

Else, print "a is lesser than or equal to 30".

4. If not divisible by 2, print "a is NOT an Even number".

5. End

## PROGRAM
```python
a=int(input())
if a%2==0:
   print(a,"is an Even number")
   if a>=30:
        print(a,"is greater than 30")
   else:
        print(a,"is lesser than or equal to 30")
else:
    print(a,"is NOT an Even number")
```
## OUTPUT
![Screenshot 2025-04-26 152858](https://github.com/user-attachments/assets/e011d9d1-23fe-413e-b88c-4ce9b5d472be)
## RESULT
Thus the python program of finding the given number is Even number or not using nested if else. has been implemented and executed successfully.
