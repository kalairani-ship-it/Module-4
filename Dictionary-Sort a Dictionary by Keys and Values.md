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
d = {'b': 'banana', 'a': 'apple', 'd': 'date', 'c': 'cherry'}

print("Original dictionary:", d)

key_sort = dict(sorted(d.items()))
print("Sorted by keys:", key_sort)

value_sort = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by values:", value_sort)

## Sample Output
<img width="856" height="265" alt="Screenshot 2026-03-25 205737" src="https://github.com/user-attachments/assets/e4e7315f-4541-4a18-b67f-da9351cccd78" />

## Result
Thus, the code was executed successfully.
