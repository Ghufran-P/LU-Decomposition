# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
Use lu(),lu_solve(),lu_factor() to get the solutions
4. End the program 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Mohammed Ghufran P
RegisterNumber: 25009482
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)

print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Mohammed Ghufran P
RegisterNumber: 25009482
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu_pivot=lu_factor(A)
x=lu_solve(lu_pivot,b)
print(x)
```

## Output:
<img width="626" height="567" alt="image" src="https://github.com/user-attachments/assets/57eb342e-f501-4d2b-b3ee-5fc5645f226e" />
<img width="472" height="443" alt="image" src="https://github.com/user-attachments/assets/7dfa8c26-18f2-4834-bbac-1a1ef00d33ac" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

