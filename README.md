# sudoko_solver_python
This is a simple Python program that solves a 9x9 Sudoku puzzle using the backtracking algorithm. The puzzle is represented as a 2D array with 9 rows and 9 columns, and the empty cells are represented by the value 0.
Usage
To use this program, simply define your Sudoku puzzle as a 2D array in the board variable, and then run the solve function. The program will solve the puzzle and print the solution to the console.
Functions

solve(bo)
This function takes a 2D array representing a Sudoku puzzle as input and solves the puzzle using the backtracking algorithm. It returns True if a solution is found, or False if the puzzle is unsolvable.

valid(bo, num, pos)
This function checks whether the given number num is valid in the given position pos in the puzzle bo. It returns True if the number is valid, or False if it is invalid.

print_board(bo)
This function prints the Sudoku puzzle bo to the console in a user-friendly format.

find_empty(bo)
This function finds an empty cell in the puzzle bo and returns its position as a tuple (row, col). If there are no empty cells, it returns None.
