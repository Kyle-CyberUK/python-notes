# Classes & Objects

**Classes** allow you to define your own data type; like you're creating a reusable template:
```
class Dog:
    def __init__(self, name, breed, size):
        self.name = name
        self.breed = breed
        self.size = size
```
- `__init__` is the constructor - it runs automatically when an object is created and sets up its attributes accordingly.
- `self` refers to the specific object being created or used. It must be the first parameter of every method.

**Objects** are an instance of a class - the actual, usable data built from the template.
- Classes are typically stored in their own file and imported when needed.
- Once imported, you can create as many objects as required:
```
from Dog import Dog

dog1 = Dog("Rex", "Labrador", "Large")
dog2 = Dog("Bella", "Poodle", "Small")

print(dog1.size)	  # Large
print(dog2.size)	  # Small
```
