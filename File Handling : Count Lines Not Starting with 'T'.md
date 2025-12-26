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
~~~
f = open("story.txt", "r")
count = 0
for line in f:
    if not line.startswith('T'):
        count += 1
f.close()
print(count)
~~~

## Output
<img width="810" height="208" alt="image" src="https://github.com/user-attachments/assets/452e5f20-9cad-433d-901e-68f3ccc9d394" />

## Result
Thus,the program has been executed successfully.
