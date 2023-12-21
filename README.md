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
```
# Register No: 23000590
# Developed By: Reklies J
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# 2-Norm of a Matrix

Program to find 2-norm of a matrix.
Developed by: Reklies  J
RegisterNumber: 212223110041

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix
#Python program to find the infinity of a matrix and display the result
#Developed by: Reklies  J
#RegisterNumber: 212223110041
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix


![Screenshot 2023-12-22 003212](https://github.com/Reklies/Norm-of-a-matrix/assets/147139232/5f483d80-5c94-4da3-8c3a-04b901d4aef1)


### 2-Norm of a Matrix



![Screenshot 2023-12-22 003314](https://github.com/Reklies/Norm-of-a-matrix/assets/147139232/58086322-9223-4847-a4dc-dcab8e552fe4)

### Infinity Norm of a Matrix



![Screenshot 2023-12-22 003340](https://github.com/Reklies/Norm-of-a-matrix/assets/147139232/5e01d572-8e8d-4f07-b1c5-9b291b976b76)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
