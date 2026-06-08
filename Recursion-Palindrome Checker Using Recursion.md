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
      def fun(n):
          if n==1:
              return 1
          elif n==0:
              return 0
          else:
              print(n,end=" ")
              return(fun(fun(n-2)))
              
      n=int(input())
      print(fun(n))

## OUTPUT
<img width="356" height="166" alt="image" src="https://github.com/user-attachments/assets/7fb829a3-53e8-48ee-86aa-042bf04ce3f3" />

## RESULT

Thus the Nested recursion is verified.
