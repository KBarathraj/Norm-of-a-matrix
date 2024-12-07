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
# Register No:24001402
# Developed By:K Barathraj
# 1-Norm of a Matrix
import numpy as np
x = np.array(eval(input()))
d = np.linalg.norm(x,1)
n = "{:.2f}".format(d)
print(n)
# 2-Norm of a Matrix
import numpy as np
l = np.array(eval(input()))
k = np.linalg.norm(l,2)
c ="{:.2f}".format(k)
print(c)
# Infinity Norm of a Matrix
import numpy as np
o = np.array(eval(input()))
k = np.linalg.norm(o,np.inf)
c = '{:.2f}'.format(k)
print(c)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/793db7ee-aef5-483d-9027-e3189c9807f5)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/321ed039-1e76-46ab-b606-90cdc3b7e58e)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/7d2d77ff-bcac-4f6e-855c-52e0bd132992)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
