# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import the numpy module to use the bulit in function for calculation
### Step 2: 
prepare the lists from each linear equations and assign in np.array()

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
end the program
## Program:
```PYTHON
#Program to find the rank of a matrix.
#Developed by:Subishesh P 
#RegisterNumber:23003621
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![image](https://github.com/Loveboysubi/RANK-OF-A-MATRIX/assets/138970879/53f5a052-21b3-4d3a-b591-ceed5580aea9)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

