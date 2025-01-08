# Introduction to Loops in Python
Loops in Python are used to repeat a block of code multiple times. Python supports two main types of loops:

**1. For Loop**

**2. While Loop**

## While Loop in Python
A while loop is used to execute a block of code as long as a condition is true.

**Syntax:**
```
while condition:
    # Code to execute
```
 **Example**:  Print numbers from 1 to 5 using a while loop.
```
count = 1
while count <= 5:
    print(count)
    count += 1
```
## Break Statement
The break statement is used to exit a loop prematurely when a certain condition is met.

 **Example**: Exit the loop when the number reaches 3.
```
count = 1
while count <= 5:
    if count == 3:
        break
    print(count)
    count += 1
```
##  Continue Statement
The continue statement skips the rest of the code inside the loop for the current iteration and moves to the next iteration.

**Example**: Skip printing the number 3.
```
count = 1
while count <= 5:
    if count == 3:
        count += 1
        continue
    print(count)
    count += 1

```
##  Nested While Loops
A nested while loop means having a while loop inside another while loop.

**Example**: Print a pattern using nested loops.
```
i = 1
while i <= 3:
    j = 1
    while j <= 3:
        print(f"i = {i}, j = {j}")
        j += 1
    i += 1
```

## Take User Input Using While Loops
You can use a while loop to repeatedly take user input until a condition is met.

 **Example**: Keep asking for a number until the user enters 0.
```
while True:
    num = int(input("Enter a number (0 to stop): "))
    if num == 0:
        print("Exiting the loop.")
        break
    print(f"You entered: {num}")
```
