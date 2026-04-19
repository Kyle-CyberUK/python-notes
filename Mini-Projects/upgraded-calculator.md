# Upgraded Calculator

## Overview
- This calculator lets users perform basic arithmetic operations.
- It improves on the simple calculator by handling multiple operations, validating input, and prevents errors such as division by zero.

## Concepts Used
- Input and float function
- Conditional statements (if, elif, and else)
- Error handling
- Comparison operators

## How It Works
1. The program prompts the user to enter a number.
2. The program prompts the user to enter an operator (+, -, *, /).
3. The program asks for a second number.
4. The program checks which operator was entered:
    - If valid, it performs the corresponding calculation.
    - If division is selected, it checks for division by zero before proceeding.
5. If the operator is invalid, the program displays an error message.

## Code
```
num1 = float(input("Enter a number: "))
op = input("Enter operator: ")
num2 = float(input("Enter another number: "))

if op == "+":
	print(num1 + num2)
elif op == "-":
	print(num1 - num2)
elif op == "*":
	print(num1 * num2)
elif op == "/":
	if num2 == 0:
		print("Cannot divide by zero")
	else:
		print(num1 / num2)
else:
	print("Invalid operator")
