# LU Decomposition to find L and U matrix.

## AIM:
To write a program to find the L and U of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define a function.

2.Get the values from the user.

3.Compare the values o find the L and U of a matrix.

4.Use for() and if() loop to find the LU Decompostion. 

## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:V.Pallavi 
RegisterNumber:21002343 
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```

## Output:
https://github.com/Pallavi-Raveendranadreddy/LU-Decomposition/blob/b7b231dfa86d407156731782e47b0b267e108e1d/s1.PNG
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

#  LU Decomposition to solve a matrix.

## AIM:
To write a program  to solve a matrix using LU decomposition.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define a function.

2.Get the values from the user.

3.Compare the values o find the LU decomposition of the matrix.

4.Use for() and if() loop to find the LU Decompostion. 

## Program:
```
/*
Program to solve a matrix using LU decomposition.
Developed by:V.Pallavi 
RegisterNumber:21002343 
To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
![lu decomposition](.\s2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

