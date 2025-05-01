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
# Register No:24900659
# Developed By:Mohana k.v.s.l
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 1)
NORM = "{:.2f}".format(ans)
print(NORM)



# 2-Norm of a Matrix
import numpy as np
# Type your code here
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
NORM = "{:.2f}".format(ans)
print(NORM)




# Infinity Norm of a Matrix
import numpy as np
matrix = np.array(eval(input()))
red = np.max(np.sum(np.abs(matrix), axis=1))
print(f"{red:.2f}")




```
## Output:
### 1-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/55e30330-6b40-409e-840a-1348dadf1565)

<br>
<br>

### 2-Norm of a Matrix
<br>
<br>![image](https://github.com/user-attachments/assets/8ab0160f-15e3-4507-b9bb-4796bf1de2a8)

<br>

### Infinity Norm of a Matrix
<br>
<br>![image](https://github.com/user-attachments/assets/cbce6dd1-6758-450c-9bb0-59aab40dac5a)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
