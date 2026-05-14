# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
###Step 1:
Import the NumPy library using import numpy as np.
###Step 2:
Define the matrix using a list or array.
###Step 3:
Using the np.linalg.matrix_rank() function, find the rank of the given matrix.
###Step 4:
Display the rank of the matrix using the print() function.
## Program:
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixa=([[1,2,3],[3,6,9]])
result=np.linalg.matrix_rank(matrixa)
print(result)
```
## Output:
![alt text](<Screenshot 2026-05-14 160048.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

