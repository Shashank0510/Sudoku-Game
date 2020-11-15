# Sudoku-Game
Sudoku game using Backtracking algorithm. Backtracking is simply reverting back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. We will use this principle of backtracking to implement the following algorithm.

#### Algorithm
<ol>
<li>Starting with an incomplete board:</li>

<li>Find some empty space</li>

<li>Attempt to place the digits 1-9 in that space</li>

<li>Check if that digit is valid in the current spot based on the current board
<ol><li>
 a. If the digit is valid, recursively attempt to fill the board using steps 1-3.</li>
<li>
 b. If it is not valid, reset the square you just filled and go back to the previous step.</li>
 </ol></li>
<li>
Once the board is full by the definition of this algorithm we have found a solution.
</li>
</ol>


Language Used : Python
<br>
Modules Used : Pygame for GUI
