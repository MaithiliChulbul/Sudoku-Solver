# Sudoku-Solver
A Sudoku Solver implemented using C++ by visualizing the Sudoku Board using Backtracking Algorithm.

# Introduction:
The objective is to fill a nine-by-nine (9x9) grid with digits so that each row, column and 3x3 section contain number between 1 and 9, with each number used once and only once in each section. The Sudoku game players are provided with empty grid meant to be solved by putting random one digit number. 

# About:
This Script is a Sudoku Solver that solves almost any Sudoku Puzzle by visualizing through the Backtracking Algorithm which is made using the C++. Ever tried but stucked on Sudoku Puzzles given in newspapers, magazines and online. You can use this script to get its solution instantly and move further.


# A sudoku board must satisfy all of the following rules:

Each of the digits 1-9 must occur exactly once in each row.
Each of the digits 1-9 must occur exactly once in each column.
Each of the digits 1-9 must occur exactly once in each of the 3x3 sub-boxes of the grid.

# Working:
Every time this Script is executed, a Random Solvable board is created.
Now, the user can first try to attempt solving it by clicking on the cells and entering values manually. Check the Input Section for the same.
Once the the user finalizes that the inputted number is the correct entry, pressing the enter key will attempt to input the number onto the board.
Correct answers will be permanently displayed .
Likewise, is same numbers are repeated then the page will display invalid board.

# Space complexity: 
it’s the recursion stack that is used as an auxiliary space which is N*N step deep. Remember we need to fill in 81 cells in a 9*9 sudoku and at each level, only one cell is filled. So, space complexity would be O(M).
