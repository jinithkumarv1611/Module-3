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
```python
s = "google"

rev = s[::-1]

if s == rev:
    print("Palindrome String")
else:
    print("Not a Palindrome String")
```

## Output
<img width="1167" height="246" alt="image" src="https://github.com/user-attachments/assets/b215bbc5-3985-4807-b4be-5d79899c5e2c" />

## Result
Thus the given program executed Sucessfully.
