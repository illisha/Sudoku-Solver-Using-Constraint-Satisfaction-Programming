# Sudoku-Solver-Using-Constraint-Satisfaction-Programming
A set of constraints is created for the Sudoku puzzle.

The ConstraintProgram class is responsible for providing these. Each variable has basically 4 constraints associated with it:  

Constraint 1: position/location:  Each cell maybe taken up by ONLY 1 value.  

Constraint 2: row:  Each number from 1 to 9 can only be present once in a row.  

Constraint 3: column:  Each number from 1 to 9 can only be present once in a column.  

Constraint 4: region:  Each region (a smaller grid of size 3x3) can contain a number from 1 to 9 at most once. 


![Test Image 4](https://github.com/illisha/Sudoku-Solver-Using-Constraint-Satisfaction-Programming/blob/master/img1.png)


![Test Image 4](https://github.com/illisha/Sudoku-Solver-Using-Constraint-Satisfaction-Programming/blob/master/img2.png)

![Test Image 4](https://github.com/illisha/Sudoku-Solver-Using-Constraint-Satisfaction-Programming/blob/master/img.png)
