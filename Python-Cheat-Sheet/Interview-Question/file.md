# 🧠 Python Interview Questions Cheat Sheet

## ✅ Basic Level

### 1. What is Python?
Python is a high-level, interpreted programming language with dynamic typing and garbage collection. It's easy to read and supports multiple paradigms.

### 2. What are Python's key features?
- Easy syntax
- Dynamically typed
- Interpreted
- Object-oriented
- Large standard library
- Cross-platform

### 3. What is PEP 8?
PEP 8 is the Python Enhancement Proposal that provides coding style guidelines for writing readable code.

### 4. What are Python data types?
- `int`, `float`, `str`, `bool`
- `list`, `tuple`, `set`, `dict`
- `NoneType`

### 5. What is the difference between `is` and `==`?
- `==` compares values.
- `is` compares memory location (identity).

```python
a = [1, 2]
b = [1, 2]
a == b   # True
a is b   # False
```
```
🔁 Intermediate Level
6. What is a Python list vs tuple?
List: Mutable, uses []

Tuple: Immutable, uses ()
```
```
7. What are *args and **kwargs?
*args: variable number of positional arguments

**kwargs: variable number of keyword arguments
```
```
def func(*args, **kwargs):
    print(args)
    print(kwargs)
```
```
8. What is a Python decorator?
A decorator is a function that takes another function and adds extra functionality without changing the original function.
```
```
def decorator(func):
    def wrapper():
        print("Before")
        func()
        print("After")
    return wrapper
    ```
```
```
9. What is list comprehension?
A concise way to create lists.
```
```
squares = [x*x for x in range(5)]
```
```
🔒 Advanced Level
10. What is the difference between deep copy and shallow copy?
Shallow Copy: Copies reference of objects (one level).

Deep Copy: Copies all nested objects (full clone).
```
```
import copy
copy.copy()     # shallow
copy.deepcopy() # deep
```
```
11. What is a generator?
A generator returns items one by one using yield, saving memory.
```
```
def gen():
    yield 1
    yield 2
```
```
12. What are Python's memory management features?
Automatic garbage collection

Reference counting

Private heap space
```
```
💻 Coding Questions (Common in Interviews)
Q1: Reverse a string
```
```
def reverse_string(s):
    return s[::-1]
```
```
Q2: Check for palindrome
```
```
def is_palindrome(s):
    return s == s[::-1]
```
```
Q3: FizzBuzz
```
```
for i in range(1, 21):
    if i % 3 == 0 and i % 5 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
```
```
Q4: Find factorial (recursion)
```
def factorial(n):
    return 1 if n == 0 else n * factorial(n-1)
```
