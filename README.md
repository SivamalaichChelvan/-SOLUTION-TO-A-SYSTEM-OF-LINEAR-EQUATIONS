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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=[[1,-3],[3,1]]
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)
```
## Output:
<img width="1918" height="972" alt="Screenshot 2026-05-20 202406" src="https://github.com/user-attachments/assets/f749aaf2-e661-4670-9c87-3b57586b0de2" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

