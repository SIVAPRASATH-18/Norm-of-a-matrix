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
#Program to find 1-Norm of a matrix and display the results in two decimal places.
#Developed by: SIVAPRASATH B
#Register Number : 212225230268
import numpy as np
mat=eval(input())
x=np.linalg.norm(mat,1)
print("{:.2f}".format(x))

#Program to find 2-norm of a matrix.
#Developed by: SIVAPRASATH B
#RegisterNumber: 212225230268
import numpy as np
mat=eval(input())
x=np.linalg.norm(mat,2)
print("{:.2f}".format(x))

#Program to find 2-norm of a matrix.
#Developed by: SIVAPRASATH B
#RegisterNumber: 212225230268

import numpy as np
mat=eval(input())
x=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(x))
```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2026-02-27 220119.png>)
<br>
<br>
<br>

### 2-Norm of a Matrix
![alt text](<Screenshot 2026-02-27 220204.png>)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![alt text](<Screenshot 2026-02-27 220217.png>)
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
