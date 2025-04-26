# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM 
1.Begin the program.

2.Take a integer input from the user.

3.Read three integers a, b, and c.

4.Compare a, b, and c.

5.Find the smallest using conditions: If a < b and a < c, smallest is a. Else if b < c, smallest is b. Else, smallest is c.

6.Display the smallest number.

7.Terminate the program.

## PROGRAM
```python
num1 = int(input())
num2 = int(input())
num3 = int(input())

min_num = num1 if (num1 <= num2 and num1 <= num3) else num2 if (num2 <= num1 and num2 <= num3) else num3

print(f"The minimum of {num1}, {num2}, {num3} is {min_num}")
```

## OUTPUT
![Screenshot 2025-04-26 145808](https://github.com/user-attachments/assets/61321df5-b75b-417d-b1f6-3f8dedaa3a5f)
## RESULT
Thus the python program of finding the minimum between three integer numbers using a conditional expression has been implemented and executive successfully.
