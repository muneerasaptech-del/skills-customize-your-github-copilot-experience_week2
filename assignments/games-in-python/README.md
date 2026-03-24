
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. You will practice string manipulation, conditionals, loops, and random selection.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create the foundation of the Hangman game by setting up a word list and selecting a random word for the player to guess.

#### Requirements
Completed program should:

- Define a list of words to choose from
- Randomly select a word from the list
- Initialize variables to track guesses and attempts remaining
- Display the hidden word in underscore format (e.g., `_ _ _`)

### 🛠️ Letter Guessing and Game Logic

#### Description
Implement the core game logic that handles player input, updates the word display, and tracks incorrect guesses.

#### Requirements
Completed program should:

- Accept letter guesses from the player using `input()`
- Check if the guessed letter is in the word
- Update the display to reveal correctly guessed letters
- Track and display remaining attempts
- Handle duplicate guesses gracefully

### 🛠️ Win/Lose Conditions and Game Flow

#### Description
Complete the game by implementing win/lose conditions and the overall game loop.

#### Requirements
Completed program should:

- End the game when the word is fully guessed (win condition)
- End the game when attempts are exhausted (lose condition)
- Display appropriate win or lose messages
- Optionally allow the player to play again
