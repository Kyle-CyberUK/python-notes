# Number Guessing Game

## Overview
- A simple number guessing game where the computer selects a random number from 1 to 20, and the user tries to guess it.

## Key Concepts
- Import random module - Generates a random, unpredictable number.
- Loops - Repeats input prompts until the number guessed is correct.
- Conditionals - Provides feedback if the guess is outside the range, too high, too low, or correct.
- Counters - Tracks the number of tries made by the player.
- Input validation - Ensures guesses are within the valid range.

## How It Works
1. The program selects a random number from 1 to 20.
2. The player is prompted to enter a guess.
3. Feedback is given if the guess is too high, too low, out of range, or correct.
4. The loop repeats until the number is guessed correctly.

## Code
```Python
import random

secret = random.randint(1, 20)
tries = 0

print("I'm thinking of a number between 1 and 20")

while True:
    guess = int(input("Take a guess: "))
    tries += 1

    if guess < 1 or guess > 20:
        print("That number is out of range. Try again.")
    elif guess < secret:
        print("Too low, try again.")
    elif guess > secret:
        print("Too high, try again.")
    else:
        print("You got it in", tries, "tries!")
        break
