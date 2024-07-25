## Pseudocode for linear algebra

The following `pseudocode` shows how to solve a syetem of linear equations.

```python
FUNCTION solution(A,b):
  Create the Augmented matrix: K=[A|b]
  Reduce in row reduced Echelon form
  Rank = number of non zero rows of RREF
  if rank(K) != rank(A):
    print( system is inconsistent)
  ELSEIF
      solve using back substitution
END FUNCTION
  
  
 
 
```




$$
A =\begin{bmatrix}
1 & 2 & 3\\
3 & 4 & 5\\
5 & 6 & 7
\end{bmatrix}
$$
