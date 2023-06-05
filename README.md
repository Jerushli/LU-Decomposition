# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1. Import the numpy module to use the built-in functions for calculation
2.Prepare the lists from each linear equations and assign in np.array()
3.Using the np.linalg.solve(), we can find the solutions.
4.End the program
 ```
 
 

## Program:
(i) To find the L and U matrix

```
Program to find the L and U matrix.
Developed by: Jerushlin Jose.J.B
RegisterNumber: 212222240039

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```


(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```



## Output:


![image](https://github.com/Jerushli/LU-Decomposition/assets/120041243/064d5b2a-5b68-491d-a0c3-d51958f91496)







![image](https://github.com/Jerushli/LU-Decomposition/assets/120041243/9ae55018-fa02-472e-9514-0388232a0e13)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

