# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries (numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor()to get the solutions
5.End of the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Neeli darshini
RegisterNumber: 212225230200
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Neeli darshini
RegisterNumber: 212225230200
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()),dtype='i')
B=np.array(eval(input()),dtype='i')
X=lu_factor(A)
solution=lu_solve(X,B)
print(solution)
*/
```

## Output:
<img width="1250" height="612" alt="image" src="https://github.com/user-attachments/assets/c726fdc8-20b6-457a-98b9-a65447951d35" />
<img width="1097" height="316" alt="image" src="https://github.com/user-attachments/assets/85d76093-c030-4e12-8cbb-2a431ddd00f1" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

