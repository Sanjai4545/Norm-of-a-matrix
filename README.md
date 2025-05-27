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
# 1-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,1)
print(norm)
```
# 2-Norm of a Matrix
```
import numpy as np
a = np.array(eval(input()))
norm = np.linalg.norm(a,2)
print(f"{norm:.2f}")
```
# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,np.inf)
print(f"{norm:.2f}")
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/ea0f4042-ab3e-4d82-849d-10895f73ecab)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/3c819f2a-1c44-46b6-a14f-d2306e596db0)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/49cd9d38-4e64-4262-8a48-aadc63f7c32d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
