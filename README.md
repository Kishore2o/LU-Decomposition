# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. First we want to import numpy 
2. Then we want to import sciply.linalg and import lufor lu decomposition 
3. Then we want to assume a input
4. Then print a result

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![OUTPUT](./images/LU deecom.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

