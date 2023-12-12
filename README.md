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
4. Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Mohamed Anas O.I
RegisterNumber: 23008005
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Mohamed Anas O.I
RegisterNumber: 23008005
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
1.
![Screenshot 2023-12-12 140754](https://github.com/Anas536/LU-Decomposition/assets/139841834/f15d811e-b7aa-431b-b244-b4243e0e6668)

2.
![Screenshot 2023-12-12 140513](https://github.com/Anas536/LU-Decomposition/assets/139841834/78817bb3-fc0d-46ba-a320-01f0add0184b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

