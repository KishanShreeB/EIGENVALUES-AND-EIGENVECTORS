# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
Put the given values in the np.array command
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
print the program and get the output

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Kishan Shree B
#RegisterNumber:23012867
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
val,vect=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(val,vect))
```

## Output:
![image](https://github.com/KishanShreeB/EIGENVALUES-AND-EIGENVECTORS/assets/144870434/3eff4cea-edb1-4ecd-a7d5-836533969c80)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
