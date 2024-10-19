# Scrabble-project

This project is a Word Board Game built using vanilla JavaScript, HTML, and CSS. The game dynamically generates a 15x15 Scrabble-like board and moves predefined words from a rack onto the board. Once the words are placed, they are automatically removed after a short delay and returned to the rack.

# Table of Contents

Demo
Features
How It Works
Installation
How to Play
Code Overview
Future Enhancements

# Demo

A quick demo shows words like CAT and ASK being moved from the rack onto the board and then removed after a brief display.

# Features

Board Generation: A 15x15 board is dynamically generated with special tiles like Double Letter, Triple Word, and a star in the center.
Automated Word Placement: Predefined words like "CAT" and "ASK" are automatically placed on the board from the player's rack.
Automated Removal: After both words are placed, they are removed and sent back to the rack after a short delay.
CalculateScore: Calculates the score of the words each player has played and displays the score.
Responsive Layout: The board is displayed with responsive styling.

# How It Works

The project is based on a Scrabble-like board where words are automatically moved from a player's rack onto specific positions on the board.

Word Placement
The word CAT is placed on row 8, starting from the center of the board.
The word ASK is placed on column 10, starting from row 9.
Word Removal
Once both words are placed on the board, they remain visible for 2 seconds before being automatically removed and placed back into the rack.

# Installation

To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/ShirleenWaithaka/Project-Scrabble
Open the index.html file in a browser to start the game.

# How to Play

Start the Game: When you open the project in a browser, the board will be generated, and the rack will contain a set of letters.

Word Movement: The words CAT and ASK will automatically move from the rack onto the board.

Watch: After the words have been placed on the board, they will be removed automatically after 2 seconds.

# Code Overview

Key Files
step.1.html: The main HTML file where the game board and rack are rendered.
all css: Contains all the styles for the board layout, tiles, and letters.
all js: The core logic for generating the board, moving the letters, and removing them after placement.
Functions
genBoard(): Generates a 15x15 board with special tiles (e.g., Double Letter, Triple Word).
autoMoveLettersCAT(): Moves the letters of the word "CAT" from the rack to the board.
autoMoveLettersTASK(): Moves the letters of the word "ASK" from the rack to the board.
removeLettersFromBoard(): Removes the letters from both words after a delay and places them back in the rack.
calculateScoreCAT():calculates the score of player one according to the placed letter and tile score.
calculateScoreTASK(); calculates the score of player two according to the placed letters and tile score.

# Future Enhancements

User Input: Allow players to input their own words.
Drag and Drop: Implement a drag-and-drop feature to manually move letters from the rack onto the board.
Scoring System: Add a scoring system based on the letter and word multipliers.
Word Validation: Include a dictionary for word validation to check if the placed word is valid.
