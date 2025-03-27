# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Use the np.linalg.inv()
### Step 4: 
End the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: SANTHOSH S
#RegisterNumber: 212224100052
import numpy as np
A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])
try:
    A_inv = np.linalg.inv(A)
    print(A_inv)
except np.linalg.LinAlgError:
    print("Matrix is singular and cannot be inverted.")
```
## Output:
![Screenshot (122)](https://github.com/user-attachments/assets/8932859c-8b09-49cb-80b9-3043f123849d)


## Result:
Thus the inverse of given matrix is successfully solved using python program

