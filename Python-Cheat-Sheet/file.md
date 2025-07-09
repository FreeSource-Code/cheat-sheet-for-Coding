# 🐍 Python Cheat Sheet

```
## 📌 Basics
```python
# Comments
# This is a single-line comment
"""This is a
multi-line comment"""
```
```
# Variables
x = 5
name = "Ishan"
```
```
# Data Types
int, float, str, bool, list, tuple, dict, set
```
```
# Type Casting
int("5")   # 5
str(10)    # "10"
float("3.14")  # 3.14
```
```
🔄 Conditionals
python
Copy code
if x > 10:
    print("Greater")
elif x == 10:
    print("Equal")
else:
    print("Smaller")
```
```
🔁 Loops
python
Copy code
# For loop
for i in range(5):
    print(i)

# While loop
i = 0
while i < 5:
    print(i)
    i += 1
```
```
📦 Functions
python
Copy code
def greet(name):
    return "Hello " + name

print(greet("Ishan"))
```
```
📚 Data Structures
✅ List
python
Copy code
fruits = ["apple", "banana"]
fruits.append("mango")
print(fruits[0])
```
```
✅ Tuple
python
Copy code
t = (1, 2, 3)
print(t[1])
```
```
✅ Dictionary
python
Copy code
person = {"name": "Ishan", "age": 21}
print(person["name"])
```
```
✅ Set
python
Copy code
my_set = {1, 2, 3}
my_set.add(4)
```
```
🧰 Useful Functions
python
Copy code
len(), type(), range(), print(), input(), sorted()
```
```
🛠️ File Handling
python
Copy code
with open("file.txt", "r") as f:
    data = f.read()

with open("file.txt", "w") as f:
    f.write("Hello World")
```
```
🐞 Exception Handling
python
Copy code
try:
    x = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("Done")
```
```
🧪 OOP (Object-Oriented Programming)
python
Copy code
class Person:
    def __init__(self, name):
        self.name = name
    
    def greet(self):
        print("Hello", self.name)

p = Person("Ishan")
p.greet()
```
```
🧪 Modules and Packages
python
Copy code
import math
print(math.sqrt(16))

# Custom Module
# file: mymodule.py
def hello():
    print("Hello from module")

# use in another file
from mymodule import hello
hello()
```
```
Let me know if you want this in Hindi, or want it topic-wise in separate files like for beginners, data structures, or OOP.

```
