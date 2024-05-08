# LU Decomposition 
## Date:30.03.2024
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: madhu mitha v
RegisterNumber: 2305002013
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
Developed by: madhu mitha v
RegisterNumber:2305002013
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv = lu_factor(A)
x=lu_solve((lu,piv),B)
print(x) 
*/
```

## Output:
![lu decomposition]()
![Screenshot 2024-05-08 085823](https://github.com/Madhumitha2006/LU-Decomposition/assets/155508589/c02f32e2-e2ca-41be-aac6-d813455dcd42)
![Screenshot 2024-05-08 085911](https://github.com/Madhumitha2006/LU-Decomposition/assets/155508589/317f0821-e963-416c-805d-38b37303621d)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

