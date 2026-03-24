# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
data = {'apple': 5, 'orange': 2, 'banana': 8, 'grape': 1}

sorted_by_keys = dict(sorted(data.items()))

sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print(data)

print(sorted_by_keys)

print(sorted_by_values)

## Sample Output
<img width="514" height="81" alt="image" src="https://github.com/user-attachments/assets/8cc9e9db-4f6f-4230-b239-91f75d31374e" />

## Result
The program organizes a dictionary's contents by applying the sorted() function to its items, using a lambda function to target values specifically when alphabetical key-ordering isn't the priority.
