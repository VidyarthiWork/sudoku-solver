# sudoku-solver
Sudoku solver program:

Input: Enter the initial sudoku grid in form of 9 arrays representing the 9 rows, with 0 representing a blank cell

Output: The program will use backtracking algorithm to return the solved Sudoku.

Working: When some cell is filled with a digit, it checks whether it is valid or not. When it is not valid, it checks for other numbers. If all numbers are checked from 1-9, and no valid digit found to place, it backtracks to previous option.
