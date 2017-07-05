# ProgrammingAssignment2
Assignment: Caching the Inverse of a Matrix

Matrix inversion is usually a costly computation and there may be some benefit to caching the inverse of a matrix rather than compute it repeatedly.

we must write two functions that cache the inverse of a matrix.

    makeCacheMatrix: This function creates a special "matrix" object that can cache its inverse.
    cacheSolve: This function computes the inverse of the special "matrix" returned by makeCacheMatrix above.
    If the inverse has already been calculated (and the matrix has not changed), 
    then the cachesolve should retrieve the inverse from the cache.

Computing the inverse of a square matrix can be done with the solve function in R.
For example, if X is a square invertible matrix, then solve(X) returns its inverse.

 The matrix supplied is always invertible.
