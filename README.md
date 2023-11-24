# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Initialize the program with import
### Step 2: 
Convert the matrix into array using array command
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
``````
#Program to find the eigen values and eigen vectors.
#Developed by:Dhivya Dharshini B 
#RegisterNumber:23008727
import numpy as np
A=np.array([[2,2],[1,3]])
Values,vectors=np.linalg.eig(A)
print("Eigen values are",Values,"and Eigen Vectors are",vectors)
``````
## Output:
![output](/Screenshot%202023-11-24%20211012.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
