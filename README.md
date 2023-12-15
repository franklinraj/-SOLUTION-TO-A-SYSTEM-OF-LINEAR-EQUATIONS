# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
import numpy as np
A=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![Screenshot 2023-12-15 152517](https://github.com/franklinraj/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/148993740/949183b2-71cc-49c3-88b5-e35fba0dd30d)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

