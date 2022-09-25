# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : To find inverse of a matrix using python programming.
### Step 2: Import numpy as np.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print result.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: harini.m.d
#RegisterNumber:22001980
import numpy as np
A=np.array([[4,2],[2,4]])
values, vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:!![Screenshot from 2022-09-21 18-36-06](https://user-images.githubusercontent.com/113497680/191511942-36e1a9ff-4baf-48f8-9f5b-09445787e022.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
