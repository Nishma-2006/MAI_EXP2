# RANK-OF-A-MATRIX
## Name: NISHMA SHERIN . K
## Register Number: 212224240104
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Read the matrix
### Step 2: 
Convert the matrix into row echelon form using row operations.
### Step 3:
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A) 
print(rank)

```
## Output:
<img width="1315" height="259" alt="Screenshot 2026-05-02 142401" src="https://github.com/user-attachments/assets/a9a7c659-f52d-4dfe-87d2-1a10dfe0700e" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
