Sudoku solver written in python that takes in a list of numbers that represent the given sudoku board, with 0s used as a placeholder to denote empty values. 

  First, I write a function that prints the given sudoku board in the form of a matrix. 
  
  Next, a function called find_zero takes in the board as an argument and loops through each column and row to determine where our zeroes are (the empty cell values   we need to solve for). 
  
  This list of column and rows gets passed into another function called is_valid, which loops through numbers 1-9 to determine which number is going to be assigned   to a specific cell. 
  
  Finally, the solution function is a recursive backtracking function that uses the partially solved board to continue to solve for other values. 
  
The current input board is considered to be a difficult sudoku board to solve, taking 196 steps to solve. My algorithm is able to solve this board in approximately 12 seconds.
