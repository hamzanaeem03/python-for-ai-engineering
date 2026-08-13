# Phase 1 — Python Fundamentals

This phase establishes the core Python knowledge required for the rest of the Python for AI Engineering roadmap.

The goal is **not to memorize Python syntax**. The goal is to become comfortable reading and writing basic Python programs.

---

## 🎯 Objective

By the end of this phase, I should be able to write small Python programs independently and understand basic Python code without relying heavily on tutorials.

---

# 1. Python Setup

- [ ] Install Python
- [ ] Verify Python installation
- [ ] Understand Python versions
- [ ] Run Python from the terminal
- [ ] Understand `.py` files
- [ ] Run a Python script
- [ ] Use the Python REPL
- [ ] Configure VS Code/PyCharm for Python

### Practice

Create:

```text
hello.py
```

Print:

```text
Hello, Python!
```

---

# 2. Variables

Learn:

- [ ] Variables
- [ ] Variable naming conventions
- [ ] Assignment
- [ ] Reassignment
- [ ] Multiple assignment
- [ ] Constants by convention
- [ ] Dynamic typing

Example:

```python
name = "Hamza"
age = 23
is_developer = True
```

Understand:

```text
Variable
   ↓
Value
   ↓
Object in memory
```

---

# 3. Python Data Types

Learn the fundamental built-in types.

### Numeric

- [ ] `int`
- [ ] `float`
- [ ] `complex`

### Boolean

- [ ] `bool`

### Text

- [ ] `str`

### Collections

- [ ] `list`
- [ ] `tuple`
- [ ] `set`
- [ ] `dict`

### Special

- [ ] `None`
- [ ] `NoneType`

Practice identifying the type of different values:

```python
type(10)
type(10.5)
type("Hello")
type(True)
type(None)
```

---

# 4. Strings

Learn:

- [ ] Creating strings
- [ ] Single vs double quotes
- [ ] Multiline strings
- [ ] String indexing
- [ ] String slicing
- [ ] String methods
- [ ] `lower()`
- [ ] `upper()`
- [ ] `strip()`
- [ ] `replace()`
- [ ] `split()`
- [ ] `join()`
- [ ] `startswith()`
- [ ] `endswith()`
- [ ] f-strings

Example:

```python
name = "Hamza"
age = 23

message = f"My name is {name} and I am {age} years old."
```

---

# 5. Lists

Learn:

- [ ] Creating lists
- [ ] Indexing
- [ ] Negative indexing
- [ ] Slicing
- [ ] Updating elements
- [ ] Adding elements
- [ ] Removing elements
- [ ] `append()`
- [ ] `insert()`
- [ ] `remove()`
- [ ] `pop()`
- [ ] `sort()`
- [ ] `reverse()`
- [ ] `len()`

Example:

```python
languages = ["Python", "JavaScript", "Java"]

languages.append("Go")

print(languages)
```

---

# 6. Tuples

Learn:

- [ ] Creating tuples
- [ ] Tuple indexing
- [ ] Tuple unpacking
- [ ] Immutable nature of tuples

Example:

```python
user = ("Hamza", 23)

name, age = user
```

Understand when a tuple is more appropriate than a list.

---

# 7. Sets

Learn:

- [ ] Creating sets
- [ ] Adding elements
- [ ] Removing elements
- [ ] Unique values
- [ ] Union
- [ ] Intersection
- [ ] Difference

Example:

```python
skills = {"Python", "JavaScript", "Python"}

print(skills)
```

Understand why duplicates disappear.

---

# 8. Dictionaries

This is one of the **most important Python data structures for AI development**.

Learn:

- [ ] Creating dictionaries
- [ ] Keys and values
- [ ] Accessing values
- [ ] Updating values
- [ ] Adding keys
- [ ] Removing keys
- [ ] `get()`
- [ ] `keys()`
- [ ] `values()`
- [ ] `items()`
- [ ] Nested dictionaries

Example:

```python
user = {
    "name": "Hamza",
    "age": 23,
    "skills": ["Python", "JavaScript"]
}

print(user["name"])
```

Understand nested JSON-like structures:

```python
response = {
    "status": "success",
    "data": {
        "user": {
            "name": "Hamza"
        }
    }
}
```

This is particularly important because AI APIs frequently return JSON-like data.

---

# 9. Operators

Learn:

### Arithmetic

- [ ] `+`
- [ ] `-`
- [ ] `*`
- [ ] `/`
- [ ] `//`
- [ ] `%`
- [ ] `**`

### Comparison

- [ ] `==`
- [ ] `!=`
- [ ] `>`
- [ ] `<`
- [ ] `>=`
- [ ] `<=`

### Logical

- [ ] `and`
- [ ] `or`
- [ ] `not`

### Membership

- [ ] `in`
- [ ] `not in`

### Identity

- [ ] `is`
- [ ] `is not`

Understand the difference between:

```python
a == b
```

and:

```python
a is b
```

---

# 10. Conditional Statements

Learn:

- [ ] `if`
- [ ] `elif`
- [ ] `else`
- [ ] Nested conditions
- [ ] Conditional expressions

Example:

```python
age = 23

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

Understand Python's indentation rules.

---

# 11. Loops

### `for`

Learn:

- [ ] Iterating over lists
- [ ] Iterating over dictionaries
- [ ] `range()`
- [ ] Nested loops

### `while`

Learn:

- [ ] While loops
- [ ] Loop conditions
- [ ] Avoiding infinite loops

### Loop control

- [ ] `break`
- [ ] `continue`
- [ ] `pass`

Example:

```python
for language in ["Python", "JavaScript", "Java"]:
    print(language)
