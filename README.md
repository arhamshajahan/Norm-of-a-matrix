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
```
# Register No:212222110005
# Developed By:ARHAM S
# 1-Norm of a Matrix
Program to find 1-norm of a matrix.
import numpy as np
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


```
# 2-Norm of a Matrix
import numpy as np

# Type your code here
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

```
# Infinity Norm of a Matrix
import numpy as np

# Type your code here
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```



## Output:
### 1-Norm of a Matrix
![norm1](https://github.com/arhamshajahan/Norm-of-a-matrix/assets/127313881/ee12097c-3ad9-43a5-b0a5-a150ed92f1e6)


### 2-Norm of a Matrix
![norm2](https://github.com/arhamshajahan/Norm-of-a-matrix/assets/127313881/09c61c24-a966-4f7a-a6cc-5a067246d644)


### Infinity Norm of a Matrix

![norm3](https://github.com/arhamshajahan/Norm-of-a-matrix/assets/127313881/5261de77-bd61-4265-993d-be31ea0f1fc7)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
