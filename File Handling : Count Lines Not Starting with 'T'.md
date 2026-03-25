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
