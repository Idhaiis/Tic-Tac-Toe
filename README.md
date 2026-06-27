# Tic-Tac-Toe 🎮

A Tic-Tac-Toe game built with Python and Pygame, featuring a two-player mode and an unbeatable AI opponent powered by the Minimax algorithm.

## Features

- **Two Player Mode** — Play against a friend on the same computer
- **Play Against Bot** — Challenge an AI that never loses, powered by the Minimax algorithm
- **Main Menu** — Navigate between game modes, start a new game, or resume a previous one
- **Sound Effects** — Click sounds on each move and a game over sound when the match ends
- **Win Detection** — Automatically detects wins in all rows, columns, and diagonals, and draws a line through the winning combination
- **Draw Detection** — Detects when the board is full with no winner
- **Resume** — Return to an ongoing game from the main menu

## How to Play

- **X** always goes first
- Click on any empty cell to place your mark
- First to get 3 in a row (horizontally, vertically, or diagonally) wins
- Press **ESC** at any time to return to the main menu

## Requirements

- Python 3.x
- Pygame

Install Pygame with:
```
pip install pygame
```

## Running the Game

```
python main.py
```

Make sure `click.wav` and `game over.mp3` are in the same directory as the script.

## Project Structure

```
├── main.py
├── click.wav
└── game over.mp3
```

## AI — Minimax Algorithm

The bot uses the **Minimax algorithm** to evaluate every possible future game state and always picks the optimal move. This means the bot is unbeatable — the best you can do against it is a draw.
