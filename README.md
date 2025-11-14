# CODECRAFT_WD_03
A simple and interactive Tic-Tac-Toe game built using HTML, CSS, and JavaScript.
This project demonstrates core concepts of DOM manipulation, game logic, event handling, and responsive UI design.

How It Works
1. HTML Structure
-Creates a 3×3 grid using <div> elements.
-Each grid cell has a click handler.
-Displays game status (whose turn it is).
-Includes a Reset Game button.

2. CSS Styling

-Uses CSS Grid to form the board layout.
-Centers the X and O inside the cells.
-Adds borders, hover effects, and styling.

3. JavaScript Logic
-Maintains a board array to store X and O placements.
-Tracks turns using currentPlayer = "X" or "O".
-Validates moves so a filled cell cannot be overwritten.
-Checks 8 possible winning combinations:
3 rows
3 columns
2 diagonals

Declares:

Winner if any combination matches

Draw if all cells are filled

Allows resetting the game to start again.
