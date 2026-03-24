# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
list1 = [10, 20, 30]

try:

    print(list1[5])
    
except IndexError:

    print("You're out of list range")
## Output
<img width="265" height="37" alt="image" src="https://github.com/user-attachments/assets/aa31330c-ab07-4809-852d-96c08080029e" />

## Result
The program uses a try-except block to safely intercept an IndexError and display a custom warning message when an attempt is made to access a list position that does not exist.
