# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
```
# Register No:212223240152
# Developed By: SANTHOSH G

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-06 131820](https://github.com/GSanthosh007/Norm-of-a-matrix/assets/147527586/813f2df7-87e7-4ad4-8c46-bb7ef90a60d3)

### 2-Norm of a Matrix
![Screenshot 2024-05-06 131851](https://github.com/GSanthosh007/Norm-of-a-matrix/assets/147527586/0615c0fe-76d3-4f82-87ca-be79bdb84566)

### Infinity Norm of a Matrix
![Screenshot 2024-05-06 131914](https://github.com/GSanthosh007/Norm-of-a-matrix/assets/147527586/7b90d659-b5d8-45a1-add6-d0b9beb1a685)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
