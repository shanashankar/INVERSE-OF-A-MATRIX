# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module
### Step 2: prepare the lists from each linear equations and assign in np.array()
### Step 3: using the np.linalg.inv(), we can find the solution
### Step 4: end the program

## Program:
#Program to find the inverse of a matrix.
#Developed by:sahana shankar
#RegisterNumber:26002875

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[2,1,1],[1,1,1],[1,-1,2]])

B=np.linalg.inv(A)

print(B)
## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c11908b6-a86c-4b24-8139-4eb23bfdc208" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

