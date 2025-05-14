---
title: "Intro to Python Variables"
date: 2025-05-15
categories:
  - Python Tutorials
tags:
  - python
  - beginner
  - variables
---

# Intro to Python Variables

If you're just starting your journey in Python programming, one of the first concepts you need to understand is **variables**. Variables are like containers — they store data so you can use it later.

In this article, you’ll learn:
- What variables are
- How to create them in Python
- The rules for naming them
- Common data types they can hold

---

## 🧠 What is a Variable?

A **variable** is a name given to a piece of data. You can think of it as a **label** you assign to a value so you can refer to it later in your code.

### ✅ Example:

```python
age = 25
name = "Alice"
is_student = True
```
Here:

age holds an integer (25)

name holds a string ("Alice")

is_student holds a boolean (True)

✍️ How to Create a Variable in Python
In Python, you don’t need to declare the type of the variable. Just assign a value using the = sign.
```python
x = 10
message = "Welcome to Python!"
```
That’s it — Python automatically figures out what type of data it is.

📌 Variable Naming Rules
When naming variables in Python, follow these simple rules:

✅ Allowed:

Must start with a letter or underscore

Can contain letters, numbers, and underscores

Should be meaningful and readable

❌ Not Allowed:

Cannot start with a number

Cannot include special characters like @, #, $

Cannot use Python reserved keywords like if, while, class, etc.

✅ Good Examples:
```python
user_age = 30
total_amount = 99.95
```
❌ Bad Examples:
```python
2user = "Bob"       # starts with a number
my-name = "Ali"     # contains hyphen
```
🔢 Common Data Types in Python
Type	Example
Integer	x = 10
Float	price = 12.99
String	name = "John"
Boolean	is_active = True
List	fruits = ["apple", "banana"]
Dictionary	user = {"name": "Ali", "age": 22}

📚 Pro Tip: You Can Change Variable Types
Python is a dynamically typed language, which means you can assign a new value (even a different type) to the same variable.

```python
score = 10
score = "ten"
```
⚠️ But this can lead to confusion in big projects — try to keep variable types consistent.

✅ Summary
Variables help store and reuse values in your code

Python variables are created with =, and no need to declare a type

Choose meaningful names and follow naming rules

Understand common data types like int, float, string, and bool

This was your first step into Python! Next up, we'll cover data types and input/output in Python to help you build real programs.

🧠 Practice Task:
Try creating your own variables using all five common types listed above!

Written by CodeWithAI - Making coding simple and fun for beginners!
