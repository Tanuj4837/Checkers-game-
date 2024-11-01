# Checkers Game with Minimax Algorithm

This project is a **Checkers Game** built with `pygame`, featuring an AI opponent that utilizes the Minimax algorithm with Alpha-Beta Pruning. The game offers a single-player mode where you can play against the AI, as well as a two-player mode where two players can play on the same computer.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Code Structure](#code-structure)
- [Future Improvements](#future-improvements)

## Features

- **Single-player mode**: Play against the AI using the Minimax algorithm with Alpha-Beta pruning.
- **Two-player mode**: Play locally with another player.
- **Graphical Interface**: Built using `pygame` for an interactive experience.
- **Winner Announcement**: Displays the winner in the terminal.

## Requirements

- Python 3.11 or higher
- Pygame 2.3.0 or higher

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/checkers-game.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd checkers-game
   ```
3. **Install dependencies**:
   ```bash
   pip install pygame
   ```

## Usage

1. **Run the game**:

   ```bash
   python main.py
   ```

2. **Select the number of players**:

   - Input `1` for a single-player game against the AI.
   - Input `2` for a two-player game.

3. **Play**:
   - Click on the pieces to select and move.
   - Follow the terminal to check the winner after each game.

## Game Rules

1. **Objective**: Capture all of your opponent's pieces or block them so they cannot move.
2. **Turns**: The game alternates between two players (or player and AI).
3. **Piece Movement**:
   - Regular pieces can only move diagonally forward.
   - If a piece reaches the opposite side, it is crowned and can then move diagonally both forward and backward.
4. **Capturing**: You must capture an opponent's piece if it is within range.

## Code Structure

- **main.py**: Contains the main game loop, player input handling, and the main menu for selecting game modes.
- **checkers/constants.py**: Defines constants like colors, dimensions, and other settings.
- **checkers/game.py**: Contains the game logic, including board setup, turn management, and winner checking.
- **minimax/algorithm.py**: Implements the Minimax algorithm with Alpha-Beta Pruning to optimize the AI’s performance.

## Future Improvements

- **Networked Multiplayer**: Implement an online multiplayer mode.
- **Enhanced AI**: Improve the AI by adjusting the Minimax depth based on difficulty levels.
- **Visual Enhancements**: Add animations and improve graphics.

---
