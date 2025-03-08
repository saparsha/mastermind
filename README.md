# Mastermind - A Code Guessing Game

## Overview
This is a Python implementation of the classic game "Mastermind." The game randomly generates a secret code consisting of four colors, and the player has ten tries to guess the correct sequence. After each guess, feedback is provided on the number of correct colors in the right and wrong positions.

## How to Play
1. The game selects a secret code of four colors from the following options:
   - R (Red)
   - G (Green)
   - B (Blue)
   - Y (Yellow)
   - W (White)
   - O (Orange)
2. The player enters their guess as four space-separated color initials (e.g., `R G B Y`).
3. The game provides feedback:
   - The number of colors in the correct position.
   - The number of correct colors in the wrong position.
4. The player has 10 attempts to guess the code correctly.
5. If the player correctly guesses the code, they win. If they run out of attempts, the secret code is revealed.

## What I Learned
- **Randomization in Python**: Used `random.choice()` to generate a random secret code.
- **User Input Handling**: Implemented input validation to ensure players enter valid colors.
- **Loop Control and Logic**: Utilized loops and conditional statements to process and verify guesses.
- **Dictionaries for Counting**: Used a dictionary to efficiently count occurrences of colors when checking guesses.
- **Error Handling**: Built error messages and input checks to improve user experience.

## Running the Game
To play, simply run the script:
```bash
python game.py
```
Ensure you have Python installed (version 3+ recommended).

Enjoy the game!

