# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
    Enter the code.
### Step 2: .
    insert the given matrix values
### Step 3: 
    Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
    check the code.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HYCINTH D
#RegisterNumber:212223240055
```
```
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues,eigenvectors=np.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```

## Output:

![alt text](<Screenshot (198).png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
