# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to use the built-in function for calculation
### Step 2: prepare the lists from each linear equations and assign in np.array()
### Step 3: using the np.linalg.matrix_rank(),we can find the rank of the given matrix
### Step 4: end the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:NARENDHARAN.M
#RegisterNumber:212223230134

import numpy as np
matrix = np.array([[1, 0, 3], 
                   [-1, 2, -2], 
                   [2, 3, -1]])

inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
```
## Output:
![image](https://github.com/user-attachments/assets/ad182be7-d889-4c14-92a8-245ee8af6ebc)

## Result:
Thus the inverse of given matrix is successfully solved using python program

