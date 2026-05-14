# RANK-OF-A-MATRIX
## Aim:
To find the rank of matrix
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
 
## Program:

#Program to find the rank of a matrix.
#Developed by:AMIRDAVARSHINI D 
#RegisterNumber: 212225230013
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=[[1,2,3],[3,6,9]]
soln=np.linalg.matrix_rank(A)
print(soln)

## Output:
<img width="1292" height="823" alt="Screenshot 2026-05-14 140856" src="https://github.com/user-attachments/assets/fdd4e2e8-522d-4b63-91a2-273fb0ef5a64" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

