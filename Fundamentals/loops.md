# Loops

## Overview
- A loop is a way to make the computer repeat the same code multiple times.
- There are different types of loops.

## For Loops
- **For loops** go through a sequence or a set of number items.
- They are best used when you know how many times you want to repeat something.
- Commonly used for lists, strings, and repeating code a fixed number of times.

### Example
```
	for i in range(5):
    		print(i)
```
- This prints numbers 0 to 4.

## While Loops
- **While loops** keep running until the condition is false.
- Useful for when you are unsure how many times the loop should repeat.

### Example:
```
	count = 0
	while count < 5:
    		print(count)
    		count += 1
```
- This also prints numbers 0 to 4.

## Loop Syntax
- `!=` means not equal to. Used primarily in while loops to check if two values are different. Decides if the loop continues.
- `break` forces a loop to stop immediately.
- `continue` skips the rest of the current loop and jumps immediately to the next one.

## Relevance
- Loops are essential because it saves the user from having to repeat the same code.
