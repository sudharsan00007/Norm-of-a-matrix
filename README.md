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
# Register No:212224040335
# Developed By: Sudharsan S

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)


# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SUDHARSAN S
RegisterNumber: 212224040335
'''
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix


![image](https://github.com/user-attachments/assets/78691f9f-9a96-4542-b6fd-55e8c463986d)



### 2-Norm of a Matrix



![image](https://github.com/user-attachments/assets/65ebbd88-8a58-4003-8934-bdc7d2c42626)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/96d14fc2-51dc-4969-8dc0-b40dd9353181)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
