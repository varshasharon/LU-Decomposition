# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use built-in functions for calculation.
2. Import lu package, lu_factor and lu_solve from scipy.linalg module.
3. Using lu_factor() and lu_solve(), we can find the solutions.
4. End the program.

## Program:
(i) To find the L and U matrix
```python
Program to find L and U matrix using LU decomposition.
Developed by: E. VARSHA SHARON
RegisterNumber: 22004867

import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: E. VARSHA SHARON
RegisterNumber: 22004867
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

```

## Output:
![image](https://user-images.githubusercontent.com/98278161/215094495-f581be67-5518-48bb-9e64-adad255f7082.png)
![image](https://user-images.githubusercontent.com/98278161/215094566-e0787fb8-d8c9-4fd9-bd1c-560d907e6231.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

