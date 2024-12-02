# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 1-norm, 2-norm and infinity norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
4. End the program.
## Program:
```Python
# Register No: 24900596
# Developed By: Kishore B
# 1-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:.2f}".format(a)
print(n)

# 2-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)

# Infinity Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)


```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-02 193541](https://github.com/user-attachments/assets/120ce054-bc9f-4f5e-bda6-c31f6c740a69)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2024-12-02 193559](https://github.com/user-attachments/assets/6ea49b65-76c4-4b4f-9912-99b1104efa8f)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2024-12-02 193615](https://github.com/user-attachments/assets/bf890211-a3ad-4ef4-9c56-33ed961b759f)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
