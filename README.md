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
#Program to find the solution for the given linear equations.
#Developed by: Harshith Sanjai S
#RegisterNumber:212225040121
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = [[1, 3],
     [2, 5]]
B = [5, -3]
solution = np.linalg.solve(A, B)
print(solution)

## Output:
<img width="1875" height="857" alt="image" src="https://github.com/user-attachments/assets/9b70e7a3-d1b2-478e-b80d-fb7669e27e75" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

