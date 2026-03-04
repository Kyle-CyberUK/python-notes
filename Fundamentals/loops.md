# Loops

## Overview
- A loop allows a computer to repeat the same steps multiple times.

## How Loops Work
- A while loop continues running until the condition is false.
- Before the loop begins, you set up starting values.
- When the loop begins, Python checks the condition.
- If the condition is true, the code inside the loop runs.
- The loop repeats until the condition becomes false, only then will it move on.

## Loop Syntax
- != - Means not equal to. It compares 2 values and checks if they are different. Decides if the loop continues.
- break - Forces a loop to stop immediately.

## Relevance
- Loops are essential because it saves the user from having to repeat the same code.

## Example - Print numbers 1 to 5
```Python
count = 1
while count <= 5:
    print(count)
    count += 1
