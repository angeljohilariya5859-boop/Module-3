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
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
lst = []
for i in items:
    find = re.search(r'e' , i)
    if not find:
        lst.append(i)
print(lst)
## Output

<img width="1917" height="517" alt="image" src="https://github.com/user-attachments/assets/d033afaa-6310-41d1-8e3d-f26c47b69aa1" />

## Result
Thus, The Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) was executed successfully.
