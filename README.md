# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Input the given matrix and assign in np.array() 
3. Using the np.linalg import lu(), we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:SATHISH R 
RegisterNumber:22009045 

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: SATHISH R
RegisterNumber: 22009045

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,u=lu_factor(a)
x=lu_solve((l,u),b)
print(x)
```

## Output:
## PROGRAM 1

![lu](https://user-images.githubusercontent.com/120574768/212457459-ff0658c6-a51f-4a95-9a9f-c05b13767c80.png)

## PROGRAM 2

![lu de](https://user-images.githubusercontent.com/120574768/212457461-596ac7aa-db17-4251-aa1f-730ef722ea9a.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

