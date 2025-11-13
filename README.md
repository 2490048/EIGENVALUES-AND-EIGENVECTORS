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
name : Rahul RP
Reg num : 212224240125
```
import numpy as np
A=[[4,2],[2,4]]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
<img width="1717" height="474" alt="image" src="https://github.com/user-attachments/assets/a0278d0a-b75d-44a0-86c3-7ac44a4ee49d" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
