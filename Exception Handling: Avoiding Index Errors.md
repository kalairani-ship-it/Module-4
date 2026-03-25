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
<img width="379" height="216" alt="Screenshot 2026-03-25 205914" src="https://github.com/user-attachments/assets/8d3b76f0-2290-4764-8a23-dc43c7a8d821" />

## Result
Thus, the code was implemented successfully.
