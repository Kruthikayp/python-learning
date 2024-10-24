### Assigning Multiple Variables with Different Values
You can assign different values to multiple variables by separating both the variables and the values with commas.

**Example**:
```
x, y, z = 10, 20, 30
print(x)  # Output: 10
print(y)  # Output: 20
print(z)  # Output: 30
```
### Assigning the Same Value to Multiple Variables
You can also assign the same value to multiple variables by separating the variables with =.

**Example:**
```a = b = c = 100
print(a)  # Output: 100
print(b)  # Output: 100
print(c)  # Output: 100
```
### Unpacking a List or Tuple to Variables
Python also allows you to "unpack" a list or a tuple directly into variables. This is useful when you have a collection of values and want to assign them to individual variables.

**Example (with tuple)**:
```
data = (5, 10, 15)
x, y, z = data
print(x)  # Output: 5
print(y)  # Output: 10
print(z)  # Output: 15
```
**Example (with list)**:
```
values = [1, 2, 3]
a, b, c = values
print(a)  # Output: 1
print(b)  # Output: 2
print(c)  # Output: 
```
 ### Swapping Values Between Two Variables
Python allows you to easily swap the values of two variables without needing a temporary variable.

**Example:**
```
x = 5
y = 10
x, y = y, x
print(x)  # Output: 10
print(y)  # Output: 5
```
### Variable Reassignment in Python
Variable reassignment means changing the value of an already defined variable. In Python, variables are dynamic, meaning you can change the type and value of a variable at any point during the program.

### How Reassignment Works:
When you assign a value to a variable and later assign a new value to the same variable, the previous value is replaced by the new one. Python automatically manages memory, so the old value is discarded if it's no longer used.

### Example of Variable Reassignment:
```
x = 10      # Initial assignment
print(x)    # Output: 10

x = 20      # Reassigning a new value to x
print(x)    # Output: 20

x = "Hello"  # Reassigning with a different data type (string)
print(x)     # Output: Hello
```
### Reassigning to a Different Data Type:
One of Python's strengths is its flexibility in allowing you to change the data type of a variable without any restrictions.

**Example**:
```
y = 15          # 'y' is initially an integer
print(type(y))  # Output: <class 'int'>

y = 3.14        # Now, 'y' is reassigned as a float
print(type(y))  # Output: <class 'float'>

y = "Python"    # Now, 'y' is reassigned as a string
print(type(y))  # Output: <class 'str'>
```
### Reassignment with Arithmetic Operations:
You can also reassign a variable's value using its current value in an arithmetic operation.

**Example:**
```
z = 5
z = z + 10   # Reassigns 'z' to its current value plus 10
print(z)     # Output: 15

# Shortcut for the same operation
z += 5     # Equivalent to z = z + 5
print(z)   # Output: 20
```
### Input and Output in Python 
**Input:**
The input() function allows users to provide input. It always returns the input as a string.

**Example**:
```
name = input("Enter your name: ")
print("Hello, " + name + "!")
```
**Output:**
The print() function is used to display output in Python.

**Example:**
```
print("This is an output example!")
```
### Formatted Strings 
Formatted strings make it easy to include variables inside strings. You can use the f"" format to create formatted strings.

**Example:**
```
name = "kruthika"
age = 30
print(f"My name is {name}, and I am {age} years old.")
```
### Absolute Value Function 
The abs() function returns the absolute value of a number (i.e., it removes the negative sign from numbers).

**Example:**
```
num = -15
print(abs(num))  # Output: 15
```
### Comments in Python 
Single-line comments are created using the # symbol. They are ignored by the Python interpreter and are used for documentation.

**Example:**
```
# This is a single-line comment
print("This code runs, the comment is ignored")
```
### Multi-line Comments
Multi-line comments can be written using triple quotes ''' or """. They are generally used for block comments or docstrings in Python.

**Example:**
```
"""
This is a multi-line comment.
It's useful for writing longer comments or documentation.
"""
print("Code after multi-line comment")
```

