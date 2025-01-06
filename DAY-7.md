# Conditional Statements in Python
Conditional statements in Python include if, else, and elif. These are used to check specific conditions and perform actions accordingly.

## 1. If Statement
The if statement executes a block of code if a condition is True.

Example:
```
age = 18
if age >= 18:
    print("You are eligible to vote.")
```
## 2. Indentation in Python
Python uses indentation (spaces or tabs) to define code blocks instead of braces {}. Proper indentation is mandatory.

Example:
```
number = 5
if number > 0:
    print("Positive number")
    print("This is inside the if block.")
```
## 3. Else Statement
The else block executes if the if condition is False.

Example:
``
age = 16
if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")
    ```
## 4. Elif Statement
The elif statement checks multiple conditions after the if statement.

Example:
```
marks = 75
if marks >= 85:
    print("Grade: A")
elif marks >= 60:
    print("Grade: B")
else:
    print("Grade: C")
```
## 5. Using Logical Operators
Logical operators like and, or, and not combine multiple conditions.

Example:
```
age = 25
citizen = True
if age >= 18 and citizen:
    print("You can apply for a driving license.")
else:
    print("You cannot apply for a driving license.")
```
 Example:  KSRTC Bus Ticket
 
Let’s check ticket eligibility for a KSRTC bus:

```
age = int(input("Enter your age: "))
if age < 5:
    print("Ticket: Free for children under 5.")
elif age <= 60:
    print("Ticket: Regular fare applies.")
else:
    print("Ticket: Discount for senior citizens.")
```
## 6. Nested If-Else
A nested if-else is an if-else block inside another if-else.

Example:
```
number = int(input("Enter a number: "))
if number >= 0:
    if number == 0:
        print("The number is zero.")
    else:
        print("The number is positive.")
else:
    print("The number is negative.")
```

##  "Programming isn't about what you know; it's about what you can figure out."
### – Take each task as an opportunity to learn and discover!

# TASKS :
### 1. Check Eligibility to Work
Write a program to check if a person is eligible to work. The age should be between 18 and 60.
### Hint:
Use an if-elif-else statement to check the age.
Include conditions like age < 18, 18 <= age <= 60, and age > 60.

### 2.  Identify Positive, Negative, or Zero
Ask the user to input a number and identify whether it's positive, negative, or zero.
### Hint:
Use nested if-else statements.
First, check if the number is >= 0. Then, check if it's zero.

### 3. Calculate Ticket Price
For a KSRTC bus:

Free for children under 5.
Regular fare for ages 5 to 60.
Senior citizens get a discount.
### Hint:
Use if-elif-else statements.
Take the age as input and apply conditions.

### 4. Determine the Grade
Input marks from the user and assign grades:

A for marks >= 85
B for marks 60–84
C for marks < 60
### Hint:
Use elif for the range checks.

### 5.  Check Driving Eligibility
Check if a person can apply for a driving license:

Age must be 18 or above.
Must be a citizen (True or False).
### Hint:

Use logical operators (and) to combine conditions.

