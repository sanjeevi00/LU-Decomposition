# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np and from scipy import lu
2. Get the input of array from the user
3. solve P,L,U and print the values
4, End the program

##Program:
```
(i) To find the L and U matrix

'''Program to find L and U matrix using LU decomposition.
Developed by: Sanjeevi J
RegisterNumber:  212222110040
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
```
(ii) To find the LU Decomposition of a matrix

'''Program to solve a matrix using LU decomposition.
Developed by: Sanjeevi J
RegisterNumber: 212222110040
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```
## Output:
![lu decomposition](![maths 5th op](https://github.com/sanjeevi00/LU-Decomposition/assets/121484976/178b7f55-ef55-4926-9688-24cbbda15dce))


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

