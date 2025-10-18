# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print'.

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable

4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu 
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```

(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pi=lu_factor(a)
x=lu_solve((lu,pi),b)
print(x)
```


## Output:

<img width="1253" height="520" alt="image" src="https://github.com/user-attachments/assets/c29b42cb-a5de-443c-87bd-b29cf7768a69" />
<img width="819" height="284" alt="image" src="https://github.com/user-attachments/assets/7a7b4c66-7ce2-48a5-8a97-ca1e23df886e" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

