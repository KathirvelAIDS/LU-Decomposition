# LU Decomposition without zero on the diagonal

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
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:kathirvel.A 
RegisterNumber: 210023662
*/
```
~~~

import numpy as np
import scipy
from scipy.linalg import lu
A =eval(input())
P,L,U=lu(A)
print(L)
print(U)
~~~

```
/*
Program to find the LU Decomposition of a matrix.
Developed by: kathirvel.A
RegisterNumber: 21002362
*/
```
~~~
import numpy as np
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)
~~~

## Output:
![lu decomposition](https://github.com/KathirvelAIDS/LU-Decomposition/blob/main/kathir.png?raw=true)

![lu decomposition](https://github.com/KathirvelAIDS/LU-Decomposition/blob/main/kathir%202.png?raw=true)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

