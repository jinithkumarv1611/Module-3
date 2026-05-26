# EX-1
# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```python
numbers = [10, 20, 30, 40, 50]

total = sum(numbers)

print("Sum of list items =", total)

DEVELOPED BY: JINITH KUMAR V
REGISTER NO: 212225040157
```

## Output
<img width="1193" height="178" alt="image" src="https://github.com/user-attachments/assets/4ead9723-9161-4f4a-9117-6bd9809fe233" />

## Result
Thus the given program executed Successfully.

# EX-2
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
```python
import re

l1 = []

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)
```

## Output
<img width="1214" height="326" alt="image" src="https://github.com/user-attachments/assets/ca61bcec-fbd4-4194-a1ac-baaa09ae2077" />

## Result
Thus the given program executed Successfully.

# EX-3
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
```python
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ""

    for i in range(len(s)):
        if i != n:
            a += s[i]

    return a

text = input("Enter a string: ")

print("Modified string:", remove(text))
```

## Output
<img width="1214" height="407" alt="image" src="https://github.com/user-attachments/assets/3c8bafec-ab81-46bd-a260-e10a28f99593" />

## Result
Thus the given program executed Successfully.

# EX-4
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

# EX-5
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
x = ('a', 'n', 'm', 5, 8, 10)

print('n' in x)
print(8 in x)
```

## Output
<img width="1207" height="159" alt="image" src="https://github.com/user-attachments/assets/679ee74b-a45e-4efe-9b45-e49e117e8e33" />

## Result
Thus the given program executed Successfully.

