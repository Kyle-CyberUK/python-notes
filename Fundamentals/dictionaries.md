# Dictionaries

## Overview
- Dictionaries store data in key-value pairs.
- Each key is unique and can be used to quickly look up its associated value.
- You can access values with square brackets or .get().

## Example
```
grades = {
    "A": "Excellent",
    "B": "Good",
    "C": "Okay",
}

print(grades["A"])
print(grades.get("A"))
