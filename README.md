[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15340099&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
  
   - python is a programming language,it is one of the most used programming language in the world. Some of it's key features that make ir popular among developers is it's simple syntax, it's easy to read and therefore easy to understand which makes it  a good first language for developers. It also has a wide variety of application and it's not limited to a specific domain or area of software development, this flexibility is part of why it is popular since it can be used for anything, from web development to data analysis to even game development. Python is written line by line making it easier to debug, not to mention that it can also be used in various operating systems such as Windows, Mac and Linux.
   - 

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
Python can be downloaded through the "Pyhton.org" website. The website gives clear instructions and guidlines for the installation process, including how and where to download python for various operating systems. Once downloaded, you need to set up the virtual environment, for this you need to go to "environment variable" control panel and add the path to Python. After this is done you need to go to your code editor of choice eg. Visual Studio Code which is conscidered the industry standard. In your code editor you need to dowload the Python extensions.
To verify the installation, you open command prompt and enter the command "python --ver" if the install and set up was succesfull this command should give your python version as the output.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   -                   STEP ONE, WRITING THE CODE
   -  To write this simple program first we need to go to our code editor eg, visual studio code, then click new file and choose python file in the drop menu that pops up.
   -  The next part will be writing the actual code fot the program which is
   -          print("Hello, World!")
   - after writing the code and checking that there are no errors in your code, click run program from the top right button that looks like a "play" button. This action will run your program in the terminal and display your message.
   -                   BASIC SYNTAX ELEMENTS USED
   - The first syntax element is the print function this ouputs data to the console. 
   - The second syntax element is the quotation, this can be single or single.The quotation marks represent the string literals. a string can contain letters, numbers or symbols. Tripple 
     quotation marks can be used to define multiple line strings.
     The third syntax element is, The parentheses () , they are used to enclose the arguments passed to the print() function.

4. Data Types and Variables:
   -1. List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   -                  BASIC DATA TYPES USED IN PYTHON
   - 2.STRINGS ('str'): strings contain letters, numbers or symbols enclosed in quotation marks.
   - 3.INTEGER ('int'): This are whole numbers. This can be positive or negative.
   -4. FLOATING POINT (float): This are numbers with decimal points.
   -5.OLEANS ('bool'): Booleans represent truth values, they can either be true or false.
   -6. LIST:('list'): This represents an ordred changable collection of items. It is denoted by square brackets [], a 'list' can be changed, we can add remove or modify the contents of this data type.
      7.TUPLE ('tuple'): Just like lists, tuples contain a collection of items, but unlike lists, this cannot be changed or modified after implementation. they are denoted by the parenthesis().
   8. SET ('set'):  A set is a collection which is unordered, unchangeable*, and unindexed. * Note: Set items are unchangeable, but you can remove items and add new items. Sets are denoted by curly brackets {} or by using the 'set()' function when creating an empty set.
   9. DICTIONARY ('dict'):Unordered, mutable collection of key-value pairs.Example: {'name': 'Alice', 'age': 25}
  
       
                  SCRIPT SHOWING DIFFERENT VARIABLES
      # String: to store the name of the expense
expense_name = "Groceries"

# Float: to store the amount spent
expense_amount = 123.45

# String: to store the date of the expense
expense_date = "2023-06-28"

# Boolean: to indicate whether the expense is recurring
is_recurring = True

# List: to store multiple expense categories
expense_categories = ["Groceries", "Utilities", "Rent", "Entertainment"]

# Dictionary: to store expenses with their respective amounts
expenses = {
    "Groceries": 123.45,
    "Utilities": 75.00,
    "Rent": 950.00,
    "Entertainment": 50.00
}

# Print out the expense details
print("Expense Tracker")
print("=================")
print(f"Expense Name: {expense_name}")
print(f"Expense Amount: ${expense_amount}")
print(f"Expense Date: {expense_date}")
print(f"Is Recurring: {is_recurring}")
print(f"Expense Categories: {expense_categories}")
print(f"Expenses: {expenses}")

# Example of accessing and modifying dictionary elements
new_expense = "Transportation"
new_expense_amount = 40.00
expenses[new_expense] = new_expense_amount

print("\nUpdated Expenses:")
for category, amount in expenses.items():
    print(f"{category}: ${amount}")

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop
   - Conditional statements allow you to execute different blocks of code based on certain conditions. Eg.
   - 
                                           age = 20
                                        if age >= 18:
                                       print("Access granted.")
                                            else:
                                       print("Access denied. You must be at least 18 years old.")
   - Loops are used to execute a block of code repeatedly as long as a certain condition is met. The primary loops in Python are for and while loops.
   -                                        count = 0
                                           while count < 5:
                                           print("Count:", count)
                                           count += 1

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   - In Python, functions are blocks of reusable code that perform a specific task. They allow you to break down your program into smaller, manageable pieces, making your code more organized, readable, and easier to maintain. Functions also promote code reusability by enabling you to call the same functionality multiple times without rewriting it, which enhances efficiency and reduces redundancy in your programs.
   - 
   -                               def sum_strings(str1, str2):
                                        return str1 + str2
                                  str1 = "PLP is a great institution"
                                  str2 = " the learning experience is very interactive"
                                  result = sum_strings (str1, str2)
                                  print(result)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   - LISTS: Lists in Python are a data type that represent an ordered changable/ mutable collection of items that can be of different types (integers, strings, objects, etc.).
   - DICTIONARIES: Dictionaries in Python are a data type that represents unordered collection of items where each item is stored as a key-value pair.
   - DIFFERENCES BETWEEN THE TWO:
   -  Lists as stated above are ordered, they mention the order of items as added. Dictionaries on the other hand are not ordered, they do not maintain the order of items.
   -  Items in a list can be accessed using their index (position in the list), starting from 0. Each item in a dictionary has a key and a value. Keys must be unique and immutable (such as strings, numbers, or tuples), while values can be of any type, items are accessed using keys, not indexes.
   -                                                 SCRIPT:
   -                                             # Script 1: Basic List and Dictionary Operations

# Creating a list of numbers
numbers = [1, 2, 3, 4, 5]

# Creating a dictionary with key-value pairs
student = {
    'name': 'John Doe',
    'age': 20,
    'major': 'Computer Science'
}

# Basic list operations
print("Original list:", numbers)
numbers.append(6)  # Adding an item
print("List after append:", numbers)
numbers.remove(3)  # Removing an item
print("List after remove:", numbers)
print("First item in the list:", numbers[0])  # Accessing by index

# Basic dictionary operations
print("\nOriginal dictionary:", student)
student['age'] = 21  # Modifying a value
print("Dictionary after modifying 'age':", student)
student['email'] = 'john.doe@example.com'  # Adding a new key-value pair
print("Dictionary after adding 'email':", student)
del student['major']  # Removing a key-value pair
print("Dictionary after removing 'major':", student)
print("Student's name:", student['name'])  # Accessing by key


9. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   - Exception handling in Python is a way to manage errors and exceptions that occur during program execution. It allows a program to continue running or gracefully terminate instead of crashing abruptly when an error occurs. This is achieved using `try`, `except`, `finally`, and optionally `else` blocks. 

- `try` block:** Contains the code that might raise an exception.
- `except` block:** Contains the code that runs if an exception occurs in the `try` block.
- `finally` block:** Contains the code that will always run, regardless of whether an exception occurred or not.
- `else` block (optional):** Contains the code that will run if no exceptions occur in the `try` block.
- EXAMPLE
- ```python
def divide_numbers(num1, num2):
    try:
        # Attempt to divide the two numbers
        result = num1 / num2
    except ZeroDivisionError as e:
        # Handle the division by zero error
        print(f"Error: Cannot divide by zero. {e}")
        result = None
    except TypeError as e:
        # Handle the type error if non-numeric values are passed
        print(f"Error: Invalid input types. {e}")
        result = None
    else:
        # Code to execute if no exceptions occur
        print("Division successful.")
    finally:
        # Code that will always execute
        print("Execution of the division operation is complete.")
    return result

# Test cases
print(divide_numbers(10, 2))  # Should print: Division successful. 5.0 Execution of the division operation is complete.
print(divide_numbers(10, 0))  # Should print: Error: Cannot divide by zero. division by zero Execution of the division operation is complete.
print(divide_numbers(10, 'a'))  # Should print: Error: Invalid input types. unsupported operand type(s) for /: 'int' and 'str' Execution of the division operation is complete.
```

 Explanation

- **`try` block:** Attempts to divide `num1` by `num2`. If this succeeds, it moves to the `else` block.
- **`except` block for `ZeroDivisionError`:** Catches the specific `ZeroDivisionError` if `num2` is zero and prints an error message.
- **`except` block for `TypeError`:** Catches the specific `TypeError` if either of the inputs is not a number and prints an error message.
- **`else` block:** Executes only if no exceptions were raised in the `try` block, indicating a successful division.
- **`finally` block:** Always executes, regardless of whether an exception was raised or not. It is used to perform cleanup actions, like closing files or releasing resources.

This structure ensures that your program can handle errors gracefully and perform any necessary cleanup before continuing execution or terminating.

10. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
### Modules and Packages in Python

#### Modules

A module in Python is a single file (with a `.py` extension) that contains definitions, functions, classes, and variables. Modules are used to organize and reuse code. Instead of writing all code in a single file, you can write different pieces of functionality in different modules and then import them into your main program.

**Example of a simple module (greetings.py):**
```python
def say_hello(name):
    return f"Hello, {name}!"

def say_goodbye(name):
    return f"Goodbye, {name}!"
```

#### Packages

A package is a way to organize multiple modules in a directory hierarchy. A package is a directory that contains a special `__init__.py` file (which can be empty) and one or more module files. This structure allows you to group related modules together and import them as a single package.

**Example of a package structure:**
```
mypackage/
    __init__.py
    module1.py
    module2.py
```

#### Importing and Using a Module

To use a module in your script, you need to import it. You can import the entire module or specific functions/classes from the module.

**Example using the `math` module:**

The `math` module is a built-in module in Python that provides mathematical functions.

1. **Importing the entire module:**

```python
import math

# Using a function from the math module
result = math.sqrt(16)
print(result)  # Output: 4.0
```

2. **Importing specific functions from the module:**

```python
from math import sqrt, pi

# Using the imported functions and variables
result = sqrt(16)
print(result)  # Output: 4.0

print(pi)  # Output: 3.141592653589793
```

### Example Code Using the `math` Module

Here's a complete example demonstrating how to use the `math` module in a script:

```python
import math

def calculate_circle_area(radius):
    """Calculate the area of a circle given its radius."""
    return math.pi * math.pow(radius, 2)

def calculate_square_root(number):
    """Calculate the square root of a given number."""
    return math.sqrt(number)

# Example usage
radius = 5
circle_area = calculate_circle_area(radius)
print(f"The area of a circle with radius {radius} is {circle_area}")

number = 25
square_root = calculate_square_root(number)
print(f"The square root of {number} is {square_root}")
```

### Explanation

- **Importing the Module:**
  - `import math`: This imports the entire `math` module.
- **Using Functions from the Module:**
  - `math.pi`: This accesses the constant π (pi) from the `math` module.
  - `math.pow(x, y)`: This function returns x raised to the power y.
  - `math.sqrt(x)`: This function returns the square root of x.
- **Example Functions:**
  - `calculate_circle_area(radius)`: Uses `math.pi` and `math.pow` to calculate the area of a circle.
  - `calculate_square_root(number)`: Uses `math.sqrt` to calculate the square root of a number.

This approach allows you to organize your code more efficiently, reuse functionality, and keep your codebase manageable.

11. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    - ### Reading from and Writing to Files in Python

#### Reading from a File

To read from a file in Python, you use the built-in `open()` function to open the file and then read its content. After you are done reading the file, it is important to close the file using the `close()` method or use a `with` statement that automatically closes the file for you.

**Example: Reading the content of a file and printing it to the console:**

```python
# Reading the content of a file and printing it to the console

# Using with statement which automatically closes the file after reading
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
```

#### Writing to a File

To write to a file in Python, you also use the `open()` function but with a mode that allows writing, such as `'w'` (write mode) or `'a'` (append mode). Writing in `'w'` mode will overwrite the existing content, while `'a'` mode will append to the existing content.

**Example: Writing a list of strings to a file:**

```python
# Writing a list of strings to a file

lines = ["First line of text", "Second line of text", "Third line of text"]

with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')
```

### Complete Example Scripts

#### Script to Read from a File

```python
def read_file(file_path):
    """Reads the content of a file and prints it to the console."""
    try:
        with open(file_path, 'r') as file:
            content = file.read()
            print(content)
    except FileNotFoundError:
        print(f"The file {file_path} does not exist.")

# Example usage
read_file('example.txt')
```

#### Script to Write to a File

```python
def write_to_file(file_path, lines):
    """Writes a list of strings to a file."""
    with open(file_path, 'w') as file:
        for line in lines:
            file.write(line + '\n')

# Example usage
lines_to_write = ["First line of text", "Second line of text", "Third line of text"]
write_to_file('output.txt', lines_to_write)
```

### Explanation

- **Reading from a File:**
  - The `read_file` function takes a file path as an argument.
  - It uses a `with` statement to open the file in read mode (`'r'`).
  - The `read()` method reads the entire content of the file, which is then printed to the console.
  - The `try-except` block handles the `FileNotFoundError` in case the file does not exist.

- **Writing to a File:**
  - The `write_to_file` function takes a file path and a list of strings as arguments.
  - It uses a `with` statement to open the file in write mode (`'w'`).
  - It iterates through the list of strings, writing each string to the file followed by a newline character (`\n`).

These scripts demonstrate the basic operations for reading from and writing to files in Python.

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


