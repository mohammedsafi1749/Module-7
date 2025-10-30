## 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:

    def sqr(num):
        if num == 0:
            return 0;
        return (num % 10)**2 + sqr(num // 10)
    
    num = int(input())
    print(sqr(num))

## OUTPUT
<img width="1057" height="250" alt="image" src="https://github.com/user-attachments/assets/10a2200c-9445-4002-9342-ad158176cdab" />

## RESULT
Thus the program executed successfully .
