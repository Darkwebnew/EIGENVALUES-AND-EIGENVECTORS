# EX 04 EIGENVALUES-AND-EIGENVECTORS
## Date: 22.08.2023
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Get the input matrix from the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sriram V
#RegisterNumber:23013561

import numpy as np

matrix = np.array([[4,  2],
                   [2,  4]])
                  
eigenvalues, eigenvectors = np.linalg.eig(matrix)

np.set_printoptions(precision=8, suppress=True)

formatted_eigenvectors = np.array2string(eigenvectors, separator=' ', formatter={'all':lambda x: f"{x: .8f}"})
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {formatted_eigenvectors}")
```
## Output:
![Screenshot 2023-10-05 163650](https://github.com/Darkwebnew/EIGENVALUES-AND-EIGENVECTORS/assets/143114486/7a2f24d4-80da-4fa8-98aa-e297f995d772)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
