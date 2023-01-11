# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. First,we want to import numpy
2. Then we want import scipy.linalg and import lu for lu decomposition
3. Then we want to assume a input
4. Then print a result.

## Program:
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: YUVARAJ.S
RegisterNumber: 22008589

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
*/


(ii)To Find The LU Decomposition of a Matrix

/*
Program to find the LU Decomposion of a Matrix.
Developed by: YUVARAJ.S
RegisterNumber: 22008589

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/


## Output:
![lu L and U Matrix](./lu1.png)
![LU Decomposition](./lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.