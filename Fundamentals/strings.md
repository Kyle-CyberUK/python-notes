# Strings

## Overview
- A string is plain text.
- It can be created using double quotes (") or single quotes (').

## Escape Characters
The \ command can be used inside strings to insert special characters.
- \n creates a new line.
- \t adds a space, like pressing the Tab key.
- \\\ prints a backslash.
- \\" prints out a double quote inside a double-quoted string.
- \\' prints out a single quote inside a single-quoted string.

## f-Strings
Allows variables to be inserted directly into a string using curly brackets.
- f""" allows multi-line strings with the use of variables.
- """ (triple quotes) allows a multi-line string.

## Strings vs Numbers
- Numbers are stored without quotation marks.
- Text must be stored inside quotation marks.

## The + Operator
The + symbol has two uses:
- Adds numbers
- Joins (concatenates) strings

## Relevance
- Strings are essential for handling user input, displaying output, and working with data.

## Examples
```
print("Hello\nWorld")

name = "Kyle"
print(f"Hello {name}")

print(5 + 5)        # 10
print("5" + "5")    # 55
