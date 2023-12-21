# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library as np
2. Create a matrix using np.array()
3. Using scipy.linalg.lu() find L and U, also using scipy.linalg.lu_solve() get the result for 
   LU Decomposition
4. Get the output and end the program


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: GOKHULRAJ V
RegisterNumber: 23004889
*/
```
```
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: GOKHULRAJ V
RegisterNumber: 23004889
*/
```
```
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:

![Screenshot 2023-12-21 181930](https://github.com/Gokhulraj2005/LU-Decomposition/assets/138849253/8d3cd167-5a41-42ad-ac3d-dd1f00d12917)
![Screenshot 2023-12-21 181824](https://github.com/Gokhulraj2005/LU-Decomposition/assets/138849253/f86dc35e-881b-448f-88e0-f3af9fe4bcae)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

