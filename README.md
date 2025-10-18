# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required library numpy as np.
### Step 2: Define the input matrix
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors using print().
## Program:
```
#Program to find the eigen values and eigen vectors.
import numpy as np
matrix=[4,2],[2,4]
eigen_values,eigen_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigen_values,eigen_vector))
```

## Output:
<img width="1261" height="923" alt="Screenshot 2025-09-27 182449" src="https://github.com/user-attachments/assets/e7dbd99d-1277-44d2-9626-4fd41094888b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
