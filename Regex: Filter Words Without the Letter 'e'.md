# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)
~~~
## Output
<img width="1543" height="989" alt="530364488-c17055c7-01f1-4309-954c-52253ff41c4c" src="https://github.com/user-attachments/assets/f0394be2-fbd3-4125-92d8-f6507f86a4ac" />

## Result
The program successfully filtered the words from the list that do not contain the letter 'e'.
