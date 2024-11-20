### Introduction
Python provides various data structures to store and organize data. Three common ones are Lists, Tuples, and Sets. Each has unique characteristics and use cases.

### Difference Between Lists and Tuples

|   Feature       |            	List               |        	Tuple              |
|-----------------|--------------------------------|-----------------------------|
|   Mutability    |	Mutable (can be changed)       |	Immutable (cannot change)  |
|   Syntax        |	Square brackets [ ]            |	Parentheses ( )            |
|  Performance    |	Slower (because of mutability) |	Faster                     |

**Example:**
```
# List
fruits_list = ["apple", "banana", "cherry"]
fruits_list[1] = "orange"  # You can change items
print(fruits_list)  # Output: ['apple', 'orange', 'cherry']

# Tuple
fruits_tuple = ("apple", "banana", "cherry")
# fruits_tuple[1] = "orange"  # This will raise an error
print(fruits_tuple)  # Output: ('apple', 'banana', 'cherry')
```

###  Tuple in Python
A tuple is an ordered collection of elements, which is immutable.

**Example:**
```
my_tuple = (1, 2, 3, 4)
print(my_tuple)  # Output: (1, 2, 3, 4)
```
### Tuple Methods
Tuples have limited methods because they cannot be modified.

+ count(): Counts the occurrences of a value.
+ index(): Finds the index of a value.
  
**Example:**
```
numbers = (1, 2, 2, 3, 4)
print(numbers.count(2))  # Output: 2
print(numbers.index(3))  # Output: 3
```
### Advantages of Using Tuple
+ **Immutability**: Ensures data integrity.
+ **Performance:** Faster than lists.
+ **Storage:** Requires less memory than lists.
  
### Sets in Python
A set is an unordered collection of unique elements.

**Example:**
```
my_set = {1, 2, 3, 4}
print(my_set)  # Output: {1, 2, 3, 4}
```
### Set Operations
+ **Union (|)**: Combines all unique elements.
+ **Intersection (&)**: Finds common elements.
+ **Difference (-)**: Finds elements in one set but not the other.

**Example**:
```
set1 = {1, 2, 3}
set2 = {3, 4, 5}
print(set1 | set2)  # Union: {1, 2, 3, 4, 5}
print(set1 & set2)  # Intersection: {3}
print(set1 - set2)  # Difference: {1, 2}
```
### Set Methods
+ **add()**: Adds an element.
+ **remove()**: Removes an element.
+ **discard()**: Removes an element without an error if it doesn't exist.
  
**Example:**
```
my_set = {1, 2, 3}
my_set.add(4)  # Adds 4
print(my_set)  # Output: {1, 2, 3, 4}

my_set.remove(2)  # Removes 2
print(my_set)  # Output: {1, 3, 4}
```
### Difference Between Lists, Tuples, and Sets

|  Feature	     |       List        | 	 Tuple      |     Set      |
|----------------|-------------------|--------------|--------------|
|  Order	       |     Ordered	     |  Ordered	    |  Unordered   |
| Mutability     |  	 Mutable       |  Immutable   | 	Mutable    |
| Duplicates	   |     Allowed	     |  Allowed     |  Not Allowed |
|  Syntax        |      	[ ]        |	   ( )      |     	{ }    |

**Example:**
```
# List
my_list = [1, 2, 3, 3]
print(my_list)  # Output: [1, 2, 3, 3]

# Tuple
my_tuple = (1, 2, 3, 3)
print(my_tuple)  # Output: (1, 2, 3, 3)

# Set
my_set = {1, 2, 3, 3}
print(my_set)  # Output: {1, 2, 3}
```
## "Dont't just learn Python; create with it. Make your code tell a story."
### 1. Tasks for Lists
####  Create and Modify a List
+ Create a list of 5 fruits.
+ Replace the second fruit with "Mango".
+ Add a new fruit to the end of the list.
+ Remove the last fruit.

### 2. Tasks for Tuples
#### Tuple Operations
+ Create a tuple of 5 numbers.
+ Find the index of the number 3.
+ Count how many times the number 2 appears in the tuple.
+ Attempt to change an element (observe the error).

### 3. Tasks for Sets
####  Set Operations
+ Create two sets: set1 = {1, 2, 3, 4} and set2 = {3, 4, 5, 6}.
+ Perform the following operations:
+ Union
+ Intersection
+ Difference (set1 - set2 and set2 - set1)
  
### 4. Set Methods Practice
+ Create a set with numbers {1, 2, 3}.
+ Add a new number 4.
+ Try to discard a number 5 and observe the behavior.
+ Try to remove a number 5 and handle the error gracefully using a try-except block.
  
### 5. Comparison Tasks
####  Convert Between Data Types
+ Create a list of numbers [1, 2, 2, 3].
+ Convert it into a set and observe what happens.
+ Convert the set back into a list.
