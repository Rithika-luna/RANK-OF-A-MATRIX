# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: 
Start the program.
### Step 2: 
Import the NumPy library using import numpy as np.
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Use the np.linalg.matrix_rank() function to calculate the rank of the given matrix.

## Program:
```


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,2,3],[3,6,9]])
solution=np.linalg.matrix_rank(a)
print(solution)

```
## Output:

<img width="1532" height="815" alt="image" src="https://github.com/user-attachments/assets/63b20e8b-ac50-4405-85fc-e3bf679021ca" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

