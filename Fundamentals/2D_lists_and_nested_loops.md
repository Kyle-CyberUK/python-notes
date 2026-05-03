# 2D Lists & Nested Loops

## Overview
- A **2D list** is a list of lists, often used to represent grids or tables.
- **Nested loops** allow you to iterate through each element in a 2D structure.

## Key Concepts
- 2D lists store data in rows and columns.
- A **nested loop** is a loop inside another loop.
- The outer loop iterates through rows.
- The inner loop iterates through items in each row.

## Example

```python
grid = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
    [0]
]

for row in grid:      # Outer loop
    for num in row:   # Inner loop
        print(num)
```
## How It Works
- The outer loop selects each row in the grid.
- The inner loop iterates through each value in that row.
- This process repeats until all elements are printed.

## Relevance
- Useful for working with grids, matrices, and structured data.
- Forms the basis for more advanced concepts like game boards and image processing.
