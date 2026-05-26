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
s = "malayalam"

rev = s[::-1]

if s == rev:
    print("Palindrome String")
else:
    print("Not a Palindrome String")
```

## Output
<img width="1221" height="254" alt="image" src="https://github.com/user-attachments/assets/0ecbf903-a1d1-4fff-87d0-e12cef482a28" />

## Result
Thus the given program executed Sucessfully.
