# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Define the matrix
matrix = np.array([[1, 2, 3],
                   [3, 6, 9]])

# Find the rank
rank = np.linalg.matrix_rank(matrix)

# Display result
print(rank)
## Output:
<img width="779" height="822" alt="image" src="https://github.com/user-attachments/assets/4cff6a97-f2d9-4e48-b069-1ebabf888fcd" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

