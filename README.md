# Sudoku-Game
Sudoku game using Backtracking algorithm. Backtracking is simply reverting back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. We will use this principle of backtracking to implement the following algorithm.

# Algorithm
<br>
Starting with an incomplete board:
<br>
Find some empty space
<br>
Attempt to place the digits 1-9 in that space
<br>
Check if that digit is valid in the current spot based on the current board
<br>
 a. If the digit is valid, recursively attempt to fill the board using steps 1-3.
<br>
 b. If it is not valid, reset the square you just filled and go back to the previous step.
<br>
Once the board is full by the definition of this algorithm we have found a solution.
<br>

Language Used : Python
<br>
Modules Used : Pygame for GUI
