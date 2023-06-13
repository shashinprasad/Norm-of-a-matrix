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
Developed by:Shashin prasad.s
RegisterNumber: 212222230144

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-06-13 185459](https://github.com/shashinprasad/Norm-of-a-matrix/assets/129143499/a728e1bc-fe21-4b4a-b5fd-c1f88fbf5337)


### 2-Norm of a Matrix

![Screenshot 2023-06-13 185507](https://github.com/shashinprasad/Norm-of-a-matrix/assets/129143499/c11a19c1-1bbc-4780-84d7-f393a857e5ed)



### Infinity Norm of a Matrix

![Screenshot 2023-06-13 185517](https://github.com/shashinprasad/Norm-of-a-matrix/assets/129143499/192bbfba-1da1-4efb-b7d7-af1af847b2ac)



## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
