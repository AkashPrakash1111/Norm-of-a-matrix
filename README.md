# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 1-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix.
## Program:
```
# Register No: 24008757
# Developed By: Akash Prakash
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)
```
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix with two decimal point.

## Program:
```
# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(round(result,2))
```
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the infinity norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix.

## Program:
```
# Infinity Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-01 154355](https://github.com/user-attachments/assets/b3aee6fc-a432-4413-ba85-981a3727bb26)


### 2-Norm of a Matrix
![Screenshot 2024-12-01 154501](https://github.com/user-attachments/assets/f3c81114-640a-4b4f-9117-3d5a8ff3d1bc)

### Infinity Norm of a Matrix
![Screenshot 2024-12-01 154521](https://github.com/user-attachments/assets/ee5c27ed-50d7-4494-8321-34b5c7e50ad4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
