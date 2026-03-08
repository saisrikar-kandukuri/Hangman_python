# Hangman Game (Python)

A simple command-line Hangman game written in Python. The program randomly selects a word and the player must guess the letters before running out of lives.

## Features

* Random word selection
* ASCII hangman graphics
* Tracks correct and incorrect guesses
* Displays remaining lives
* Prevents repeated guesses

## Project Structure

```
hangman-python/
│
├── hangman_python.py
├── hangman_words_python.py
├── hangman_art_python.py
└── README.md
```

## How to Run

1. Make sure Python is installed.
2. Navigate to the project folder.
3. Run the game using:

```
python hangman_python.py
```

## How the Game Works

* The program randomly selects a word.
* The player guesses one letter at a time.
* Correct guesses reveal letters in the word.
* Incorrect guesses reduce the number of lives.
* The game ends when the player guesses the word or runs out of lives.

## Technologies Used

* Python
* Random module
* Lists, loops, and conditional statements

## Author

Srikar
