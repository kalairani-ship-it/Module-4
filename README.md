# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of circle:", area)

r = float(input("Enter radius: "))

obj = cse()
obj.mech(r)

## Output
<img width="411" height="349" alt="Screenshot 2026-03-25 205306" src="https://github.com/user-attachments/assets/77dfa285-e134-4b64-9173-8d10348ea820" />

## Result
Thus, the code was implemented successfully.

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

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
count = 0

with open("story.txt", "r") as f:
    for line in f:
        if line[0] != 'T':
            count += 1

print("Number of lines not starting with T:", count)

## Output
<img width="427" height="232" alt="image" src="https://github.com/user-attachments/assets/b23294fc-1de4-4196-adba-5d51fdcca6ee" />

## Result
Thus, the code was executed successfully.
