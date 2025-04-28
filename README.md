# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy library to perform matrix operations.

### Step 2:
Define the matrix a using np.array() with given elements.

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
Display the Eigenvalues and Eigenvectors using print().
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Tamil Pavalan M 
#RegisterNumber: 212223110058

import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print(f'Eigen values are {values} and Eigen Vectors are {vectors}')
```
## Output:
![image](https://github.com/user-attachments/assets/5292d5e0-ef88-495f-8cea-5afb8350bb32)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