```

---

# 12. Functions

This is one of the most important topics.

Learn:

- [ ] Defining functions
- [ ] Calling functions
- [ ] Parameters
- [ ] Arguments
- [ ] Return values
- [ ] Default parameters
- [ ] Keyword arguments
- [ ] Multiple parameters
- [ ] Function scope
- [ ] Docstrings

Example:

```python
def calculate_total(price, quantity):
    return price * quantity
```

Understand the difference between:

```python
print()
```

and:

```python
return
```

---

# 13. Input and Output

Learn:

- [ ] `input()`
- [ ] `print()`
- [ ] Formatting output
- [ ] User input validation

Example:

```python
name = input("Enter your name: ")

print(f"Hello, {name}!")
```

---

# 14. Basic Error Awareness

At this stage, understand common Python errors:

- [ ] `SyntaxError`
- [ ] `NameError`
- [ ] `TypeError`
- [ ] `ValueError`
- [ ] `IndexError`
- [ ] `KeyError`
- [ ] `AttributeError`

Don't worry about advanced exception handling yet.

The goal is to learn how to **read the traceback and locate the problem**.

---

# 15. Pythonic Thinking

Start getting used to the Python way of writing code.

Instead of trying to write JavaScript/TypeScript in Python syntax, learn Python conventions.

Important concepts:

- [ ] Indentation
- [ ] Readability
- [ ] PEP 8 awareness
- [ ] Duck typing
- [ ] Explicit over implicit
- [ ] Python built-ins

Example:

```python
numbers = [1, 2, 3, 4, 5]

total = sum(numbers)
```

Rather than manually implementing everything.

---

# 🧪 Exercises

Complete these in:

```text
exercises/
```

### Exercise 01 — Variables

Create variables representing:

- Name
- Age
- City
- Programming experience
- Favorite programming language

Print them using an f-string.

---

### Exercise 02 — Data Types

Create examples of:

- String
- Integer
- Float
- Boolean
- List
- Tuple
- Set
- Dictionary
- None

Print their types.

---

### Exercise 03 — User Profile

Create a dictionary representing a user:

```text
name
age
email
skills
experience
```

Print each value.

---

### Exercise 04 — Calculator

Create functions for:

```text
addition
subtraction
multiplication
division
```

Allow the user to enter two numbers and select an operation.

---

### Exercise 05 — Number Analyzer

Ask the user for a number and determine:

- Positive/negative
- Even/odd
- Greater than 100 or not

---

### Exercise 06 — List Processing

Given:

```python
numbers = [10, 20, 30, 40, 50]
```

Calculate:

- Sum
- Average
- Maximum
- Minimum

---

### Exercise 07 — Dictionary Processing

Given:

```python
user = {
    "name": "Hamza",
    "age": 23,
    "skills": ["JavaScript", "Node.js", "React"]
}
```

Print:

- Name
- Age
- Number of skills
- Each individual skill

---

### Exercise 08 — Word Counter

Ask the user for a sentence and calculate:

- Number of words
- Number of characters
- Most common word

---

### Exercise 09 — Password Validator

Create a program that checks whether a password:

- Has at least 8 characters
- Contains a number
- Contains an uppercase letter
- Contains a lowercase letter

---

### Exercise 10 — Simple To-Do CLI

Create a command-line application allowing the user to:

```text
1. Add task
2. View tasks
3. Remove task
4. Exit
```

Store tasks in a Python list.

---

# 🚀 Phase Project

## Project: Python CLI Expense Tracker

Build a command-line expense tracker.

### Features

- [ ] Add expense
- [ ] View expenses
- [ ] Delete expense
- [ ] Calculate total spending
- [ ] Categorize expenses
- [ ] Show spending by category
- [ ] Validate user input

Example:

```text
===== Expense Tracker =====

1. Add Expense
2. View Expenses
3. Delete Expense
4. Show Total
5. Show By Category
6. Exit
```

Do not use a database yet.

Store the data in Python data structures.

---

# 🧠 Knowledge Check

Before moving to Phase 2, I should be able to explain:

- [ ] Difference between list, tuple, set, and dictionary
- [ ] Mutable vs immutable objects
- [ ] `==` vs `is`
- [ ] `return` vs `print`
- [ ] Function parameters vs arguments
- [ ] How loops work
- [ ] How dictionaries work
- [ ] How indexing and slicing work
- [ ] How Python handles indentation
- [ ] How to read a basic Python traceback

---

# ✅ Phase Completion Criteria

Phase 1 is complete when:

- [ ] All topics are understood
- [ ] All exercises are completed
- [ ] CLI Expense Tracker is completed
- [ ] Code is pushed to GitHub
- [ ] I can write basic Python without following a tutorial
- [ ] I can read simple Python code
- [ ] I can debug basic Python errors

---

# ➡️ Next Phase

After completing Phase 1:

**Phase 2 — Python Programming**

Topics will include:

```text
Advanced Functions
Comprehensions
*args / **kwargs
Modules
Packages
Exceptions
Files
JSON
Type Hints
Decorators
Generators
Iterators
```

---

## Principle

> Learn the concept → write code without looking at the solution → make mistakes → debug → commit to GitHub.

The objective is understanding, not completing checkboxes.