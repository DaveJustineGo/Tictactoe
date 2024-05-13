Description of my Code:
1. Imports:

The code imports necessary packages from java.awt and java.awt.event for creating GUI components and handling events.

2. Class Declaration:

The GOTicTacToe class is declared, extending Frame and implementing the ActionListener interface. This means the class represents a graphical window (Frame) and handles action events.

3. Main Method:

The main method is included for executing the program. It creates an instance of the GOTicTacToe class, initiating the Tic Tac Toe game.

4. Instance Variables:

buttons: A 2D array of Button objects representing the Tic Tac Toe grid.
turnLabel: A Label object for displaying whose turn it is.
board: A 2D array representing the game board's state (0 for empty, 1 for X, 2 for O).
xTurn: A boolean variable to track whose turn it is (true for Player 1 (X), false for Player 2 (O)).

5. Constructor (GOTicTacToe):

Initializes the GUI components and sets up the game board.
Creates a 3x3 grid of buttons for the Tic Tac Toe board, sets their appearance and adds action listeners.
Initializes the turn label to display "Player 1's Turn".
Adds a "New Game" button for resetting the game.
Sets up window closing behavior and sets the size and visibility of the Frame.

6. Action Listener (actionPerformed):

Handles button clicks on the Tic Tac Toe grid.
Updates the game board state when a cell is clicked.
Checks for a winner or draw after each move and updates the turn label accordingly.

7. Helper Methods:

isGameOver: Checks whether the game is over (win or draw) by examining the game board state.
resetGame: Resets the game board and buttons for a new game, resetting the turn to Player 1.

Summary:
The provided code implements a simple Tic Tac Toe game using Java's AWT. It features a graphical user interface with a 3x3 grid of buttons representing the game board. Players take turns clicking on cells to place their X or O. The game keeps track of the current player, checks for a winner or draw after each move, and allows players to start a new game.
