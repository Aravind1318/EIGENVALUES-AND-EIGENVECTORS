# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 :Import the numpy module to use the built-in functions for calculation.

### Step 2:Prepare the lists from each equations and assign in np.array()

### Step 3:Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:End the program

## Program:
```

#Program to find the eigen values and eigen vectors.
#Developed by: aravind.p
#RegisterNumber:212224240015
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigv,eigvector=np.linalg.eig(a)
print("Eigen values are",eigv,"and Eigen Vectors are",eigvector)
```

## Output: ![Screenshot 2025-04-16 112928](https://github.com/user-attachments/assets/fadd27b0-623e-4aac-80cf-9be8928149f8)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
