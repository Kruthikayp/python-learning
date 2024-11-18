### 1. Lists in Python
A list is a collection of items in a particular order. Lists are mutable, meaning you can change their contents. Lists are defined using square brackets [].
#### Example:

```
# Creating a list of fruits
fruits = ["apple", "banana", "cherry"]
print(fruits)   # Output : ['apple', 'banana', 'cherry']
```
### 2. List Indexing
Each item in a list has an index that starts from 0. You can access items using their index.

#### Example:
```
# Accessing items by index
print(fruits[0])  # Output: apple
print(fruits[1])  # Output: banana
print(fruits[-1]) # Output: cherry (last item)
```
### 3. List Operations
You can perform different operations on lists, like adding, removing, or joining lists.

+ Concatenation (+): Joining two lists.
+ Repetition (*): Repeating a list multiple times.

##### Example:
```
# List operations
numbers = [1, 2, 3]
letters = ['a', 'b', 'c']

# Concatenation
combined = numbers + letters
print(combined)  # Output: [1, 2, 3, 'a', 'b', 'c']

# Repetition
print(numbers * 2)  # Output: [1, 2, 3, 1, 2, 3]
```
### 4. Slicing the List
Slicing allows you to get a part of the list using the format list[start:end]. The start index is inclusive, while the end index is exclusive.

#### Example:
```
# Slicing a list
print(fruits[0:2])  # Output: ['apple', 'banana']
print(fruits[1:])   # Output: ['banana', 'cherry']
print(fruits[:2])   # Output: ['apple', 'banana']
```
### 5. List Functions
Python provides several built-in functions to work with lists.

+ len(): Returns the length of the list.
+ max(): Returns the maximum value.
+ min(): Returns the minimum value.
+ sum(): Returns the sum of all elements (only for numerical lists).

#### Example:
```
numbers = [10, 20, 30, 40]

print(len(numbers))  # Output: 4
print(max(numbers))  # Output: 40
print(min(numbers))  # Output: 10
print(sum(numbers))  # Output: 100
```
### 6. List Methods
Lists come with various methods to modify their contents.

+ append(): Adds an item to the end of the list.
+ insert(): Inserts an item at a specific index.
+ remove(): Removes the first occurrence of an item.
+ pop(): Removes an item by index and returns it.
+ sort(): Sorts the list in ascending order.
+ reverse(): Reverses the list order.
```
# Using list methods
fruits.append("orange")
print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']

fruits.remove("banana")
print(fruits)  # Output: ['apple', 'cherry', 'orange']

fruits.sort()
print(fruits)  # Output: ['apple', 'cherry', 'orange']

fruits.reverse()
print(fruits)  # Output: ['orange', 'cherry', 'apple']
```
### 7. Nested Lists / Matrices
A nested list is a list within a list, useful for representing matrices or tables.
#### Example:
```
# Creating a nested list (2D list)
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
# Accessing elements in a nested list
print(matrix[0][1])  # Output: 2 (first row, second column)
print(matrix[2])     # Output: [7, 8, 9] (third row)
```
**PRACTICE TIME**
"Keep coding, keep exploring, and let Python be your path to innovation."

**Task 1**: Create and Manipulate Lists
+ Create a list named cities containing at least 5 different city names (e.g., "Paris", "London", "New York").
+ Print the list of cities.
+ Use indexing to print the first and last city in the list.
+ Use slicing to print the first three cities.

**Task 2:** Perform List Operations
+ Create two lists:
+ numbers = [10, 20, 30, 40, 50]
+ colors = ["red", "green", "blue"]
+ Concatenate the numbers and colors lists into a new list called combined_list and print it.
+ Repeat the colors list 3 times and print the result.

**Task 3**: Use List Functions
+ Use the len() function to find the number of elements in the numbers list.
+ Use max() and min() to find the maximum and minimum values in the numbers list.
+ Calculate the sum of all numbers in the numbers list using the sum() function.

**Task 4**: Apply List Methods
+ Create an empty list called shopping_list.
+ Add the following items to the list using the append() method: "milk", "eggs", "bread".
+ Insert "butter" at the beginning of the list using the insert() method.
+ Remove "eggs" from the list using the remove() method.
+ Sort the list in alphabetical order using the sort() method.
+ Reverse the list order using the reverse() method.
+ Print the final shopping_list.


