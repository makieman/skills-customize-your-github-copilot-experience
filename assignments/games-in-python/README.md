# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a word-guessing game in Python that uses strings, loops, conditionals, user input, and random selection. The game should reveal a hidden word as the player guesses letters while limiting the number of incorrect guesses.

## 📝 Tasks

### 🛠️ Select a Secret Word

#### Description

Use the provided list of words to randomly select a secret word at the start of each game.

#### Requirements

Completed program should:

- Store multiple possible words in a predefined list.
- Use Python's `random` module to select one word from the list.
- Keep the selected word hidden from the player.

### 🛠️ Implement the Guessing Game

#### Description

Create the main game loop so the player can guess letters, see their progress, and receive a result when the game ends.

#### Requirements

Completed program should:

- Accept one letter guess at a time from the player.
- Display the current progress using underscores for unguessed letters, such as `_ _ _ _`.
- Track incorrect guesses and display the number of incorrect guesses remaining.
- End when the player reveals the entire word or reaches the maximum number of incorrect guesses.
- Display a clear win or lose message at the end of the game.
