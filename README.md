# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program 
2. Import the necessary libraries(numpy,scipy.linalg)
3. Use lu(),lu_solve(),lu_factor() to get the solutions 
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: VINUTHA V
RegisterNumber: 212225230306
*/
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
P, L, U=lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:VINUTHA V 
RegisterNumber: 212225230306
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![find l and u](<Screenshot 2026-02-28 133957.png>)
![lu decomposition](<Screenshot 2026-02-28 134018.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

