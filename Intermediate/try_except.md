# Try / Except

- `try` and `except` are used to handle errors so your program does not crash.
- `try` contains code that may cause an error.
- `except` runs if an error happens in the `try` block.

For example:
```
try:
    number = int(input("Enter a number: "))
    print(number)
except ValueError:
    print("Invalid input")
```
- If the user types anything that isn't a number, Python skips to the `except` block.
- If the user types a number, the `try` block runs as normal.
- This is useful for handling bad input and preventing crashes.
