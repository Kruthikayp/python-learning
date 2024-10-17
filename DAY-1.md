# Self-Learning Python Journey - Day 1

## Introduction
This repository documents my self-learning journey in Python programming. I aim to develop a strong foundation in Python and explore its various applications.

## What is Coding?
Coding is the process of creating instructions for computers using programming languages. It involves writing code to perform specific tasks or solve problems. Coding is essential for developing software, websites, applications, and more.

**Example**: Writing a simple greeting in Python.
```python
print("Hello, World!")
```
## What is python?
Python is a high-level, interpreted programming language known for its simplicity and readability. It's widely used for web development, data analysis, artificial intelligence, scientific computing, and more.

**Example**: A basic Python program that adds two numbers.
```# Adding two numbers
a = 5
b = 3
sum = a + b
print("The sum is:", sum)
```
## What is an Interpreted Language?
An interpreted language is one where the code is executed line by line at runtime. This means that the source code is translated into machine code on the fly, allowing for immediate feedback and easier debugging.

**Example**: Running a Python script directly in the interpreter.

```python
# This line will be executed immediately when written in the interpreter
print("This is an interpreted language example.")
```
## Why is Python Popular?
Python is popular for several reasons:

+ **Easy to Learn**: Its syntax is clean and easy to understand.
+ **Versatile**: Used in web development, data science, artificial intelligence, etc.
+ **Large Community**: A vast ecosystem of libraries and frameworks.
+ **Cross-Platform**: Runs on Windows, macOS, Linux, and more.

## What is a Dynamically Typed Language?
In a dynamically typed language, the type of a variable is determined at runtime, allowing you to change a variable's type during execution. This offers more flexibility but can lead to runtime errors if not handled properly.
``` # Dynamically typed variable
x = 5      # x is an integer
print(x)

x = "Hello"  # Now x is a string
print(x)
```

 ## What is a Variable?
A variable in Python is like a container that stores data values. You can think of it as a label attached to a value. The value can be changed at any time during the execution of the program.
**Example**:
``` x = 10  # Here, 'x' is a variable that stores the value 10
name = "John"  # 'name' stores the string "John"
```
## Important Rules for Naming Variables
+ Variable names should start with a letter (a-z, A-Z) or an underscore (_).
+ Variable names cannot start with a number.
+ Variable names are case-sensitive (age and Age are different).
+ Avoid using Python reserved keywords (e.g., if, else, while).
**Example**:
``` age = 25   # Valid variable name
 _age = 30  # Valid (starts with an underscore)
2days = 20  # Invalid (starts with a number)
```
## Data Types in Python
+ int (Integer): Used for whole numbers.
+ float (Floating-Point): Used for decimal numbers.
+ str (String): Used for sequences of characters (text).
+ bool (Boolean): Used for True or False values.
**Example**:
```
num = 10  # int
pi = 3.14  # float
name = "Rahul"  # string
is_active = True  # bool
```

## Type Conversion Techniques
Type conversion is the process of converting one data type to another, like converting an integer to a string or vice versa.

**Techniques**:
+ int(): Converts a value to an integer.
+ float(): Converts a value to a floating-point number.
+ str(): Converts a value to a string.
**Example**:
```
x = 5  # int
y = float(x)  # Converts x to float (y will be 5.0)
```
```
num_str = "100"
num_int = int(num_str)  # Converts string to integer (100)
```
## Operators Explained
Arithmetic operators in Python are used to perform basic mathematical operations like addition, subtraction, multiplication, and division.

 Operator   |     Description          | Example      |
| --------- | ------------------------ | ------------ |
|     +     | Addition                 | 5 + 3 = 8    |          
|     -     | Subtraction              | 5 - 3 = 2    |
|     *     | Multiplication           | 5 * 3 = 15   |
|     /     | Division (float result)  | 5 / 2 = 2.5  |
|    //	    | Floor Division           | 5 // 2 = 2   |
|     %     | Modulus (remainder)	     | 5 % 2 = 1    |
|    **     |	Exponentiation (power)   | 2 ** 3 = 8   |

**Example**:
```
a = 10
b = 3
print(a + b)  # Output: 13
print(a - b)  # Output: 7
print(a * b)  # Output: 30
print(a / b)  # Output: 3.33 (float division)
print(a // b)  # Output: 3 (floor division)
print(a % b)  # Output: 1 (remainder)
print(a ** b)  # Output: 1000 (exponentiation)
```
## practice Time :
### "Practice makes progress, not perfection." 
The more you practice, the better you become. Python programming is no different. Each task is a step towards mastery.

## Task 1: Variable Assignment and Reassignment
**Objective**:
Practice assigning and reassigning values to variables of different data types.

**Instructions**:
+ Create variables to store an integer, a float, a string, and a boolean.
+ Reassign each variable to a new value with a different data type.
+ Print each variable's value and data type before and after reassignment using the type() function.

 ## Task 2: Basic Arithmetic Operations
**Objective**:
Use arithmetic operators to perform mathematical calculations.

**Instructions:**
+ Create two variables a and b and assign them integer values.
+ Perform the following arithmetic operations between a and b: addition, subtraction, multiplication, division, modulus, and exponentiation.
+ Print the results of each operation.

## Task 3 : Variable Naming Rules
**Objective**: Follow proper naming conventions and avoid reserved keywords.
**Instructions**:
+ Create variables following these rules:
+ One variable that starts with an underscore.
+ One variable with a descriptive name (e.g., user_age).
+ One invalid variable (e.g., starting with a number).
+ Write a comment explaining why the invalid variable name is incorrect.

## Task 3: Type Conversion Practice
**Objective**: Practice type conversion techniques.
**Instructions**:
+ Create three variables: a (string of a number), b (float), and c (integer).
+ Convert the string a to an integer and add it to c.
+ Convert b to an integer and multiply it by c.
+ Convert the result of each operation back to a string and print the results.

 ## Task 5: Python as an Interpreted Language
**Objective**: Understand how Python is interpreted line by line.
**Instructions**:
+ Write a Python script that contains a series of print statements.
+ In between the print statements, insert invalid lines of code (with comments) to see that Python executes code line by line and stops when an error is encountered.
+ After each valid print statement, show how Python stops when it hits an error.



