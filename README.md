# Sudoku Solver in JavaScript

This project is a Sudoku solver implemented in JavaScript. It solves Sudoku puzzles of varying difficulty using a backtracking algorithm.

## How It Works

The Sudoku solver functions as follows:
1. **Input Format**: The input puzzle is provided as a string where each character represents a cell in the Sudoku grid. A digit (`1-9`) represents a filled cell, and a hyphen (`-`) represents an empty cell.
2. **Recursive Solving**: The solver attempts to solve the puzzle by recursively filling in each empty cell with valid digits. If a digit placement leads to an unsolvable state, the algorithm backtracks and tries the next possibility.
3. **Validation**: The solver ensures that all rows, columns, and 3x3 subgrids remain valid as it fills in the cells.

## Files

- `sudoku_solver.js`: Contains the implementation of the Sudoku solver.
- `README.md`: This file, providing an overview of the project.

## Usage

### Sample Puzzles

You can test the solver with different levels of Sudoku puzzles:

```javascript
var EASY_PUZZLE = "1-58-2----9--764-52--4--819-19--73-6762-83-9-----61-5---76---3-43--2-5-16--3-89--";
var MEDIUM_PUZZLE = "-3-5--8-45-42---1---8--9---79-8-61-3-----54---5------78-----7-2---7-46--61-3--5--";
var HARD_PUZZLE = "8----------36------7--9-2---5---7-------457-----1---3---1----68--85---1--9----4--";
