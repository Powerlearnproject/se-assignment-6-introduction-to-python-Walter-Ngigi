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

11. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


