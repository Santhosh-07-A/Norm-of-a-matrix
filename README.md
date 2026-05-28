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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A,1)
print("{:.2f}" .format(norm))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Santhosh A
RegisterNumber: 212225040378
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A,2)
print("{:.2f}".format(norm))
# Type your code here




# Infinity Norm of a Matrix





```
## Output:
### 1-Norm of a Matrix
<img width="1919" height="1006" alt="Screenshot 2026-05-29 000902" src="https://github.com/user-attachments/assets/3020e7f3-a896-4f1d-8d62-5b9565aafc47" />


### 2-Norm of a Matrix
<img width="1920" height="1029" alt="Screenshot 2026-05-29 000923" src="https://github.com/user-attachments/assets/3c3b9404-1449-404f-951f-edee43104e22" />

### Infinity Norm of a Matrix
<img width="1917" height="1007" alt="Screenshot 2026-05-29 000935" src="https://github.com/user-attachments/assets/24338f24-f11c-48d3-924e-fc7ca69e5637" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
