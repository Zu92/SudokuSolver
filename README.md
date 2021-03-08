# SudokuSolver

In this project I solve a Sudoku.
For Each possible numer (1-9)
  1- Find for each row what places can be used.
  2- For that places, remove if the number was in a column.
  3-For that places, remove if the number was in a square.
For Each possible place:
  1-Find if there is the only one possibility to fill the row with that number
  2-Find if there is the only one possibility to fill the column with that number
  3-Find if there is the only one possibility to fill the square with that number
  
The results of these steps give me the places that must be fill with each number.
Replace the free spaces with the numbers.
Repeat procces until there are no free spaces.

  
