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
num = int(input())
temp = num
rev =  0
while num > 0:
    digit = num % 10
    rev = rev * 10 + digit
    num = num // 10
if temp == rev:
    print(f"The given number {rev} is a Palindrome")
else:
    print(f"The given number {temp} is not a palindrome")

## Output

<img width="971" height="191" alt="image" src="https://github.com/user-attachments/assets/914b5fd4-80ba-48ae-ad5f-17d0df7adc5a" />


## Result
Thus, The Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions was executed successfully.
