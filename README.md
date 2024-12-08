# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
S### tep1 :
Import the numpy module to use the built-in functions for calculations.

### Step 2:
Prepare the lists from each equations and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
END OF PROGRAM

## Program:
import numpy as np

A = np.array([[2, 2],[1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues,"and Eigen Vectors are", eigenvectors)



## Output:
![image](https://github.com/user-attachments/assets/88f30b61-1475-4283-8c1a-20fbddb2b50a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
