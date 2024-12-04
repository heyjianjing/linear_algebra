# Linear algebra

`la` linear algebra \
`nla` numerical linear algebra

### Linear algebra

Main reference
* Lectures from Prof. Stephen Boyd (Stanford)

`la_01`
* Matrix-vector multiplication interpreted as transformation and translation
* Change of basis based on two interpretations

`la_02`
* Matrix-vector multiplication as the only way of expressing linear function
* Affine function

`la_03`
* Algebraic definition of dot (inner) product
* Dot product as projection

`la_04`
* Geometric intuition of determinant
* Determinant and cross product

`la_05`
* Interpretations of matrix-vector multiplication
* Interpretations of matrix-matrix multiplication

`la_06`
* Vector space and subspace
* Independent set of vectors
* Basis of a vector space

`la_07`
* Nullspace of a matrix
* Zero nullspace and equivalent statement: left inverse, independent columns, determinant,...

`la_08`
* Column space of a matrix
* Onto matrix and equivalent statement: right inverse, independent rows, determinant,...
* Left inverse and right inverse

`la_09`
* Inverse of square matrices
* Left and right invertibility
* Left and right inverse are unique and equal
* Dual basis

`la_10`
* Rank of a matrix
* Column rank equals row rank
* Full rank matrices

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
* Find orthonormal basis for an independent set of vectors
* Basic Gram-Schmidt procedure based on sequential orthogonalization

`la_14`
* Find orthonormal basis for a set of vectors (independent or not)
* General Gram-Schmidt procedure and QR factorization

`la_15`
* Full QR factorization
* Relationship among four subspaces of matrices through QR
* Bessel's inequality

`la_16`
* Useful derivatives in matrix calculus (column vector convention)

`la_17`
* Least squares and left inverse
* Geometric interpretation and projection matrix
* Least squares through QR factorization
* Properties of projection matrices

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
* Optimality conditions for equality-constrained least squares
* KKT equations and invertibility of KKT matrix

`la_21`
* Verification of solution obtained from KKT equations
* The solution is also unique

`la_22`
* Definition of matrix exponential

`la_23`
* Left and right eigenvectors
* Real matrices have conjugate symmetry for eigenvalues and eigenvectors
* Characteristic polynomial
* Basic properties of eigenvalues
* Markov chain example

`la_24`
* Matrices with independent set of eigenvectors are diagonalizable
* Not all square matrices are diagonalizable
* Matrices with distinct eigenvalues are diagonalizable
* The other way is not true
* Diagonalization simplifies calculation: resolvent, powers, exponential,...
* Diagonalization and left eigenvectors
* Left and right eigenvectors as dual basis

`la_25`
* Jordan canonical form generalizes diagonalization of square matrices
* Determinant of a matrix is product of all its eigenvalues
* Generalized eigenvectors
* Cayley-Hamilton theorem
* Corollary and intuition

`la_26`
* Symmetric matrices have real eigenvalues
* Symmetirc matrices have orthogonal eigenvectors

`la_27`
* Similarity transformation
* Things preserved under similarity transformation (characteristic polynomial, eigenvalues, determinant, matrix rank...)

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
* Left and right inverses computed via SVD

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
* Issues with Gauss-Newton algorithm
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

### Numerical linear algebra

Main reference
* Numerical Linear Algebra (Lloyd Trefethen and David Bau)

`nla_01`
* Classic Gram-Schmidt (CGS) in rank-one projection form
* Modified Gram-Schmidt (MGS) for numerical stability

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
* Gaussian elimination for solving linear system of equations
* LU factorization with partial pivoting
* Concept of permutation matrices

`nla_05`
* Cholesky factorization for positive definite matrices
* Use Cholesky to detect non-positive definite matrices
* LDLT factorization for nonsingular symmetric matrices

`nla_06`
* Compute determinant using factorization (Cholesky and LU with partial pivoting)

`nla_07`
* Forward substitution
* Back substitution

`nla_08`
* Condition of a problem
* Absolute and relative condition number
* Condition of matrix-vector multiplication
* Forward and backward error
* Condition number of a matrix
* Condition of a system of equations

`nla_09`
* Double precision system
* Machine precision
* Precision in relative terms
* Cancellation error

`nla_11`
* Conditioning parameters and condition numbers for least squares
* Numerical stability of different QR factorization in solving ill-conditioned least squares

`nla_12`
* Solve linear system of equations with symmetric matrices using Cholesky or LDLT
* Solve generic linear system of equations using LU factorization with partial pivoting
* Block elimination for equations with structured sub-blocks

`nla_13`
* Power iterations to compute dominant eigenvalue for diagonalizable matrices
* Convergence to eigenvector
* Rayleigh quotient and convergence to eigenvalue
* Compute all eigenvalues for symmetric matrices
* Compute SVD for general matrices

`nla_14`
* Power iterations for nonsymmetric matrices
* Update of matrix with both left and right eigenvectors
* Update of biorthogonality between left and right eigenvectors
* Compute all eigenvalues for nonsymmetric matrices

`nla_15`
* Schur decomposition
* Obtain Schur form of general matrices using orthogonal iterations
* Upper triangular matrix in Schur form contains eigenvalues in its diagonal
* Computation of eigenvectors based on Schur form

`nla_16`
* QR algorithm as refomulation of orthogonal iterations for general matrices

`nla_17`
* Fixed point method for iterative solution to linear system of equations
* Jacobi method
* Gauss-Seidel method and successive over relaxation (SOR)
* Convergence requirement

`nla_18`
* Characteristic polynomial and minimal polynomial
* Intuition via generalized eigenvectors
* Krylov subspace

`nla_19`
* Hessenberg form of matrices
* Arnoldi iteration for Hessenberg decomposition
* Arnoldi iteration constructs orthonormal basis for successive Krylov subspaces
* Reduced Hessenberg form
* Eigenvalue approximation

`nla_20`
* Lanczos iteration as special case of Arnoldi iteration for symmetric matrices
* Hessenberg form in symmetric case is tridiagonal
* Reorthogonalization for Lanczos iteration

`nla_21`
* Generalized minimal residuals (GMRES) for iterative solution to linear system of equations
* Relation to Arnoldi iteration
* Convergence of GMRES

`nla_22`
* Gradient method for iterative solution to linear system of equations
* Gradient descent and line search for optimal step size
* Conjugate gradient method for positive definite matrices
