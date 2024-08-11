**Introduction**
This repository contains a simple text-based implementation of the classic Tic-Tac-Toe game in Python. Two players, X and O, take turns to place their markers on a 3x3 grid, aiming to get three in a row either horizontally, vertically, or diagonally.

**How the Code Works
Game Setup**
The game board is represented by two lists, xState and zState, each with 9 elements corresponding to the 9 positions on the board.
Each element in the lists can be either 0 (unoccupied), 1 (occupied by the respective player), or retain the position number if it’s still available.

**Functions**
printBoard(xState, zState): Displays the current state of the board, showing X, O, or the position number.
checkWin(xState, zState): Checks all possible winning combinations to determine if either player has won the game.

**Main Game Loop**
The game alternates between the two players, X and O.
Players input their desired position on the board.
The program checks if the position is valid and unoccupied.
The game continues until one player wins or the board is full.
**Example Gameplay**
**Initial Board Display:**

0 | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8

**Player Turns:
X chooses position 0:**

X | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8

**O chooses position 4:**
X | 1 | 2
--|---|---
3 | O | 5
--|---|---
6 | 7 | 8

**Game Continues:**
The game proceeds with players alternating turns until one achieves a winning combination or the game ends in a draw.
Running the Game
To play the game, simply run the Python script. The game will prompt each player to enter their move and will update the board accordingly.

**Conclusion**
This project is a simple but effective demonstration of how to implement a classic game using basic Python programming concepts like lists, functions, and loops. It's a great starting point for beginners to learn about game development in Python.

