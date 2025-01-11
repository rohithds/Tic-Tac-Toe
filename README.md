Tic-Tac-Toe Game in Python
A simple command-line Tic-Tac-Toe game built in Python, where two players take turns to place "X" and "O" on a 3x3 grid until one player wins or the game ends in a draw.

Features
Two Players: The game is played between two players (Player X and Player O).
Turn-Based: Players alternate turns to place their mark on the grid.
Win Conditions: The game checks for winning conditions (horizontal, vertical, or diagonal) after each move.
Draw: If the board is full and no player has won, the game results in a draw.
Requirements
Python 3.x (Recommended version: Python 3.6 or higher)
Installation
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/rohithds/tic-tac-toe.git
Navigate into the project directory:

bash
Copy code
cd tic-tac-toe
There are no additional dependencies for this project, as it runs with Python's built-in modules.

Usage
Run the Python script tic_tac_toe.py:

bash
Copy code
python tic_tac_toe.py
The game will print the current state of the board and ask each player to enter their move (a number between 1 and 9).

The game will continue until one player wins or the game ends in a draw.

Example:
diff
Copy code
Welcome to Tic-Tac-Toe!
Player X, enter your move (1-9): 1
X |   |  
--+---+--
  |   |  
--+---+--
  |   |  
Player O, enter your move (1-9): 5
X |   |  
--+---+--
  | O |  
--+---+--
  |   |  
Player X, enter your move (1-9): 9
X |   |  
--+---+--
  | O |  
--+---+--
  |   | X
Player X wins!
Error Handling
Invalid Input: If a player enters an invalid move (a number outside the range of 1-9 or a spot that is already taken), the game will prompt them to try again.
Draw: If no player wins and the board is full, the game will declare a draw.
Contributing
Feel free to fork this repository, create issues, and submit pull requests. Contributions are welcome!



Author
RohithDS

