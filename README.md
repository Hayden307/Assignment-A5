# Assignment-A5
#code to find the eigen values
import numpy as np

c_matrix = np.array([[5, 1, 2],
                       [1, 9, -3],
                       [2, -3, 4]])

eigenvalues = np.linalg.eigvalsh(c_matrix)

positive_definite = all(eigenvalues > 0)

print("The Eigenvalues are:", eigenvalues)
