# Simple Calculator

## Overview
- A basic Python program that collects two numbers from the user and adds them together.

## Concepts Used
- input()
- Type conversion (float())
- Variables
- Arithmetic operators
- print()

## How It Works
- input() collects user input as a string.
- float() converts the string into a number.
- The + operator adds the two numbers.
- The result is printed to the screen.

## Code
```
num1 = input("Enter a number: ")
num2 = input("Enter another number: ")
result = float(num1) + float(num2)
print(result)
