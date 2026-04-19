# Data Types

## Overview
- Data types define the types of value a variable holds.

## Common Types
- String (str) - Text
- Integer (int) - Whole numbers
- Float (float) - Decimal numbers
- Boolean (bool) - True or False

## Strings
- Used to store text.
- Defined using single or double quotes.
- f-strings are used to embed variables inside strings. Prefixed with f. Placed inside curly brackets.

## List Functions
Tools to manage list items.
- `.append()` - Add one item to the end.
- `.insert()` - Add an item at a specific position.
- `.remove()` - Remove a specific item.
- `.pop()` - Remove last item.
- `.sort()` - Put items in order.
- `.clear()` - Removes everything from a list.
- `.index()` - Returns the position of an item in a list.
- `.count()` - Returns how many times a value appears in a list.
- `.copy()` - Makes a new copy of a list.

## Lists & Tuples
- A list is a collection that holds multiple things in order. It is mutable. Created using square brackets.
- A tuple is a list you cannot change (immutable). Created using parentheses.

## Examples
```python
name = "Rob"
age = 23
height = 6.1
is_student = True

print (f"My name is {name} and I am {age} years old.")

numbers = [3, 1, 2]
numbers.sort()
print(numbers)  # [1, 2, 3]
