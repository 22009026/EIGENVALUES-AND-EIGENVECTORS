# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : Import numpy package 
### Step 2: Give the input values in np.array package
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Lavanya.M
#RegisterNumber: 22009026
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![](./eigen%20val.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
