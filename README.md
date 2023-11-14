# EX 7: Norm of a matrix
## Date:03.10.23
## Aim:
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
# Register No: 212222230034
# Developed By: DIVYA.A

# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
solu=np.linalg.norm(A,1)
norm="{:.2f}".format(solu)
print(norm)

# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
solu=np.linalg.norm(A,2)
norm="{:.2f}".format(solu)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
solu=np.linalg.norm(A,np.inf)
norm="{:.2f}".format(solu)
print(norm)
```

## Output:
### 1-Norm of a Matrix
![math exp 07(1)](https://github.com/Divya110205/Norm-of-a-matrix/assets/119404855/6d837d54-e2d6-4390-b9fb-b22c638c20c4)

### 2-Norm of a Matrix
![math exp 07(2)](https://github.com/Divya110205/Norm-of-a-matrix/assets/119404855/9c6b35ff-bf6a-4132-a308-5222919fc931)

### Infinity Norm of a Matrix
![math exp 07(3)](https://github.com/Divya110205/Norm-of-a-matrix/assets/119404855/84c28933-bad3-4905-a5f7-8737fadc640a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
