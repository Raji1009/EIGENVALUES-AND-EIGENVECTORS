# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.
### Step 2: 
Import numpy and enter the matrix values.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rajalakshmi R
#RegisterNumber: 23013958

import numpy as np
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print ("Eigen values are {} and Eigen Vectors are {}". format(values,vectors))
```

## Output:
![image](https://github.com/Raji1009/EIGENVALUES-AND-EIGENVECTORS/assets/89059861/6f714e95-174b-4280-8aed-e4a261cdc992)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
