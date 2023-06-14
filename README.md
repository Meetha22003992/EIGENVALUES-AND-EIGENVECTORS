# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module as np
### Step 2: Get the input array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigen values and vectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Meetha Prabhu
#RegisterNumber:212222240065

import numpy as np
a=np.array([[4,2],[2,4]])
w,v=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(w,v))
```
## Output:
![image](https://user-images.githubusercontent.com/119401038/227968280-abfcf822-6620-4fe5-b175-a9aeb0ffd24b.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
