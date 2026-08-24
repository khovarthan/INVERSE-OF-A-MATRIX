# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy module to perform matrix operations.
### Step 2:
Create the given matrix using np.array() and store it in a variable.
### Step 3:
Use the np.linalg.inv() function to find the inverse of the matrix.
### Step 4:
Display the inverse matrix and end the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: khovarthan.v
#RegisterNumber: 212225220052

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[6, 2, 3],[3, 1, 1],[10, 3, 4]])

inverse = np.linalg.inv(A)

print(inverse)
```
## Output:
<img width="539" height="282" alt="MA EX;3" src="https://github.com/user-attachments/assets/54357d6e-1c73-473c-b634-bd92051c5c78" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

