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

print(dog1.size)    # Large
print(dog2.size)    # Small
```
A **method** is a function defined inside a class that describes the behaviours an object can perform.
They are defined using 'def', and they always take 'self' as the first parameter.
```
class Dog:
    def __init__(self, name, breed):
        self.name = name
        self.breed = breed

    def description(self):
	    print(f"{self.name} is a {self.breed}.")

dog1 = Dog("Rex", "Labrador")
dog1.description()    # Rex is a Labrador.
```
Methods can also return values:
```
class Dog:
     def __init__(self, name, age):
         self.name = name
         self.age = age

     def human_years(self):
        return self.age * 7

dog1 = Dog("Rex", 4)
print(dog1.human_years())    # 28
```
