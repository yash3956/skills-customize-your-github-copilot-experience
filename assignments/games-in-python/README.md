
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python using strings, loops, conditionals, and user input. Students will practice core programming concepts while creating an interactive game.

## 📝 Tasks

### 🛠️ Create the Game Setup

#### Description
Set up the game by selecting a random word, initializing the guess state, and displaying the current progress to the player.

#### Requirements
Completed program should:

- Store a list of words and randomly choose one at the start of the game
- Display the hidden word using underscores, such as `_ _ _ _`
- Track the number of incorrect guesses remaining

### 🛠️ Implement Gameplay Logic

#### Description
Allow the player to enter guesses, update the display after each turn, and end the game when the word is solved or attempts are exhausted.

#### Requirements
Completed program should:

- Accept a single letter guess from the user
- Reveal correctly guessed letters in the word
- Decrease remaining attempts for incorrect guesses
- End the game with a win or loss message
