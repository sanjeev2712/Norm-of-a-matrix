# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Import the required libraries and read the matrix elements from the user.
    2. Use the np.linalg.norm() function to compute the 1-norm, 2-norm, and infinity norm of the matrix.
	3. Print the norm of the matrix in two decimal places.
	4. Display the 1-norm, 2-norm, and infinity norm values of the matrix.
	
## Program:
```
#Program to find the 1-norm of a matrix
#Developed by: K.Sanjeev Kumar
#RegisterNumber:212225230246
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```

```
#Program to find L2-norm of a matrix.
#Developed by: K.Sanjeev Kumar
#RegisterNumber: 212225230246
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```

```
#Program to find the infinity norm of a matrix.
#Developed by: K.Sanjeev Kumar
#RegisterNumber: 212225230246
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```


## Output:
### 1-Norm of a Matrix
<img width="1161" height="657" alt="Screenshot 2026-05-16 124854" src="https://github.com/user-attachments/assets/3d6c95b8-c03e-443a-a6bf-5e936361aca7" />
<img width="1157" height="311" alt="Screenshot 2026-05-16 124907" src="https://github.com/user-attachments/assets/57101aa4-72c1-43c7-870c-79bc176c1c1b" />


### 2-Norm of a Matrix
<img width="1157" height="662" alt="Screenshot 2026-05-16 124923" src="https://github.com/user-attachments/assets/ae8d4b3e-8ecc-4abf-a888-42d57b57c5ba" />
<img width="1161" height="330" alt="Screenshot 2026-05-16 124935" src="https://github.com/user-attachments/assets/892ef29b-fae5-41df-a8f5-de8ac73b4214" />

### Infinity Norm of a Matrix
<img width="1158" height="638" alt="Screenshot 2026-05-16 124955" src="https://github.com/user-attachments/assets/d425c1ae-2826-4222-8508-c73bce49d92f" />
<img width="1177" height="317" alt="Screenshot 2026-05-16 125009" src="https://github.com/user-attachments/assets/a6624a90-be07-42f7-9220-1274b8adaa2d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
