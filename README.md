This is a Python code that creates a simple GUI-based login page that allows users to play Tic-Tac-Toe game.

The code imports the necessary modules and creates the main window by creating an instance of the Tk() class from the tkinter module. The window is titled "LOGIN PAGE", and its size is not resizable.

The next() function is defined, which will be called when the user clicks on the "NEXT" button on the login page. This function checks whether the user has entered names for both players and displays an error message using the messagebox module if not. If both names are provided, it creates a new window, sets its title, and size, and disables its resizing. The game's rules are then defined, and the gameboard is created using nine Button widgets.

The clicked1() through clicked9() functions are defined to handle the button-click events for each Button widget on the gameboard. They toggle the text on the button from " " to "X" or "O" depending on whose turn it is and then call the check() function to see if the game has ended.

The check() function checks the game board's state after each move and displays the winner if there is one. If the game ends in a tie, it displays a message saying so.

Overall, this code creates a simple GUI-based Tic-Tac-Toe game that allows two users to play against each other.



