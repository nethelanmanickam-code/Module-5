# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
class Demo:
    
    def __init__(self):
    
        print("Hello World!")

    
    def __del__(self):
    
        print("Hello from the __del__ method.")

obj = Demo()

del obj
## 🧪 Output
<img width="1254" height="215" alt="image" src="https://github.com/user-attachments/assets/6a0b297c-118a-4aaf-a2b1-2126e6c7d18e" />

## Result
Thus the program demonstrates how to implement a destructor in Python using a simple class has been executed successfully.
