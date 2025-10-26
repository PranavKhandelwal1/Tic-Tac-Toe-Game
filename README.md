# Tic-Tac-Toe-Game
A simple Tic Tac Toe game implemented in Java that allows two players to play against each other in the console. Players take turns marking cells on a 3×3 board until one wins or the game ends in a draw.  This project demonstrates fundamental Java concepts such as arrays, loops, conditional statements, and user input handling using Scanner.
🚀 Features

Two-player console gameplay (Player X and Player O)

Input validation for invalid or occupied cells

Automatic win and draw detection

Simple text-based board display

💻 How to Run

Clone the repository:

git clone https://github.com/your-username/TicTacToe-Game.git
cd TicTacToe-Game


Compile the program:

javac TicTacToe.java


Run the game:

java TicTacToe

🧠 How It Works

The game maintains a 3×3 character array (char[][] board) initialized with spaces.

Players alternate turns entering row and column indices (0–2).

The program checks after each move:

If the current player has won (checkWin() method)

If the board is full (isBoardFull() method)

The game ends with a message declaring a winner or a draw.
