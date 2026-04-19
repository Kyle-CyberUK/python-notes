# Mad Libs Game

## Overview
- A simple interactive game where the user provides words that are inserted into a short story.

## Concepts Used
- Variables
- Input Function
- f-strings
- Print Function
- Multi-line Strings

## How It Works
1. Prompts the user to enter different types of words (name, place, animal, verb, adjective).
2. Stores the input in variables.
3. Inserts the variables into a pre-written story using an f-string.
4. Prints the story with the user’s words.

## Code
```
print("Welcome to Mad Libs!")
print("Please enter the following words:\n")

name = input("Enter a name: ")
place = input("Enter a place: ")
animal = input("Enter an animal: ")
verb = input("Enter a verb: ")
adjective = input("Enter an adjective: ")

print("\nHere is your story:")
story = f"""
One day, {name} went to {place}.
While looking around, they saw a {adjective} {animal}.
Suddenly, the {animal} began to {verb}.
{name} was so surprised!
"""
print(story)
