# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Define the package as scipy.linalg import lu 
### Step 2:
Get input from the user and print l and u matrix by 'print' 
### Step 3:
For finding the LU decomposition of a matrix:
Degine a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable 'x' include the package in that variable
### Step 4:
print the variable 'x'

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Visalan H
RegisterNumber: 212223240183
'''
import numpy as np
from scipy.linalg import lu
n=np.array(eval(input()))
p,l,u=lu(n)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Visalan H
RegisterNumber: 212223240183
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

