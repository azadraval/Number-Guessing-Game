# Number Guessing Game

This is a simple **Number Guessing Game** implemented in **C**. The program generates a random number between 1 and 100, and the player must guess the number. The game provides hints to guide the player until the correct number is guessed.

---

## Features

- Generates a random number between 1 and 100.
- Provides hints such as "Higher value" or "Lower value."
- Tracks the number of guesses taken.
- Displays the result when the player wins.

---

## How to Play

1. **Compile the Program**:
   ```bash
   gcc game.c -o number_guessing_game
## Example Gameplay
   Guess the number: 50
   Lower value please

   Guess the number: 25
   Higher value please

   Guess the number: 37
   Higher value please
   
   Guess the number: 42
   Congrants!!
   You guessed the number in 4 guesses.
