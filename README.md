# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : 

Import the numpy module to use the built-in functions for calculation.

### Step 2: 

Prepare the lists from each equations and assign in np.array()

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

End the program

## Program:

DEVELOPED BY:MOHAMMED SAAJID S

REGISTER NUMBER: 212223240093

TO FIND THE EIGEN VALUES AND EIGEN VECTORS

```
import numpy as np

A = np.array([[2, 2], [1, 3]])


eigenvalues, eigenvectors = np.linalg.eig(A)


print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues,eigenvectors))
```

## Output:

![mathaiexp4](https://github.com/Confusion7/EIGENVALUES-AND-EIGENVECTORS/assets/141727149/3e115fd6-b9db-4aae-9f3a-4f3758df0f44)


## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
