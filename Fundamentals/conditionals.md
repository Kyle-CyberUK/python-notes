# Conditionals

## Overview
- Conditionals allow programs to make decisions.
- They use if, elif (else if), and else to decide what happens.

## Example
```python
score = 80

if score >= 90:
    print("A")
elif score >= 70:
    print("B")
else:
    print("C")

# This would print out "B" because score >= 90 is False, but score >= 70 is True.
