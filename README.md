# Python-Tictactoe-with-AI(Minimax)

## Overview

This is a **Tic-Tac-Toe** game built using **Pygame** for the GUI and **Minimax** algorithm for the AI. The project simulates a two-player game where you can either play against another player or an AI opponent. The AI uses the Minimax algorithm to play optimally, ensuring it never loses.

The project is organized into four Python files:
- **`ai.py`**: Implements the AI logic using the Minimax algorithm.
- **`board.py`**: Handles the game board, including drawing the grid and checking for win conditions.
- **`constants.py`**: Contains all the constant values like colors, dimensions, and other game settings.
- **`tictactoe.py`**: The main file that ties everything together and runs the game.

## Features
- **Play Modes**: 
  - Player vs. Player
  - Player vs. AI (Minimax algorithm)
- **Optimal AI**: The AI plays optimally using Minimax and cannot be defeated.
- **Interactive GUI**: Built using Pygame for smooth user interaction and graphics.
- **Game Logic**: Automatically detects win/loss/draw conditions and restarts the game.

## Files Description

### 1. `ai.py`
- This file contains the AI implementation using the **Minimax algorithm**.
- The AI calculates all possible moves and chooses the optimal one.
- It handles both maximizing (AI) and minimizing (human) players to ensure the AI never loses.

### 2. `board.py`
- Manages the game board and game state.
- Handles the drawing of the grid and player moves on the screen.
- Contains logic to check for win conditions, a full board (draw), and to reset the board after a game finishes.

### 3. `constants.py`
- This file stores all the constants used in the game, such as:
  - **Colors**: RGB values for grid lines, player symbols, and background.
  - **Dimensions**: Window size, grid line thickness, and other display settings.
  - **Player Symbols**: X and O, represented by numbers or characters.

### 4. `tictactoe.py`
- The **main file** that starts the game and initializes Pygame.
- Handles the main game loop, player input, and interaction with the `board` and `ai` modules.
- Alternates turns between the player and AI, displaying the result (win/draw) at the end.

## Prerequisites

- **Python 3.x**
- **Pygame** library

To install Pygame, run the following command:
```bash
pip install pygame
```

## How to Run the Game

1. Clone this repository or download the project files.
2. Ensure you have Python 3.x installed on your system.
3. Install Pygame by running:
   ```bash
   pip install pygame
   ```
4. Run the main game file:
   ```bash
   python tictactoe.py
   ```
5. The game window will open, and you can play Tic-Tac-Toe against the AI or another player.

## How to Play

1. Click on any square on the board to place your mark (X or O).
2. If you're playing against the AI, it will automatically make its move after you.
3. The game will detect if someone has won, and the result will be displayed on the screen.
4. If the game ends in a draw, it will notify you and reset the board for a new game.

## Minimax Algorithm

The AI is designed using the **Minimax algorithm**, which ensures that the AI always plays optimally:
- **Minimax** is a recursive algorithm used for decision-making and game theory.
- It evaluates every possible move by both the player and the AI, assigns scores to the outcomes (win/loss/draw), and chooses the move that maximizes the AI's chances of winning (or minimizes its chance of losing).
- The AI can play either as X or O.

## Future Improvements

- Add a difficulty setting to make the AI less predictable at lower levels.
- Implement different board sizes (e.g., 4x4, 5x5).
- Add animations and sound effects to enhance the user experience.

## License

This project is open-source and available for modification and distribution. Feel free to contribute or use this code for educational purposes.

---

Enjoy the game and feel free to extend or improve it as you like!
