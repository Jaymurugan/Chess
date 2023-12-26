# Chess Game Project

This repository contains a Python-based chess game built using the Pygame library. The project comprises multiple files that work together to create a playable chess experience.

## Files Overview

### 1. `game.py`
- Contains the `Game` class that manages the game's user interface, including the game loop, menus, board display, and game logic.

### 2. `main.py`
- Initializes the game by creating an instance of the `Game` class and starts the chess game.

### 3. `piece.py`
- Defines the `Piece` class, handling the sprites of chess pieces and their rendering on the board.

### 4. `utils.py`
- Provides utility methods within the `Utils` class for handling mouse events in the Pygame environment, specifically for obtaining mouse coordinates and detecting left-click events.

### 5. `chess.py`
- Contains the core game logic in the `Chess` class, implementing the rules of chess, player moves, piece captures, and determining the game's outcome (win, loss, or draw).

## Usage

### Running the Game
- Ensure Python is installed on your system.
- Install the Pygame library using `pip install pygame`.
- Run `main.py` to start the chess game.

### Game Controls
- Interact with menus and pieces using the mouse.
- Press `ESC` to exit the game.
- Press `SPACE` to reset the game.

### Gameplay
- Begin with the main menu; click "Play" or press `ENTER` to start the game.
- Players take turns moving pieces by clicking and dragging them to valid positions.
- The game declares the winner when a player checkmates the opponent's king.

### Modifications
- Modify the codebase to add features, customize UI elements, or enhance gameplay.

## Requirements
- Python 3.x
- Pygame library
