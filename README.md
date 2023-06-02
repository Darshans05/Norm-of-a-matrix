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
# Register No: 212222100010
# Developed By: DARSHAN S 
# 1-Norm of a Matrix
'''
program to find 1-Norm of a matrix
register number:212222100010
NAME: DARSHAN S 
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: DARSHAN S 
RegisterNumber: 212222100010
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

'''
register number: 212222100010
Name: DARSHAN S 
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
## Output:
### 1-Norm of a Matrix
![1-NORM of matrix](https://github.com/Darshans05/Norm-of-a-matrix/assets/115534676/112b7d5e-29f2-42e8-8074-de8489c5d80c)

### 2-Norm of a Matrix

![2-NORM of matrix](https://github.com/Darshans05/Norm-of-a-matrix/assets/115534676/c50cbc09-ea31-4746-9db1-064889b360fc)

### Infinity Norm of a Matrix

![infinity norm of matrx](https://github.com/Darshans05/Norm-of-a-matrix/assets/115534676/8c9b076b-66f9-4f8d-b916-8d6ae82d47b4)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
