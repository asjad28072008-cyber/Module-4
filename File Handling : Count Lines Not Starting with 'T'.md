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
```
with open ('story.txt','r') as file:
   count=0
   for line in file:
      lines=line.strip()
      if lines[0]!='T':
         count+=1
print("Sum :",count)
```

## Output

<img width="510" height="172" alt="Screenshot 2025-10-20 144312" src="https://github.com/user-attachments/assets/68b66ccf-6aba-4f84-b7a2-e2092b2bfc5d" />


## Result
Thus ,the python program has been executed successfully
