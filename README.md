# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Write the code appropirately.
3. Check the code.
4. Run the program.

## Program:
```
(i) To find the L and U matrix

Program to find the L and U matrix.
Developed by: BHAVATHARANI S
RegisterNumber: 23005455
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)


(ii) To find the LU Decomposition of a matrix


Program to find the LU Decomposition of a matrix.
Developed by: BHAVATHARANI S
RegisterNumber: 23005455
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
![output](./ludecomposition1.png)
![output](./ludecomposition2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

