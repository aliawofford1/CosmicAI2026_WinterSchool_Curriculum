# Lesson 5b: Linear Algebra with NumPy — Part 2 Quiz 
## Multiple-Choice Quiz

### Question 1

**What is an "affine transformation" in the context of linear algebra?**

a) A transformation that always passes through the origin.

b) A linear transformation followed by a translation (shift).

c) A transformation that only involves scaling.

d) A transformation that only involves rotation.

### Question 2

**What is an "eigenvector" in linear algebra?**

a) A vector that, when multiplied by a matrix, changes its direction significantly.

b) A nonzero vector whose direction remains along the same line when a linear transformation is applied, scaled by an eigenvalue.

c) A scalar value that defines the magnitude of a matrix.

d) The inverse of a matrix.

### Question 3

**What does "eigendecomposition" involve?**

a) Breaking down a vector into its component parts.

b) Decomposing a matrix using its eigenvectors and eigenvalues.

c) Multiplying two matrices together.

d) Calculating the determinant of a matrix.

### Question 4

**What is Singular Value Decomposition (SVD)?**

a) A method to calculate the sum of matrix elements.

b) A powerful matrix factorization technique with applications in dimensionality reduction and data compression.

c) A process of adding two vectors.

d) An operation to find the maximum value in a matrix.

### Question 5

**The "Moore-Penrose Pseudoinverse" is particularly useful for what kind of matrices?**

a) Square matrices only.

b) Invertible matrices only.

c) Non-square or singular matrices that do not have a traditional inverse.

d) Identity matrices.

### Question 6

**What does the determinant of a square matrix indicate?**

a) The number of eigenvectors associated with the matrix.

b) Whether the matrix is invertible and the signed scaling factor of its transformation.

c) The sum of all elements in the matrix.

d) The number of rows and columns in the matrix.

### Question 7

**What does an eigenvalue represent in the equation `Av = λv`?**

a) The number of dimensions in the vector.

b) The angle between two arbitrary vectors.

c) The scalar factor by which the eigenvector is scaled during the transformation.

d) The inverse of the transformation matrix.

### Question 8

**How is eigendecomposition useful in Principal Component Analysis (PCA)?**

a) It helps identify directions of greatest variance in the data through the eigenvectors of a covariance matrix.

b) It automatically removes every correlated variable from a dataset.

c) It converts all numerical features into categorical variables.

d) It guarantees that a machine learning model will have zero prediction error.

### Question 9

**What does the trace operator calculate for a square matrix?**

a) The product of the diagonal elements.

b) The sum of all elements in the matrix.

c) The largest eigenvalue of the matrix.

d) The sum of the diagonal elements.

### Question 10

**Why is the Moore-Penrose pseudoinverse useful in least-squares regression?**

a) It guarantees that every data point lies exactly on the regression line.

b) It can calculate a least-squares solution when the system has more equations than unknowns.

c) It eliminates the need for input features in a regression model.

d) It converts the regression problem into a classification problem.

---

# Instructor Answer Key — Lesson 5b

| Question | Correct Answer | Explanation |
|:---:|:---:|---|
| 1 | **B** | An affine transformation combines a linear transformation with a translation. This allows operations such as scaling, rotation, and shifting. |
| 2 | **B** | An eigenvector is a nonzero vector that remains along the same line after a linear transformation. Its corresponding eigenvalue determines the scaling factor. |
| 3 | **B** | Eigendecomposition expresses a diagonalizable matrix in terms of its eigenvectors and eigenvalues, commonly written as `A = VΛV⁻¹`. |
| 4 | **B** | SVD factors a matrix into singular vectors and singular values. It is useful for dimensionality reduction and lossy image compression. |
| 5 | **C** | The Moore-Penrose pseudoinverse generalizes the matrix inverse and is useful for non-square or singular matrices, including least-squares regression problems. |
| 6 | **B** | The determinant describes the signed scaling factor of a square matrix's linear transformation. A determinant of zero indicates that the matrix is singular and cannot be inverted. |
| 7 | **C** | An eigenvalue is the scalar factor associated with an eigenvector. In the equation `Av = λv`, the eigenvalue `λ` determines how the eigenvector is scaled, including a possible reversal of direction. |
| 8 | **A** | PCA can use eigendecomposition of the covariance matrix to identify principal components. Eigenvectors represent directions of variance, while their corresponding eigenvalues indicate how much variance is associated with each direction. |
| 9 | **D** | The trace of a square matrix is the sum of its diagonal elements. For example, a matrix with diagonal entries 2, 4, and 6 has a trace of 12. |
| 10 | **B** | The Moore-Penrose pseudoinverse can be used to obtain a least-squares solution for an overdetermined system, where there are more equations than unknowns. It minimizes the sum of squared residuals. |

