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
```
import math
def cir(hj):
    ol=math.pi*hj*hj
    print(f"Area of circle: {ol:.2f}")
f=int(input())
cir(f)
```


## Output


<img width="715" height="180" alt="Screenshot 2025-10-20 112945" src="https://github.com/user-attachments/assets/d260e5bc-0301-44f3-920c-a0722f80f48a" />



## Result


Thus,the python program has been executed successfully


## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1=eval(input())
dict2=eval(input())
dict1.update(dict2)
print(dict1)
```


## Output

<img width="1310" height="151" alt="Screenshot 2025-10-20 113818" src="https://github.com/user-attachments/assets/06a269bc-c840-40ed-8a26-28160357fc8d" />


## Result
Thus,the python program has been executed successfully


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


```
def dictionairy(): 
# Declaring hash function      
key_value ={}    
# Initializing the value 
key_value[2] = 56       
key_value[1] = 2 
key_value[5] = 12 
key_value[4] = 24 
key_value[6] = 18      
key_value[3] = 323 
print ("Keys and Values sorted", 
"in alphabetical order by the value") 
print(sorted(key_value.items(), key = lambda kv:(kv[1], kv[0])))

```

## Sample Output

<img width="1063" height="132" alt="Screenshot 2025-10-20 143027" src="https://github.com/user-attachments/assets/aa35c338-8fff-4c81-a26c-74edbf4b4e47" />


## Result
Thus ,the python program has been executed successfully





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
```
lis=[5,9,2,2,3]
try:
    print(lis[5])
except IndexError:
    print("You're out of list range")
```

## Output

<img width="603" height="291" alt="Screenshot 2025-10-20 143522" src="https://github.com/user-attachments/assets/8b45a356-1f51-4801-8d7c-02bdbb5d4f5b" />


## Result
Thus ,the python program has been executed successfully




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


