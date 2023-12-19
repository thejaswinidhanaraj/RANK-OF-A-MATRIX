# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the lists from each linear equations and assingn in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Using the np.linalg.solve(), we can find the solutions
## Program:
```
#Program to find the rank of a matrix.
#Developed by: THEJASWINI D
#RegisterNumber:23008944

import numpy as np
A = [[5,-3,-10],[2,2,-3],[-3,-1,5]]
B = np.linalg.matrix_rank(A)
print(B)
```
## Output:
![image](https://github.com/thejaswinidhanaraj/RANK-OF-A-MATRIX/assets/148514511/211b7a3a-c499-4dc1-a58c-5c3abef65807)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

