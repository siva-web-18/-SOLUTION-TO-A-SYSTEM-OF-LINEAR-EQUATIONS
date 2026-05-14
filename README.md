<img width="1258" height="783" alt="image" src="https://github.com/user-attachments/assets/891dc957-2f19-4114-af66-4868f3384885" /># -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=np.array([-9,4,-1])
C=np.linalg.solve(A,B)
print(C)


## Output:
<img width="1258" height="783" alt="Screenshot 2026-05-14 203538" src="https://github.com/user-attachments/assets/135d0c4c-40b7-4a73-9d2c-9e446c983f38" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

