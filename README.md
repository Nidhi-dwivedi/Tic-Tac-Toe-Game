# Tic-Tac-Toe Game

This is a console-based implementation of the classic Tic-Tac-Toe game in C++. The game allows a human player to compete against the computer. The AI uses the Minimax algorithm to ensure optimal moves, providing a challenging experience.

## Features
- Play against the computer.
- Intelligent computer moves using the Minimax algorithm.
- Instructions to guide the player.
- Detects game-over conditions (win, lose, or draw).
- Clear and easy-to-read console interface.

## How to Play
1. The game is played on a 3x3 grid.
2. The player can choose to start first or let the computer go first.
3. Players take turns placing their mark (`X` for the player and `O` for the computer) in an empty cell.
4. The first to align three marks horizontally, vertically, or diagonally wins the game.
5. If all cells are filled without a winner, the game ends in a draw.

## Instructions
1. Choose a cell numbered from 1 to 9 as shown below:
  1 | 2 | 3
  4 | 5 | 6
  7 | 8 | 9

2. Enter the corresponding number to place your mark.
3. Follow the prompts to take your turns.

## Setup and Compilation
Clone this repository, compile the program, and execute it:

```bash
# Clone the repository
git clone https://github.com/Nidhi-dwivedi/Tic-Tac-Toe-Game.git

# Navigate to the project directory
cd TicTacToe

# Compile the code
g++ tictactoe.cpp -o tictactoe

# Run the program
./tictactoe
```
##Example Gameplay
 -------------------------------------------------------------------
                        Tic-Tac-Toe
-------------------------------------------------------------------

Do you want to start first? (y/n): y

Choose a cell numbered from 1 to 9 as below and play:

    1 | 2 | 3
   -----------
    4 | 5 | 6
   -----------
    7 | 8 | 9

Enter the position = 5

HUMAN has put a X in cell 5
    * | * | *
   -----------
    * | X | *
   -----------
    * | * | *

COMPUTER has put a O in cell 1
    O | * | *
   -----------
    * | X | *
   -----------
    * | * | *

