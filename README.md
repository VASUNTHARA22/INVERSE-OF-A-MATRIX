# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists for linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.inv(), we can find the solutions.
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: S Vasunthara sai
#RegisterNumber:212224230297

import numpy as np

matrix = np.array([[6, 2, 3], [3, 1, 1], [10, 3, 4]])

if matrix.shape[0] != matrix.shape[1]:
    print("The matrix is not square, so it does not have an inverse.")
else:
    det = np.linalg.det(matrix)
    

    if det == 0:
        print("The matrix is singular (determinant is 0), so it does not have an inverse.")
    else:
  
        inverse_matrix = np.linalg.inv(matrix)
        
        print(inverse_matrix)
```
## Output:
![image](https://github.com/user-attachments/assets/2d5ce9b5-e61b-474c-ba81-34e8b020fed4)


## Result:
Thus the inverse of given matrix is successfully solved using python program

