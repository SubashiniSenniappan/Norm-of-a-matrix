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
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```




# 2-Norm of a Matrix
```
import numpy as np

mat =np.array(eval(input()))
ans =np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```



# Infinity Norm of a Matrix
```
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix


![Screenshot_20230126_075412](https://user-images.githubusercontent.com/119404951/214744480-44f0b00a-5b4d-4473-ae4d-70bf0865507c.png)

# 2-Norm of a Matrix


![Screenshot_20230126_075650](https://user-images.githubusercontent.com/119404951/214744726-8f3d4306-78c5-4b25-a588-b38a576677e7.png)

### Infinity Norm of a Matrix


![Screenshot_20230126_075824](https://user-images.githubusercontent.com/119404951/214744905-30f2b28b-3867-4d93-9f25-e7fa9ca2ddcd.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
