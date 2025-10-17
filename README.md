# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
```
import numpy as np
from scipy.linalg import lu 
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```

## Output:

<img width="1253" height="520" alt="image" src="https://github.com/user-attachments/assets/c29b42cb-a5de-443c-87bd-b29cf7768a69" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

