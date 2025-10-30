# 🔁 Recursion:Palindrome Checker Using Recursion in Python

## 🎯 AIM:
To write a Python program to check whether a given string is a **palindrome** using **recursion**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `is_palindrome(word)`
   - **Base Case:** If the string length is less than 1, return `True`
   - **Recursive Case:** If the first and last characters match, call the function recursively on the substring without first and last characters
   - Else, return `False`
3. Get input from the user
4. Call the recursive function
5. Print whether the string is a palindrome
6. **Stop**

---

## 💻 PROGRAM:

    def is_palindrome(word):
        if(word[0] == word[-1]):
             return True
        else:
             return False
        return is_palindrome(word[0:-1])
    
    word = input()
    if(is_palindrome(word)):
        print("String is a palindrome")
    else:
        print("String is not a palindrome")


## OUTPUT
<img width="1135" height="343" alt="image" src="https://github.com/user-attachments/assets/ada5b1b6-b741-4765-805c-6653bf35d869" />

## RESULT
Thus the program executed successfully .
