# Sudoku Solver
## AIM:
To develop a code to solve a given sudoku puzzle.

## THEORY:
We create a python program to solve a given sudoku puzzle by using Elimination and Only Choice strategies.<br>
Firstly, we form the puzzle itself, either by getting data in String form or by indexes and values, from the user.<br>
Then we fill the empty boxes with all the possible values, 1-9. We iteratively apply Elimination and Only Choice Strategies to finally end up with a result.

## DESIGN STEPS:

### STEP 1:
We define the puzzle. We initialize those boxes with only one value, with the data provided by the user, either in String format or in the Index & value format.
### STEP 2:
We identify the Row units, Column units, and the square units. And then we form a unit list using the prior data. 
### STEP 3:
Two Dictionaries with units and peers of each boxes is defined.
### STEP 4:
We reduce the puzzle using the two strategies. 
### STEP 5:
Search function is defined to find the final solution to a given sudoku puzzle.

## PROGRAM:
```

```

## OUTPUT:
## RESULT:
Hence, a python program has been developed to solve a given sudoku puzzle.
