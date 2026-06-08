# # 🔁 Recursion:Sum of Digits using Recursion in Python

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

      def sum_digit(num):
          if num < 0 or int(num) != num:
              return 0
          elif num == 0:
              return 0
          else:
              return (num % 10) + sum_digit(num//10)
      num= int(input())
      print(sum_digit(num))

## OUTPUT
<img width="467" height="220" alt="image" src="https://github.com/user-attachments/assets/98e82ea3-5e48-4eb5-8e2d-57efb467f217" />

## RESULT
Thus the output is verified.
