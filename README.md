# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
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
![eigen value eigen vector](https://github.com/Vikaash19/EIGENVALUES-AND-EIGENVECTORS/assets/148514589/d71165c7-7970-4b3c-bae0-d8328905b443)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
