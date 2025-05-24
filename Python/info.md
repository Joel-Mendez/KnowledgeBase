# Python

## Hello World
```python
print("Hello World")
```
---
## Assigning Variables
```python
name = "Joel" # Assign a single variable
x, y, z = 1, 2, 3 # Assign multiple variables
a = b = c = 0 # Assign save value to multiple variables
```
## Datatypes
```python
name = "Joel"       # String
age = 94            # Integer
height = 6.17       # Float
is_verified = True  # Boolean
```
---
## DataStructures
### Lists: Ordered, mutable
```python
fruits = ["apple", "banana", "orange"]
numbers = [1, 2, 3, 4, 5]
mixed = [1, "hello", True, 3.14]

```

### Tuples: Ordered, immutable
```python
coordinates = (10, 20)
rgb_color = (255, 128, 0)
person = ("Alice", 25, "Engineer")

# Tuple unpacking
x, y = coordinates
name, age, job = person
```

### Dictionaries: Key-value pairs, (ordered since Python 3.7)
```python
student = {
    "name": "John",
    "age": 20,
    "grades": [85, 92, 78]
}

# Access and modify
print(student["name"]) # Access value mapped to "name" key
student["major"] = "Computer Science" # Set value mapped to "major" key
```

### Sets: Unordered, unique elements
```python
unique_numbers = {1, 2, 3, 4, 5}
colors = {"red", "green", "blue"}

# Set operations
colors.add("yellow")
colors.remove("red")
set1 & set2  # Intersection
set1 | set2  # Union
```

---
## Control Flow
### If Statements
```python
if condition: 
    # code
elif another_condition:
    # code
else: 
    # code
```
### For Loops
```python
for item in sequence:
    # code
```
### While Loops
```python
while condition:
    True
```
### Loop Control Statements
- ```break``` - exits the entire loop 
- ```continue ``` - exits the current iteration of the loop and continues on to the next iteration
- ```pass``` - does nothing, placeholder if you want nothing to happen for a specific conditional

### Try/Except
```python
try: 
    # code to try 
except ExceptionType:
    # code to execute upon the occurance of the specified error 
else: # Optional
    # code excecuted if not exceptions occur
finally: # Also Optional
    # always executes
```
---
## Functions
```python
def function_name(input1, input2):
    # Write function code
    return output
```
---
## Classes
```python 
class ClassName:
    # Class body
    def __init__(self, parameters):  # Constructor/initializer
        # Initialize instance attributes
        self.attribute = parameters

    def method(self, parameters):  # Instance method
        # Method logic
        return value
```
```python
class Dog:
    # Class attribute (shared by all instances)
    species = "Canis familiaris"

    def __init__(self, name, age):
        # Instance attributes
        self.name = name
        self.age = age

    def bark(self):
        # Instance method
        return f"{self.name} says Woof!"

    def describe(self):
        # Another instance method
        return f"{self.name} is {self.age} years old and belongs to {self.species}."

# Creating instances (objects) of the Dog class
dog1 = Dog("Buddy", 3)
dog2 = Dog("Luna", 5)

# Accessing attributes and methods
print(dog1.name)          # Output: Buddy
print(dog1.bark())       # Output: Buddy says Woof!
print(dog2.describe())   # Output: Luna is 5 years old and belongs to Canis familiaris.
```
---
## Naming Conventions
- Variables and Functions: ```snake_case```

- Constants: ```UPPER_CASE```

- Classes: ```PascalCase```

- Private Variables and Functions: ```_snake_case```
---
## Comments and Docstrings
```python 
# Python Comment 
```

```python
"""
Doc-string/ 
Multi-Line
Comment
"""
```