# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the eigen values and eigen vectors of the matrices.
## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: RAGUL.V.K
#RegisterNumber:21003061
import numpy as np
A = np.array([[4,2],[2,4]])
values,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
~~~


## Output:
![OUTPUT](engen.jpg)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
