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
Print the program and get the output

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: M Sanjay
#RegisterNumber:212222240090
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```


## Output:
![Screenshot 2023-04-10 092732](https://user-images.githubusercontent.com/119830477/230822902-8ff99b4c-6142-4af7-98fe-b6c08b057da5.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
