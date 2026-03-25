# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
~~~
string = "google"
reversed_string = string[::-1]

if string == reversed_string:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
~~~

## Output
<img width="1552" height="989" alt="530365166-00e50126-188e-4f81-befa-d7a4a67c7599" src="https://github.com/user-attachments/assets/405dc883-9d2c-4e63-b45e-7923c30ef46c" />

## Result
The program successfully checked that "google" is not a palindrome.
