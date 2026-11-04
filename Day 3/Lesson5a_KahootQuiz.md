# Lesson 5a: Linear Algebra with NumPy — Part 1 Quiz 
## Multiple-Choice Quiz


### Question 1

**What is the difference between a scalar and a vector in linear algebra?**

a) A scalar has both magnitude and direction, while a vector has only magnitude.

b) A scalar is a single numerical value, while a vector is an ordered collection of numerical values.

c) Scalars and vectors are interchangeable in all mathematical operations.

d) A scalar is always a matrix with multiple rows and columns.

### Question 2

**What does the transpose of a matrix represent?**

a) A matrix obtained by swapping its rows and columns.

b) A matrix obtained by multiplying all elements by −1.

c) A matrix obtained by calculating the inverse of each element.

d) A matrix containing only the diagonal elements of the original matrix.

### Question 3

**What does the L² norm (Euclidean norm) of a vector measure?**

a) The sum of all elements in the vector.

b) The number of dimensions in the vector.

c) The straight-line distance from the origin to the point represented by the vector.

d) The largest absolute value in the vector.

### Question 4

**When are two nonzero vectors considered orthogonal?**

a) When they have the same magnitude.

b) When their dot product equals zero.

c) When all their corresponding elements are equal.

d) When their sum equals the zero vector.

### Question 5

**What is the purpose of an identity matrix?**

a) To transform every element of a matrix into zero.

b) To calculate the determinant of a matrix.

c) To reverse the order of rows and columns.

d) To leave a compatible matrix or vector unchanged when multiplied by it.

### Question 6

**What does the L¹ norm (Manhattan norm) of a vector calculate?**

a) The square root of the sum of squared elements.

b) The sum of the absolute values of its elements.

c) The largest absolute value in the vector.

d) The product of all elements in the vector.

### Question 7

**What is the Hadamard product of two matrices?**

a) The multiplication of corresponding elements in two matrices of the same shape.

b) The multiplication of two matrices using row-by-column dot products.

c) The addition of all elements in two matrices to produce a scalar.

d) The transposition of one matrix followed by matrix inversion.

### Question 8

**What does the dot product of two vectors of equal length produce?**

a) A matrix containing the original vectors.

b) A new vector containing their elementwise sums.

c) A scalar obtained by summing the products of corresponding elements.

d) A matrix containing the outer products of the vectors.

### Question 9

**Which condition must be satisfied to multiply a matrix A of shape (m, n) by a matrix B of shape (p, q)?**

a) Both matrices must have the same number of rows.

b) Both matrices must have identical shapes.

c) The number of rows in A must equal the number of columns in B.

d) The number of columns in A must equal the number of rows in B.

### Question 10

**What does the inverse of an invertible square matrix A represent?**

a) A matrix that reverses the transformation performed by A.

b) A matrix containing only the diagonal elements of A.

c) A matrix that changes the signs of all elements in A.

d) A matrix obtained by exchanging the rows and columns of A.

---

# Solution  Key 

| Question | Correct Answer | Explanation |
|:---:|:---:|---|
| 1 | **B** | A scalar is a single numerical value, while a vector is a one-dimensional ordered collection of values. |
| 2 | **A** | Transposing a matrix swaps its rows and columns. A matrix with shape `(3, 2)` becomes `(2, 3)` after transposition. |
| 3 | **C** | The L² norm measures the Euclidean length of a vector, calculated as the square root of the sum of its squared components. |
| 4 | **B** | Two nonzero vectors are orthogonal when their dot product equals zero, meaning they are perpendicular to each other. |
| 5 | **D** | An identity matrix acts as the multiplicative identity. Multiplying a compatible matrix or vector by an identity matrix leaves it unchanged. |
| 6 | **B** | The L¹ norm is the sum of the absolute values of a vector's components. It is also called the Manhattan or taxicab norm. |
| 7 | **A** | The Hadamard product multiplies corresponding elements of matrices with the same shape. This differs from standard matrix multiplication. |
| 8 | **C** | The dot product multiplies corresponding vector components and sums the products, producing a scalar. |
| 9 | **D** | Matrix multiplication requires the inner dimensions to match. A matrix of shape `(m, n)` can multiply a matrix of shape `(n, q)`, producing `(m, q)`. |
| 10 | **A** | The inverse of an invertible square matrix reverses its transformation. Multiplying `A` by `A⁻¹` produces the identity matrix. |

