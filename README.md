# Tic Tac Toe
This is a simple command-line implementation of the classic game Tic Tac Toe. The game is played between two players, one X and the other O, on a 3x3 grid. The goal of the game is to place three symbols in a row, either horizontally, vertically, or diagonally, before the other player.

# How to play
To play the game, simply run the script in your terminal using a Python interpreter. The game will begin by displaying an empty board with numbers representing the grid squares. Each player takes turns choosing a square to place their symbol until one player achieves three in a row or all squares are filled. To select a square, enter the corresponding number when prompted. X always goes first, and the player who achieves three in a row wins the game.

# Code Structure
● sum(a, b, c) takes three arguments and returns their sum.

● printBoard(xState, zState) takes the current state of the game board for X and O and prints it to the terminal.

● checkWin(xState, zState) takes the current state of the game board for X and O and checks for a win condition.

● main() is the main game loop that initializes the game board, takes user input, updates the game board, checks for a win condition, and repeats until the game is over.

# Improvements
There are several improvements that could be made to this implementation of Tic Tac Toe. For example, the current code does not handle invalid input or tie games. Additionally, the game board could be displayed more elegantly, and the code could be refactored for better readability and maintainability.

Overall, this code provides a solid foundation for a basic Tic Tac Toe game and could be expanded upon to create a more robust implementation.
