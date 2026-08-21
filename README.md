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
#Developed by: Janani saraswathi S
#RegisterNumber:  212225230110
# 1-Norm of a Matrix
```
'''
Developed by: Janani saraswathi S
RegisterNumber:  212225230110
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by:Janani saraswathi S
RegisterNumber: 212225230110
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix) 
```

# Infinity Norm of a Matrix
```
'''
Developed by: Janani saraswathi S
RegisterNumber:  212225230110
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix) 
```


## Output:
### 1-Norm of a Matrix
<img width="1252" height="320" alt="image" src="https://github.com/user-attachments/assets/a7389e4b-8939-4594-90cd-9f9dd638114f" />



### 2-Norm of a Matrix
<img width="873" height="353" alt="image" src="https://github.com/user-attachments/assets/0cabb0e3-79d5-4bce-91f4-c01fb4f63920" />



### Infinity Norm of a Matrix
<img width="974" height="300" alt="image" src="https://github.com/user-attachments/assets/49e2b50f-4753-4c63-94b5-34229c8a0999" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
