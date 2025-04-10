# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:MAHALINGA JEYANTH V
#RegisterNumber:212224220057
import numpy as np
matrix=np.array([[2,2],[1,3]])
eigen_values,eigen_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigen_values,eigen_vectors))
```
## Output:
![alt text](<Screenshot 2025-04-10 215230.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
