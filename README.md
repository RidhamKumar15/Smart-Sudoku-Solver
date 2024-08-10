# Sudoku-Solver
This Java application solves any NxN Sudoku puzzle using the Recursive Backtracking algorithm. It guarantees a solution for solvable puzzles and displays the time taken to find the solution.

# Features 
 * Solves NxN Sudoku Puzzles: Works with any size Sudoku grid.
 * Recursive Backtracking Algorithm: Efficiently finds solutions.
 * Timing: Displays how long it took to solve the puzzle

# Usage Instructions:
  1) Download Required Files:
    - Ensure you have the 'Sudoku.jar' file and the 'puzzle.txt' file.
    - Make sure these files are in the same directory

  2) Prepare the Puzzle File:
      -Open puzzle.txt and enter your Sudoku puzzle.
      -Use 0 to represent empty cells. See the File Format section below for details.
  3) Run the Solver:

    - Open your terminal or command prompt
    - Navigate to the directory where Sudoku.jar and puzzle.txt are located.
    * RUN THIS COMMANDS *
    - cd path/to/your/directory
    - java -jar Sudoku.jar
  4) Enter Puzzle Dimensions:

    - When prompted, specify the number of rows and columns for the inner boxes of the Sudoku grid.
    * Example for a standard 9x9 Sudoku *
        - Enter 3 for the number of rows.
        - Enter 3 for the number of columns.

        * Example for a 12x12 Sudoku with 3x4 boxes *
        - Enter 3 for rows.
        - Enter 4 for columns.

  5) File Format
    - The puzzle.txt file should be formatted as follows:
    3 0 0 4 0 2 0 9 0 </br>
    0 0 0 0 0 9 0 6 3 </br>
    0 0 7 0 6 3 1 0 0 </br>
    0 9 1 7 2 6 0 8 0 </br>
    0 0 0 9 0 1 0 0 0 </br>
    0 2 0 3 8 5 9 1 0 </br>
    0 0 8 1 9 0 2 0 0 </br>
    6 7 0 2 0 0 0 0 0 </br>
    0 3 0 6 0 4 0 0 9 </br>

   # **Notes**
  #  The program handles any NxN Sudoku puzzle, but you must specify the dimensions of the inner boxes accurately for correct solving.
  #  For non-standard puzzles, adjust the dimensions according to your puzzle layout.
  
