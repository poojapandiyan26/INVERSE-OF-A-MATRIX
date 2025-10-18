## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the required NumPy library using import numpy as np.
### Step 2: 
Define the matrix as a NumPy array (example: A = np.array[1, 0, 3], [-1, 2, -2],[2, 3, -1]
### Step 3: 
Use the built-in function np.linalg.inv(A) to compute the inverse of the matrix.
### Step 4: 
Store the result in a variable (e.g., A_inv) and display the inverse matrix using the print() function.
## Program:
```python

import numpy as np
np.set_printoptions(precision=8, suppress=True)  
A_inv = None            
A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]], dtype=float)

try:
    A_inv = np.linalg.inv(A)
    print(A_inv)
except np.linalg.LinAlgError:
    A_inv = None
    print("Matrix is singular and has no inverse.")
)
```
## Output:
<img width="1357" height="368" alt="image" src="https://github.com/user-attachments/assets/8e082940-effa-4823-806a-15b49d3c0eb9" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

