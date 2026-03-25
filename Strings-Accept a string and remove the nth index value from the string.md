# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
~~~
def remove(string, n):
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

string = input("Enter a string: ")
n = int(input("Enter the index to remove: "))
result = remove(string, n)
print("Modified string:", result)
~~~

## Output
<img width="1554" height="981" alt="530364865-d559cd59-bf2a-4c47-b611-f1e572065344" src="https://github.com/user-attachments/assets/4ec213b7-c68e-4532-a03e-cacdc0cf4faa" />

## Result
The program successfully removed the character at the specified index from the string.
