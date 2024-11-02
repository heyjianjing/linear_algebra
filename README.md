# (Numerical) linear algebra

`la` linear algebra \
`nla` numerical linear algebra

### Linear algebra

Main reference
* Lectures from Prof. Stephen Boyd (Stanford)

`la_01`
* Intepretations of Ax, as transformation or translation
* Change of basis based on two interpretations

`la_02`
* y=Ax as only way of expressing linear function
* Affine function

`la_03`
* Dot product
* Equivalence with projection
* Dot product under transpose

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
* p-norm of a vector
* Cauchy-Schwarz inequality

`la_12`
* Orthonormal basis
* Equivalence between transpose and inverse
* Preservation of norm, inner product and angle
* Orthogonal matrix
* Projection of a vector onto subspace
* Two interpretations of projection

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
* Diagonalization simplifies many matrix expressions, resolvent, powers, exponential,...
* Diagonalization and left eigenvectors
* Left and right eigenvectors as dual basis

`la_25`
* Jordan canonical form generalizes diagonalization of square matrix
* Determinant of a matrix is product of all its eigenvalues
* Generalized eigenvectors
* Cayley-Hamilton theorem
* Corollary and intuition

`la_26`
* Symmetric matrix has real eigenvalues
* Symmetirc matrix has orthogonal eigenvectors
* Equivalency between transpose and inverse of eigenvector matrix when A is symmetric

`la_27`
* Similarity transformation
* Things that are preserved under similarity transformation (characteristic polynomial, eigenvalues, determinant, matrix rank...)

`la_28`
* Quadratic form
* Uniqueness of quadratic form
* Upper and lower bound of quadratic form
* Positive semidefinite and positive definite matrices
* Simple inequality related to largest/smallest eigenvalue

`la_29`
* Gain of a matrix
* Matrix norm as the largest gain
* Nullspace and zero gain

`la_30`
* Singular value decomposition (SVD) as a more complete picture of gain of matrix
* Singular vectors
* Input direction and sensitivity
* Output direction
* Comparison to eigendecomposition

`la_31`
* Left and right inverse computed via SVD

`la_32`
* Full SVD

`la_33`
* Error estimation in linear model via SVD
* Two types of ellipsoids

`la_34`
* Sensitivity of linear equations to data error
* Condition number
* Condition number of one
* Tightness of condition number bound

`la_35`
* SVD as optimal low-rank approximation
* Singular value as distance to singularity
* Model simplification with SVD

`la_ex_01`
* Example: position estimation from ranges
* Nonlinear least squares (NLLS)
* Gauss-Newton algorithm

`la_ex_02`
* Example: position estimation from ranges
* Issue with Gauss-Newton algorithm
* Levenberg-Marquardt algorithm for NLLS

`la_ex_03`
* Example: k-nearest neighbours classifier

`la_ex_04`
* Example: principal component analysis (PCA)
* Recap SVD
* Covariance in data
* Principal components

`la_ex_05`
* Example: k-means clustering

`la_ex_06`
* Example: tomography with regularized least squares
* Coordinates of image pixels
* Length of intersection between ray and pixel
* Regularized least squares for underdetermined system
* Tikhonov regularization vs Laplacian regularization

`la_ex_07`
* Example: linear quadratic state estimation with constrained least squares
* Product of two Gaussians
* Kalman filter and sequential state estimation

`la_ex_08`
* Example: polynomial data fitting with constrained least squares

### A bit of numerical linear algebra

Main reference
* Numerical Linear Algebra (Trefethen and Bau)

`nla_01`
* Classic Gram-Schmidt (CGS) in rank-one projection form
* Modified Gram-Schmidt (MGS) for numerical stability
* QR factorization example (where CGS failed)

`nla_02`
* Householder reflector for QR factorization
* Construction of reflection matrix
* Orthogonality of reflection matrix
* Householder finds full QR factorization

`nla_03`
* Givens rotation for QR factorization
* Construction of rotation matrix
* Orthogonality of rotation matrix
* Givens rotation finds full QR factorization

`nla_04`
* Gaussian elimination for solving systems of linear equations
* LU factorization with pivoting
* Concept of permutation matrix

`nla_05`
* Cholesky factorization for positive definite matrices
* Use Cholesky factorization to detect non-positive definite matrices

`nla_06`
* Method of power iterations to compute dominant eigenvalue for diagonalizable matrices
* Convergence to eigenvector
* Rayleigh quotient and convergence to eigenvalue
* Compute eigenvalues for symmetric matrices
* Compute SVD for general matrices

`nla_07`
* Schur decomposition of square real matrices with real eigenvalues
* Proof of Schur theorem by induction
* Extension of power iterations to orthogonal iterations
* Orthogonal iterations with QR factorization to get Schur form and find eigenvalues
* QR algorithm as rearrangement of orthogonal iterations
