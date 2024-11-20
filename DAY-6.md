##  Let's Learn About Dictionaries in Python
A dictionary in Python is a collection of key-value pairs. Each key is unique, and it maps to a specific value.

### 1. Dictionaries in Python
**Definition:**

+ Syntax: {key: value}
+ Keys must be unique and immutable (like strings, numbers, or tuples).
+ Values can be of any type.
 
**Example:**
```
# Example dictionary
person = {
    "name": "Kruthika",
    "age": 25,
    "city": "Chikkamagalur"
}
print(person)    # OUTPUT: {'name': 'Kruthika', 'age': 25, 'city': 'Chikkamagalur'}
```
### 2. Accessing Dictionary Elements
You can access a value by using its key.

**Example:**
```
person = {"name": "Kruthika","age": 25, "city": "Chikkamagalur"}

# Accessing elements
print(person["name"])     # Output: Kruthika
print(person.get("age"))  # Output: 25
```
### 3. Adding and Updating Dictionary Elements
 Add New Key-Value Pair:
```
person = {"name": "Kruthika", "age": 25}
person["city"] = "Chikkamagalur"  # Adding new key-value pair
print(person)                     #Output:{'name': 'Kruthika', 'age': 25, 'city': 'Chikkamagalur'}
```
### Update Existing Value:
```
person["age"] = 26       # Updating the value of an existing key
print(person)            #OUTPUT: {'name': 'Kruthika', 'age': 26, 'city': 'Chikkamagalur'}
```
### 4. Removing Elements from Dictionary
**Using pop():**
```
person = {"name": "Kruthika", "age": 25, "city": "Chikkamagalur"}
person.pop("city")     # Removes the key 'city'
print(person)          #OUTPUT : {'name': 'Kruthika', 'age': 25}
```
**Using del:**
```
del person["age"]    # Deletes the key 'age'
print(person)        #OUTPUT: {'name': 'Kruthika'}
```
**Using clear()**:
```
person.clear()  # Clears all elements
print(person)   #OUTPUT: {}
```
### 5. Dictionary Methods
Here are some common methods you can use with dictionaries:

|    Method       |    	              Description                             |  	                           Example                             |
|-----------------|-----------------------------------------------------------|--------------------------------------------------------------------|
|   keys()	      |       Returns all keys in the dictionary	              |   person.keys() -> dict_keys(['name', 'age'])                      |
|   values()	  |       Returns all values in the dictionary	              |   person.values() -> dict_values(['Kruthika', 25])                 |
|   items()       |      	Returns all key-value pairs as tuples	          |   person.items() -> dict_items([('name', 'Kruthika'), ('age', 25)])|
|   update()	  |       Updates the dictionary with new key-value pairs     |   person.update({"city": "Chikkamagalur"})                         |
|   get(key       |       Gets the value for the specified key, if it exists  |   person.get("name") -> "Kruthika"                                 |
|   pop(key)	  |       Removes the specified key and returns its value     |   person.pop("age") -> 25                                          |





