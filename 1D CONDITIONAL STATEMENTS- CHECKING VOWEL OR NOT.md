## Experiment No: 1d – Conditional Statements- finding the smallest amoung three Integer numbers

## AIM  
To Write a Python program to find the smallest among three Integer  Numbers
## ALGORITHM  
1. Begin the program.  
2. Take a integer input from the user
3. Read three integers a, b, and c.
4. Compare a, b, and c.
5. Find the smallest using conditions:
If a < b and a < c, smallest is a.
Else if b < c, smallest is b.
Else, smallest is c.
6. Display the smallest number.
7. Terminate the program.

## PROGRAM
```python
a=int(input())
b=int(input())
c=int(input())
min=a if(a<b and a<c) else b if(b<a and b<c) else c
print(f"The Smallest  of the three a= {a} b= {b} c= {c} is {min}")
```
## OUTPUT
![Screenshot 2025-04-26 145101](https://github.com/user-attachments/assets/9b479070-30f3-4014-bdc8-d64c68d413aa)
## RESULT
Thus the python program of finding the smallest among three Integer  Numbers has been implemented and executed successfully.
