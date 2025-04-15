# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

```
1. Define the package as scipy.linalg import lu.


2.Get input from user and print L and U matrix by 'print' .


3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.


4.print the variable 'X'
```

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SURIYA PRAKASH M.K
RegisterNumber:
import numpy as np
from scipy.linalg import lu
A=eval(input())
A=np.array(A)
P,L,U=lu(A)

print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SURIYA PRAKASH M.K
RegisterNumber:212224110053
A=eval(input())
B=eval(input())
import numpy as np
from scipy.linalg import lu,solve_triangular
A=np.array(A,dtype=float)

B=np.array(B,dtype=float)
P,L,U=lu(A)
Pb=P@B
y=solve_triangular(L,Pb,lower=True)
x=solve_triangular(U,y)
print(x)

*/
```

## Output:
![image](https://github.com/user-attachments/assets/50fbfb26-3ed7-4242-bb60-e4af23c81db3)

![image](https://github.com/user-attachments/assets/a783b5bf-b577-4784-a68d-78095e44576c)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

