# Sudoko-Solver
This Repository is a Sudoko Board Solver App

# Purpose
  The purpose of this project is break down how to use backtracking algorithm to solve a sudoku puzzle
  
# Criteria
  Given a Sodoku puzzle 
  make a fast algorithm to solve this puzzle
  find a valid solution
  print it to screen
  
# Naive Algorithm vs Backtracking Algorthim
  There are other possiblities to solving the puzzle.
  One way is the Naive solution,
  this solution takes every single possible combonation of numbers and tries that for each square.
  this solution would take the digits from 1 to 9 and fill each row, column and 3X3 box in the grid and check digit in the box.
  the way the math works out there There are exactly 6, 670, 903, 752, 021, 072, 936, 960 possible solutions to solve a puzzle.
  that is lot of brute force guessing and checking and  having the computer one that algrorithm would take a long time.
  
  Our way of solving is Backtracking algorthim,
  because it will completely explore one branch to a possible solution before moving to another branch.
  if it finds an error it backtracks to previous solution and retries with a differnt number.
  this greatly reduces trying the 6, 670, 903, 752, 021, 072, 936, 960 possible solutions.
  
