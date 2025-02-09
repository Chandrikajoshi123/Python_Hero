# Python Beginer to Pro


![WhatsApp Image 2025-01-16 at 12 25 16](https://github.com/user-attachments/assets/0cec4a7c-85bb-4847-9520-76f08f193fcc)

------------------------------------------

Wlcome to the **Learn Python: Beginner to Pro** repository! This repository is designed to guide absolute begginers through their python programming journy, starting with basics and progressing to advanced concepts. <br>
Whether you are learning Python for data analysis, web development, or automation, this repository provides clear explanations, real_world examples, practice questions, and coding exercises to help you build a strong foundation.

------------------------------------------
## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Basic Concepts](#basic-concepts)
    - [Variables](#variables)
    - [Data Types](#data-types)
    - [Operators](#operators)
    - [Control Flow](#control-flow)
    - [Functions](#functions)
4. [Advanced Topics](#advanced-topics)
    - [Object-Oriented Programming](#object-oriented-programming)
    - [Modules and Packages](#modules-and-packages)
    - [File Handling](#file-handling)
    - [Exception Handling](#exception-handling)
    - [Decorators](#decorators)
    - [Generators](#generators)
    - [Context Managers](#context-managers)
    - [Regular Expressions](#regular-expressions)
    - [Concurrency and Parallelism](#concurrency-and-parallelism)
    - [Asynchronous Programming](#asynchronous-programming)
    - [Unit Testing](#unit-testing)
5. [Projects](#projects)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction
Python is a versatile and beginner-friendly programming language. It's widely used in web development, data analysis, artificial intelligence, scientific computing, and more. This repository aims to provide you with the knowledge and skills you need to become a Python Hero.

## Getting Started
To get started with Python, you need to install Python on your computer. You can download it from the official [Python website](https://www.python.org/). Once installed, you can write and run Python code using an Integrated Development Environment (IDE) like PyCharm, VS Code, or even a simple text editor.

## Basic Concepts

### Variables
Variables are used to store data values. You can think of them as containers for data. For example:
```python
age = 20
name = "Chandrika"
```

### Data Types
Data types specify the type of data that a variable can hold. Common data types include:

- Integer: Whole numbers (e.g., 42)
- Float: Decimal numbers (e.g., 3.14)
- String: Text (e.g., "Hello, World!")
- Boolean: True or False values (e.g., True)

### Operators

Operators are symbols that perform operations on variables and values. Common operators include:

- Arithmetic Operators: +, -, *, /
- Comparison Operators: ==, !=, <, >, <=, >=
- Logical Operators: and, or, not
  
### Control Flow

Control flow statements allow you to control the execution of code based on conditions. Common control flow statements include:

- If Statement: Executes code if a condition is true.
```python

if age > 18:
    print("You are an adult.")

```
- For Loop: Iterates over a sequence (e.g., list, string)
```python
for i in range(5):
    print(i)
```

- While Loop: Repeats code as long as a condition is true.
```python
  while age < 30:
    age += 1
  ```
### Functions

Functions are reusable blocks of code that perform a specific task. You can define a function using the def keyword.
```python
def greet(name):
    print(f"Hello, {name}!")
```
You can call a function by using its name followed by parentheses.
```python
greet("Alice")
```
## Advanced Topics
### Object-Oriented Programming

Object-Oriented Programming (OOP) is a programming paradigm based on the concept of "objects". Objects are instances of classes, which can have attributes (data) and methods (functions).
```python
class Dog:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def bark(self):
        print("Woof!")

my_dog = Dog("Lucy", 3)
my_dog.bark()
```
### Modules and Packages

Modules are files containing Python code, and packages are directories containing multiple modules. You can import and use them in your projects.
```python
import math
print(math.sqrt(16))
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
### File Handling

You can read from and write to files using Python's built-in functions.
```python
# Writing to a file
with open("example.txt", "w") as file:
    file.write("Howdy!")

# Reading from a file
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```
### Exception Handling

Exceptions are errors that occur during the execution of a program. You can handle exceptions using try-except blocks.
```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero.")
```

### Decorators

Decorators are a way to modify or extend the behavior of functions or methods. They are commonly used for logging, access control, and caching.

```python
def my_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

@my_decorator
def say_hello():
    print("Hello!")

say_hello()
```
### Generators

Generators are a type of iterable, like lists or tuples, but they generate values on the fly using the yield keyword. They are memory efficient and can be used to handle large datasets.
```python
def my_generator():
    yield 1
    yield 2
    yield 3

gen = my_generator()
for value in gen:
    print(value)
```
### Context Managers

Context managers are used to manage resources, such as opening and closing files, in a clean and efficient way using the with statement.
```python
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```

### Regular Expressions

Regular expressions (regex) are patterns used to match character combinations in strings. They are useful for searching, replacing, and validating text.
```python
import re

pattern = r"\d+"
text = "There are 123 apples and 456 oranges."
matches = re.findall(pattern, text)
print(matches)  # Output: ['123', '456']
```
### Concurrency and Parallelism

Concurrency and parallelism allow you to perform multiple tasks simultaneously. Concurrency is achieved using threads, while parallelism is achieved using processes.
```python
import threading

def print_numbers():
    for i in range(5):
        print(i)

thread = threading.Thread(target=print_numbers)
thread.start()
thread.join()
```
### Asynchronous Programming

Asynchronous programming allows you to write non-blocking code using async and await keywords. It is useful for I/O-bound tasks like network requests.

```python
import asyncio

async def say_hello():
    await asyncio.sleep(1)
    print("Hello!")

asyncio.run(say_hello())
```
### Unit Testing

Unit testing involves writing tests for individual units of code to ensure they work as expected. The unittest module provides tools for writing and running tests.
```python
import unittest

def add(a, b):
    return a + b

class TestAddFunction(unittest.TestCase):
    def test_add(self):
        self.assertEqual(add(2, 3), 5)

if __name__ == '__main__':
    unittest.main()
```
### Projects

Check out the projects directory for hands-on projects that will help you apply what you've learned. Each project comes with detailed instructions and sample code.


-------------------------------------------
## How to Use This Repository<br>
1. **Start from the Basics:** Begin with the foundational topics in python Basics and gradually move to advanced sections.<br>
2. **Practice Regularly:** Each section includes coding practice questions to test your understanding.<br>
3. **Explore Examples:** Real-world examples are provided to help you understand how python is used in daily applications.<br>
4. **Apply your Knowledge:** Use the bonus projects to apply what you've learned.<br>

-------------------------------------------
## Contributing 
Wlcome contributions to improve this repositoy!<br>
&bull;Found an error? Submit an issue.<br>
&bull;Have a great example or project? create a pull request.

--------------------------------------------
## License
This repositoy is licensed under the MIT License. Feel free to use, modify, and share this content.

--------------------------------------------
## Contact
For any questions or suggestions, feel free to open an issue or connect on Github.
