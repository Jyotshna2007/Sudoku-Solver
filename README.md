# Sudoku Solver (C++)

## Problem Statement
Sudoku is a widely played logic-based puzzle that requires filling a 9×9 grid with digits from 1 to 9 such that each digit appears exactly once in every row, column, and 3×3 sub-grid.  
The challenge is to design an efficient algorithm that can automatically solve a valid Sudoku puzzle while maintaining all these constraints.

For students learning Data Structures and Algorithms, Sudoku serves as an excellent problem to understand recursion, backtracking, and constraint validation.

## Project Description
This project is a console-based **Sudoku Solver** developed using **C++**. It solves a standard 9×9 Sudoku puzzle by applying **recursion and backtracking techniques**. The solver systematically fills empty cells by trying valid numbers and backtracks whenever a conflict occurs.

The project focuses on clarity of logic, efficient constraint checking, and clean implementation rather than advanced optimizations. It is designed to be easy to understand, explain, and demonstrate during interviews or academic evaluations.

## Solution Approach
The solution is implemented using a **backtracking algorithm** combined with recursion. The process works as follows:
- The grid is scanned to locate an empty cell.
- Digits from 1 to 9 are tried in the empty cell.
- For each digit, validity is checked against the current row, column, and the corresponding 3×3 sub-grid.
- If the digit is valid, it is placed and the algorithm recursively attempts to solve the remaining grid.
- If no valid digit can be placed, the algorithm backtracks and tries alternative values.

This approach ensures correctness while efficiently pruning invalid possibilities.

## Technologies Used
- **C++**
- **Standard Template Library (STL)**
- **Recursion**
- **Backtracking**
- **2D Vectors / Arrays**
- **Git & GitHub** for version control

---

Author: **Pragnya Yelisetti**  
GitHub: https://github.com/Pragnyayelisetti
