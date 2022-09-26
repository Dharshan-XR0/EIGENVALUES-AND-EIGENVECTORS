# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen vectors.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors, then end the program.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: DHARSHAN V
#RegisterNumber:22003103
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Ex4CR](https://user-images.githubusercontent.com/113497491/191961445-cf8c9c08-9130-4f15-9d2c-77dd37975165.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
