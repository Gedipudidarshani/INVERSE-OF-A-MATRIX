# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation. 
### Step 2: 
Prepare the lists from the given matrix and asign in np.array() 
### Step 3: 
Using the np.linalg.inv(),we can find the solution
### Step 4:
End the program. 

## Program:
``````
#Program to find the inverse of a matrix.
#Developed by: Gedipudi Darshani
#RegisterNumber:23004619
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
rank=np.linalg.inv(A)
print(rank)
``````
## Output:
![solution](output1.png)
## Result:
Thus the inverse of given matrix is successfully solved using python programming.

