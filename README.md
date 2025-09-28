# Tic Tac Toe Game  
A simple and interactive Tic Tac Toe game built with Python and Tkinter. 
## Description  
This is a classic Tic Tac Toe game where two players take turns marking spaces in a 3×3 grid.
The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.
## Features  
- **Two-player gameplay**: Players alternate between X and O
-  **Graphical user interface**: Clean and intuitive Tkinter-based UI
-  **Win detection**: Automatically detects when a player wins
- **Draw detection**: Identifies when the game ends in a tie
- **Play again option**: After each game, players can choose to restart or exit
- **Responsive buttons**: Large, clearly labeled buttons for easy gameplay
  
 ## Requirements
- Python 3.x
- Tkinter (usually comes pre-installed with Python)
 ## Installation  
 1. Ensure you have Python installed on your system
 2. Download or copy the game code to a file named `tic_tac_toe.py`
## How to Run 
Execute the game by running the following command in your terminal or command prompt:  ```bash  python tictactoe.py   ``

How to Play
-----------
1.  The game starts with Player X's turn 
2.  Click on any empty cell to place your mark
3.  Players alternate turns between X and O
4.  The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins    
5.  If all cells are filled without a winner, the game ends in a draw    
6.  After each game, a dialog box will ask if you want to play again:
    *   Click "Yes" to reset the board and start a new game   
    *   Click "No" to exit the application
        

Game Rules
----------
*   Players take turns placing their marks (X or O) on the 3×3 grid 
*   Only one mark can be placed per turn  
*   A player cannot place a mark on an already occupied cell 
*   The game ends when: 
    * One player has three marks in a row
    * All cells are filled (draw)
        

Code Structure
--------------
*   TicTacToe class: Main game class containing all game logic  
*   \_\_init\_\_(): Initializes the game board and GUI   
*   make\_move(): Handles player moves and game progression
*   check\_winner(): Checks if the current player has won 
*   is\_board\_full(): Checks if the board is completely filled 
*   ask\_continue(): Displays game end dialog with play again option 
*   reset\_game(): Resets the game to initial state
