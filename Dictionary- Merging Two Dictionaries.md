## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge():
    x = {**dict1, **dict2}
    print(x)

merge()

## Output
<img width="384" height="223" alt="Screenshot 2026-03-25 205553" src="https://github.com/user-attachments/assets/9d38390a-81af-4e02-b911-03947c69090d" />

## Result
Thus, the code was successfully implemented.
