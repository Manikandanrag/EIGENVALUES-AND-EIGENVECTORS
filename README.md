# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation.

Step 2:
Prepare the lists from each equations and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Manikandan R
#RegisterNumber:23004754
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b,c=np.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")
```
## Output:
![image](https://github.com/Manikandanrag/EIGENVALUES-AND-EIGENVECTORS/assets/138849491/637479d0-6baa-4348-afad-27b7de882fd5)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
