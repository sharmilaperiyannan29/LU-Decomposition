# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)/*
Program to find the L and U matrix.
Developed by: Sharmila P
RegisterNumber: 212225230261


(ii) To find the LU Decomposition of a matrix
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)


## Output:
![s4](https://github.com/user-attachments/assets/bfcc784c-9229-4580-92df-e44e04a46c37)
![s5](https://github.com/user-attachments/assets/f0da6962-03c5-441c-9e02-eaffac84792d)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

