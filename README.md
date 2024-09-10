# Linear algebra and numerical linear algebra

`la`: linear algebra

### Notes on `linear algebra`

Source 
* Lectures from Prof. Stephen Boyd at Stanford

`la_01`
* Intepretations of $Ax$, as transformation or translation
* Change of basis based on two interpretations

`la_02`
* $y=Ax$ as only way of expressing linear function
* Affine function

`la_03`
* Dot product
* Equivalence with projection

`la_04`
* Geometric intuition of determinant
* Determinant and cross product

`la_05`
* Interpretations of matrix-vector multiplication
* Interpretations of matrix-matrix multiplication

`la_06`
* Vector space and subspace
* Independent set of vectors
* Basis

`la_07`
* Nullspace definition
* Zero nullspace and equivalent statement: left inverse, indepedent columns, determinant,...
* Tall matrix

`la_08`
* Column space definition
* Onto matrix and equivalent statement: right inverse, independent rows, determinant,...
* Fat matrix
* Left inverse and right inverse
* Compute the `right` right inverse

`la_09`
* Inverse of square matrix
* Left invertible $\Longleftrightarrow$ right invertible
* Left and right inverse are unique and equal
* Dual basis

`la_10`
* Rank of matrix
* Column rank equals row rank
* Full rank matrix
* Change of basis

`la_11`
* Euclidean norm of a vector
* $l_p$ norm of a vector
* Cauchy-Schwarz inequality

`la_12`
* Orthonormal basis
* Equivalence between transpose and inverse
* Preservation of norm, inner product and angle
* Orthogonal matrix
* Projection onto subspace

`la_13`
* Find orthonormal basis for independent set of vectors
* Basic Gram-Schmidt procedure based on sequential orthogonalization

`la_14`
* Find orthonormal basis for set of vectors (independent or not)
* General Gram-Schmidt procedure
* Sequentially determine whether each vector in the set can be expressed as a linear combination of vectors that precede it

`la_15`
* QR and full QR decomposition
* Relationship among four subspaces of a matrix through QR
* Bessel's inequality

`la_16`
* Useful derivatives from matrix calculus

`la_17`
* Least squares and left inverse
* Geometric interpretation and projection matrix
* Least squares through QR decomposition
* Properties of projection matrix

`la_18`
* Multi-objective least squares and regularization
* Tikhonov regularization

`la_19`
* Least squares problem with equality constraints
* Least norm problem
* Right inverse as solution to least norm problem
* Derivation of least norm solution through method of Lagrange multipliers
* Intuition behind method of Lagrange multipliers

`la_20`
* Least squares with equality constraint
* Optimality conditions using method of Lagrange multipliers
* KKT equations and invertibility of KKT matrix

`la_21`
* Verification of solution obtained from KKT equations
* The solution is also unique

`la_22`
* Definition of matrix exponential
* In general $e^{A+B}\neq e^A e^B$

`la_23`
* Left and right eigenvectors
* Real matrix has conjugate symmetry for eigenvalues and eigenvectors
* Characteristic polynomial
* Basic properties of eigenvalues
* Eigenvalues and characteristic polynomial is the same under similarity transformation

`la_24`
* Matrix diagonalization as an application of eigenvectors and eigenvalues
* Matrix is diagonalizable if and only if it has independent set of eigenvectors
* Not all square matrices are diagonalizable
* If matrix has distinct eigenvalues, then it is diagonalizable
* The other way is not true
* Diagonalization simplies many matrix expressions, resolvent, powers, exponential,...
* Diagonalization and left eigenvectors
* Left and right eigenvectors as dual basis
