# .Linear-Algebra-Functions-
26-02-25
6.Linear Algebra Functions 
import numpy as np
a=np.array([[1,2],[3,4]])
b=np.array([[2,0],[1,2]])
print("matrix multiplication:",np.dot(a,b))
print("determinant:",np.linalg.det(a))
print("inverse:",np.linalg.inv(a))
Output:
matrix multiplication: [[ 4  4]
 [10  8]]
determinant: -2.0000000000000004
inverse: [[-2.   1. ]
 [ 1.5 -0.5]]
