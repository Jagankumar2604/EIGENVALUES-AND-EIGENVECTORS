# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Start the program.
### Step 2:Import the NumPy library using import numpy as np.
###        Define a square matrix A using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Stop the program.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Jagan kumar V
#RegisterNumber:212225100018
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values, vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1341" height="796" alt="Screenshot 2026-01-30 182037" src="https://github.com/user-attachments/assets/9500315c-4ae1-4f01-b798-19572cf1de9b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
