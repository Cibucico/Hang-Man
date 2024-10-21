# Hangman Game

🎮 **A Simple Hangman Game Built with Python and ASCII Art!** 🎨

This is a terminal-based version of the classic Hangman game, where you guess letters to reveal a hidden word. Complete with fun ASCII art and various features, it’s a nostalgic coding project that’s both fun to play and build!

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Game Mechanics](#game-mechanics)
- [How to Play](#how-to-play)
- [Future Enhancements](#future-enhancements)
- [Contributions](#contributions)

## Features
- Guess the word letter by letter.
- Lose lives for incorrect guesses.
- Fun ASCII art that changes as you play.
- Dynamic gameplay that keeps you engaged.
- Plan to add more features like difficulty levels, multiplayer mode, and hints in the future!

### Getting Started

Follow these instructions to get a copy of the game up and running on your local machine.

### Prerequisites

You need Python installed on your computer. You can download it here: [Python.org](https://www.python.org/downloads/).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Cibucico/hangman-game.git

### Navigate to the project directory:

cd hangman-game

### Run the game:
 
python hangman.py

If you're using Python 3, you may need to run:

python3 hangman.py

### Game Mechanics

In Hangman, you have to guess a hidden word by suggesting letters within a certain number of guesses.

### Rules

The game chooses a random word from a predefined list.
The player must guess letters one at a time to try and reveal the hidden word.
For each incorrect guess, the player loses a life.
The game continues until the player either guesses the word or loses all lives.

### Components
Word List: The game features a list of words from which a random word is selected for each game.
Lives: Players start with 6 lives, losing one for each incorrect guess.
ASCII Art: The hangman and other fun graphics that change as the player makes incorrect guesses.

### How to Play
Run the game in your terminal.
You will be given a random word represented by blanks (e.g., "_ _ _ _ _").
You can guess one letter at a time.
The game will inform you if the letter is in the word or not.
If you guess all the letters before losing all your lives, you win! If not, it's game over.

### Example Gameplay

### Welcome to Hangman!
Guess a letter: a
You guessed "a", that's not in the word. You lose a life.
Lives left: 5
_ _ _ _ _
Guess a letter: e
_ e _ _ _ 

### Future Enhancements
Add difficulty levels (easy, medium, hard).
Implement multiplayer mode (local or online).
Add hints or power-ups to assist players.
Create a score system and leaderboard to track player performance.
Develop a web-based or mobile-friendly version using Flask or React for broader accessibility.

### Contributions
Feel free to fork this project, open issues, or make pull requests if you'd like to contribute or improve the game! Any feedback or suggestions are also welcome.

