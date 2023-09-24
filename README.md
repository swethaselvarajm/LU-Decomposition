# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X'.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SWETHA.S
RegisterNumber: 212222230155
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SWETHA.S
RegisterNumber: 212222230155
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A = eval(input())
b = eval(input())
lu,piv=lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![Screenshot 2023-09-24 201716](https://github.com/swethaselvarajm/LU-Decomposition/assets/119525603/ce40a7a1-f128-44ab-8261-c369eec87ad6)

![Screenshot 2023-09-24 201727](https://github.com/swethaselvarajm/LU-Decomposition/assets/119525603/c031bbd7-fc33-4e82-818b-207fa3865d19)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

