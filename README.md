# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:

      def fun(n):
      if (n >0):
      fun(n - 2)
      print(n-1,
      end=" ) x =
      int(input())
      if(x%2==0):
      fun(x )
       else:
      fun(x+1)

## OUTPUT
<img width="458" height="148" alt="image" src="https://github.com/user-attachments/assets/4b5bc8c8-c081-42ca-a3d4-e7daed81ae31" />

## RESULT
Thus, the given program is implemented and executed successfully.

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
