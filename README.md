![image](https://github.com/SavindaKaveesha/Tic-Tac-Toe/assets/115203716/245b6f09-6150-47ae-9a7c-98a238a8a47d)


# Tic-Tac-Toe Game

## Overview

This Java application implements a simple Tic-Tac-Toe game using Swing for the graphical user interface. The game allows two players to take turns marking spaces in a 3x3 grid with their respective symbols (X and O) until one player wins or the game ends in a draw.

## How to Use

1. **Clone the Repository:** Clone this repository to your local machine using Git.
   ```
   git clone https://github.com/your-username/tic-tac-toe-game.git
   ```

2. **Open the Project:** Open the project in your Java Integrated Development Environment (IDE), such as IntelliJ IDEA or Eclipse.

3. **Run the Game:** Run the `Game.java` file to start the Tic-Tac-Toe application.

4. **Gameplay:**
   - The game starts with player X as the first player.
   - Players take turns clicking on the grid cells to place their symbol (X or O).
   - The game checks for a win condition after each move to determine if a player has won.
   - If no player wins and all cells are filled, the game ends in a draw.

5. **Reset and Exit:**
   - Use the "Reset" button to start a new game.
   - Click the "Exit" button to close the application.

## Features

- **Player Turns:** The game alternates between player X and player O for each turn.
- **Win Detection:** Checks for winning combinations after each move to determine the winner.
- **Draw Detection:** Ends the game in a draw if all cells are filled without a winner.
- **Score Tracking:** Keeps track of the number of wins for each player.
- **Reset and Exit:** Provides options to reset the game or exit the application.

## Code Explanation

- **Main Class (`Game.java`):**
  - Initializes the game window and user interface using Swing components.
  - Manages player turns, symbol placement, win detection, and game logic.
  - Includes action listeners for buttons to handle player moves, reset the game, and exit the application.

- **Game Logic:**
  - Uses integer variables (`b1` to `b9`) to represent the state of each grid cell (0 for X, 1 for O, and 10 for empty).
  - Implements methods to check for winning combinations horizontally, vertically, and diagonally.
  - Tracks the number of moves (`i`) to determine when the game ends in a draw.

## Technologies Used

- **Java:** Programming language used for game logic and implementation.
- **Swing:** Java GUI toolkit for creating the graphical user interface.
- **Git:** Version control system for managing code and collaboration.
