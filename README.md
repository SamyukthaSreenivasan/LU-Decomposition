# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm1
1. Import numpy module to use the built in function for calculation.

2. From scipy package import lu

3. Get the input from the user

4. Find the L  and U matrix using lu

5. Print the L matrix and U matrix.

## Algorithm2:
1. Import numpy module to use the built in function for calculation.

2. From scipy package import lu_factor and lu_solve

3. Get the input from the user

4. Find lu_factor of one input and store in result.

5. Create a new variable and find the lu_solve and store the result and the other variable.

6. Print the newly created variable.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Samyuktha.S
RegisterNumber: 22005276
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
a=np.array(arr)
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Samyuktha.S
RegisterNumber: 22005276
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=eval(input())
res=lu_factor(a)
solution=lu_solve(res,b)
print(solution)

```

## Output:
(i)
![output](/lu1.png)

(ii)
![output](/lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

