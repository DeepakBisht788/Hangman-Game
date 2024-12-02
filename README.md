# Hangman Game
Welcome to the **Hangman Game**! In this game, you have to guess a randomly selected word by suggesting one letter at a time. For each incorrect guess, a part of a hangman is drawn. If the hangman is fully drawn before you guess the word, you lose. If you guess the word before that happens, you win!

## How to Play
1. **Start the Game**: The game will choose a random word, and you will see it represented by underscores (e.g., "_ _ _ _").
2. **Guess a Letter**: You will be asked to input a letter. If the letter is in the word, it will replace the corresponding underscore.
3. **Wrong Guesses**: Each incorrect guess will result in a part of the hangman being drawn. You lose a life for each wrong guess.
4. **Game End**:
   - **Win**: If you guess all letters of the word before running out of lives, you win the game.
   - **Lose**: If the hangman is fully drawn (i.e., you run out of lives), you lose the game.

## Features
- **Random Word Selection**: A random word is chosen from a predefined list.
- **Hangman Stages**: The game uses ASCII art to draw the hangman for each incorrect guess.
- **Gameplay Feedback**: Displays the current state of the word (with underscores for unguessed letters) and the number of remaining lives.
- **Game Over Conditions**: Ends the game when the player either guesses the word or loses all lives.
