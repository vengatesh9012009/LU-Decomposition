# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
5(a)
### step 1.import os and import numpy module to use the built in function
### step 2. Read the input matrix perform LU decomposition to obtain the L and U
### step 3. Read the right hand side matrix B and solve the system AX=B using LU decomposition
### step 4. Display the L,U and the solve X matrices , then return the output
5(b)
### step 1.import os and import numpy module to use the built in function
### step 2. Read the input matrix perform LU decomposition to obtain the L and U
### step 3. Read the right hand side matrix B and solve the system AX=B using LU decomposition
### step 4. Display the L,U and the solve X matrices , then return the output
## Program:
(i) To find the L and U matrix
```
/*
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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```
## Output:
### 5(a)
<img width="400" height="400" alt="{4BD13730-4C95-4C34-AA59-BD215AFFBF16}" src="https://github.com/user-attachments/assets/5c275bf9-3cc1-4cf0-adb5-93f454c43930" />
<img width="400" height="400" alt="{D826E3AD-2500-4826-B6A1-8D447B869D3D}" src="https://github.com/user-attachments/assets/ae9127b5-4347-4cf7-8647-fc8225f1b313" />
### 5(b)
<img width="400" height="400" alt="{E93EA354-D2F4-43C3-9347-82D45B9929D2}" src="https://github.com/user-attachments/assets/c79e5f14-730c-4d9e-a155-33b6d09b301c" />
<img width="400" height="400" alt="{ADD805FB-D354-4366-927F-7AA85B192EC4}" src="https://github.com/user-attachments/assets/39dcf363-a95b-4d32-8e20-0c8394e4a22c" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

