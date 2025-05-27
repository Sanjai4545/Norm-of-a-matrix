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
# Register No:212224240144
# Developed By:sanjai.T
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,1)
print(norm)
# 2-Norm of a Matrix
import numpy as np
a = np.array(eval(input()))
norm = np.linalg.norm(a,2)
print(f"{norm:.2f}")
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,np.inf)
print(f"{norm:.2f}")

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/f939e8be-1299-4b06-8c84-452ec28a5a71)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/41deaceb-014a-4531-9bde-a010637f9556)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/1dbb5638-c7ff-4416-98fb-9fdacd9b2d99)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
