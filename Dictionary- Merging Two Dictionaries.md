## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

def merge(dict1, dict2):

    res = {**dict1, **dict2}
    return res

dict1 = {'a': 10, 'b': 20}

dict2 = {'b': 30, 'c': 40}

merged_dict = merge(dict1, dict2)

print(merged_dict)

## Output
<img width="338" height="28" alt="image" src="https://github.com/user-attachments/assets/33ad4f3b-9975-4148-b7b9-e0bd079a3e14" />

## Result
The program employs the double-asterisk unpacking operator to combine two dictionaries into a single collection, where any overlapping keys are updated with values from the second dictionary.
