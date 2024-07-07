# TicTacToe Game

TicTacToe is a classic game implemented in Python using Minmimax Algorithm and tkinter library for the graphical user interface. The game allows players to play against each other or against an AI opponent with different difficulty levels.

## Features

- **Player vs Player:** Play against a friend on the same computer.
- **Player vs AI:** Challenge the computer with two difficulty levels: Beginner and Advanced.
- **Reset Game:** Reset the game board to start a new game.

## Gameplay

- The game board is a 3x3 grid where players take turns placing their marks ('X' or 'O').
- The game ends when a player successfully aligns three marks in a row, column, or diagonal, or when all grid spaces are filled without a winner (tie).


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TicTacToe.git
   cd TicTacToe

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Usage

1. Start the game:
   ```bash
   python tictactoe.py
   
2. Choose the game mode:
 
    - **Player vs Player:** Play against another person.
    - **Beginner:** Play against a basic AI opponent.
    - **Advanced:** Play against a more challenging AI opponent.
     
3. Click on the grid to place your mark and take turns with your opponent or the AI.

4. Use the "Reset" button to start a new game at any time.

 ## Technologies Used
- **Python**
- **tkinter library** 
