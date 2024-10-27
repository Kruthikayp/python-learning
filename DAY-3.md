## Operators in Python
Operators in Python are special symbols that perform operations on variables and values. They are divided into several categories:
### 1. Assignment Operators
Assignment operators are used to assign values to variables.

|  Operator  |          Description        |       Example       | 
| ---------- | ----------------------------|---------------------|
|   =        |	Assigns value              |	x = 5              |
|   +=       | 	Adds and assigns	         |  x += 3 (x = x+3)   |
|   -=	     |  Subtracts and assigns	     |  x -= 2 (x = x-2)   |
|   *=       |	Multiplies and assigns     |  x *= 4 (x = x*4)   | 
|   /=	     |  Divides and assigns        |	x /= 2 (x = x/2)   |
|   %=	     |  Modulus and assigns	       |  x %= 3 (x = x%3)   |
|   **=	     |  Exponent and assigns	     |  x **= 2 (x = x^2)  |
|   //=      |	Floor division and assigns |	x //= 3 (x = x//3) |

### **Example:** 
Assignment operators are used to assign values to variables.
```
# Assigning initial values
x = 5   # Simple assignment
print("x =", x)  # Output: 5

x += 3  # Equivalent to x = x + 3
print("x after += 3:", x)  # Output: 8

x -= 2  # Equivalent to x = x - 2
print("x after -= 2:", x)  # Output: 6

x *= 4  # Equivalent to x = x * 4
print("x after *= 4:", x)  # Output: 24

x /= 3  # Equivalent to x = x / 3
print("x after /= 3:", x)  # Output: 8.0

x %= 5  # Equivalent to x = x % 5
print("x after %= 5:", x)  # Output: 3.0

x **= 2  # Equivalent to x = x ** 2
print("x after **= 2:", x)  # Output: 9.0

x //= 3  # Equivalent to x = x // 3
print("x after //= 3:", x)  # Output: 3.0
```

### 2. Comparison Operators
Comparison operators are used to compare values.

| Operator  |	         Description	           |    Example      |
|-----------|----------------------------------|-----------------|
|  ==	      |   Equal to	                     |    x == y       |
|  !=	      |   Not equal to                   |    x != y       |
|  >	      |   Greater than                   |    x > y        |
|  <	      |   Less than	                     |    x < y        |
|  >=       |   Greater than or equal to	     |    x >= y       |
|  <=	      |   Less than or equal to	         |    x <= y       |

**Example:**

Comparison operators compare values and return **True** or **False**.

```
a = 10
b = 20

print("a == b:", a == b)  # Equal to - Output: False
print("a != b:", a != b)  # Not equal to - Output: True
print("a > b:", a > b)    # Greater than - Output: False
print("a < b:", a < b)    # Less than - Output: True
print("a >= b:", a >= b)  # Greater than or equal to - Output: False
print("a <= b:", a <= b)  # Less than or equal to - Output: True
```
### 3. Logical Operators
Logical operators are used to combine conditional statements.

|  Operator	|            Description                        |	    Example       |
|-----------|-----------------------------------------------|-------------------|
| and     	|Returns True if both statements are true	      |(x > 5 and y < 10) |
| or	      |Returns True if one of the statements is true	|(x > 5 or y < 10)  |
| not     	|Reverses the result, True if false	not         |(x > 5)            |

**Example:**
Logical operators are used to combine multiple conditions.
```
x = 5
y = 10

print("(x > 0 and y < 20):", (x > 0 and y < 20))  # Output: True (Both conditions are true)
print("(x > 10 or y < 20):", (x > 10 or y < 20))  # Output: True (One condition is true)
print("not(x > 0):", not(x > 0))                 # Output: False (Reverses the result)
```
### 4. Membership Operators
Membership operators check for membership in sequences like strings, lists, or tuples.

| Operator |	               Description                           |       Example           |
|----------|-------------------------------------------------------|-------------------------|
|  in      |	Returns True if a value is found in a sequence	     |   'a' in 'apple'        |
|  not     | in	Returns True if a value is not found in a sequence |	 'b' not in 'apple'    |

**Example:**
Membership operators check if a value is part of a sequence.
```
a = "kruthika"
a2 = "kruthikayp"

print("p" in a2)    # Output:true
print("k" in a)     # Output:true
print("y" in a)     # Output:false
print("a" in a2)    # Output:true
```
### 5. Bitwise Operators
Bitwise operators work on bits and perform operations at the bit level.

|   Operator  |    Description        |	Example |
|-------------|-----------------------|---------|
|     &       |     	AND	            |  x & y  |
|     `       |      	`	              |   OR    |
|     ^       |     	XOR	            |  x ^ y  |
|     ~       |     	NOT	            |   ~x    |
|    <<	      |  Zero fill left shift |	x << 2  |
|    >>	      |  Signed right shift   |	x >> 2  |

**Example**:

Bitwise operators perform operations on binary representations of integers.
```
a = 10  # Binary: 1010
b = 4   # Binary: 0100

print("a & b (AND):", a & b)            # Output: 0 (Binary: 0000)
print("a | b (OR):", a | b)            # Output: 14 (Binary: 1110)
print("a ^ b (XOR):", a ^ b)           # Output: 14 (Binary: 1110)
print("~a (NOT):", ~a)                 # Output: -11 (Inverts all bits)
print("a << 2 (Left Shift):", a << 2)  # Output: 40 (Binary: 101000)
print("a >> 2 (Right Shift):", a >> 2) # Output: 2 (Binary: 0010)
```
### **TASK:**
## "Every line of Python you write brings you one step closer to mastering it."

#### 1. Assignment Operators Task:
Create a variable a and perform different assignment operations (+=, -=, *=, /=) and print the results.

#### 2. Comparison Operators Task:
Write a function that compares two numbers and returns which one is larger, smaller, or if they are equal.

#### 3. Logical Operators Task:
Create a function that takes two boolean values and returns their logical and, or, and not values.

#### 4. Membership Operators Task:
Check if a specific element is present in a list or not using in and not in.

#### 5. Bitwise Operators Task:
Perform bitwise operations between two numbers (e.g., 10 and 4) and print the result.

