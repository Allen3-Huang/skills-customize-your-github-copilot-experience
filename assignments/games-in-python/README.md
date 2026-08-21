# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman game while practicing Python strings, loops, conditionals, user input, and random selection.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Use the provided starter code to select a secret word and initialize the values needed to track the player's progress.

#### Requirements
Completed program should:

- Randomly select a secret word from the predefined `words` list
- Track the letters the player has guessed
- Set and track a maximum number of allowed incorrect guesses


### 🛠️ Implement the Guessing Loop

#### Description
Create the main game loop so the player can guess letters, see the revealed portions of the word, and continue until they win or run out of attempts.

#### Requirements
Completed program should:

- Accept one letter guess from the player during each turn
- Display the correctly guessed letters and use underscores for hidden letters, such as `_ _ t _ _ _`
- Update the number of incorrect guesses when a letter is not in the secret word
- End when the player reveals the entire word or reaches the maximum number of incorrect guesses
- Display a clear win or loss message and reveal the secret word when the game ends
