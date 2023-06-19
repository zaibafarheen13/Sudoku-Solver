Sudoku solver

Language Used: Python

It uses the principle of backtracking to implement the following algorithm-
Starting with an incomplete board:
1. Find some empty space
2. Attempt to place the digits 1-9 in that space
3. Check if that digit is valid in the current spot based on the current board
   a) If the digit is valid, recursively attempt to fill the board using steps 1-3. 
   b) If it is not valid, reset the square you just filled and go back to the previous step.

Once the board is full by the definition of this algorithm we have found a solution.