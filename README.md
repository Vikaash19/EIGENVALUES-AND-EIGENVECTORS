# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: Vikaash K S
#RegisterNumber: 23013426
import numpy  as n
a=n.array([[2,-3,0],[2,-5,0],[0,0,3]])
e,v=n.linalg.eig(a)
print("Eigen values are",e,"and Eigen Vectors are",v)
~~~
## Output:
![eigen value and vector](https://github.com/Vikaash19/EIGENVALUES-AND-EIGENVECTORS/assets/148514589/c3cf8742-011f-4a02-bee6-a9a0fcdc32eb)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
