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

![py1](https://github.com/arhamshajahan/Norm-of-a-matrix/assets/127313881/7759c5d4-55db-4455-901a-de2a783b49eb)

### 2-Norm of a Matrix

![Screenshot 2023-06-04 094844](https://github.com/arhamshajahan/Norm-of-a-matrix/assets/127313881/b62f8ca6-49d1-4935-8189-7f8d8a022ae9)


### Infinity Norm of a Matrix


![Screenshot 2023-06-04 094928](https://github.com/arhamshajahan/Norm-of-a-matrix/assets/127313881/be382084-115c-4d43-a885-5f2628292931)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
