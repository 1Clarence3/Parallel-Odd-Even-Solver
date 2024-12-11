# Parallelized Odd-Even Solver using CUDA and Sequential Odd-Even Solvers

## Author
Clarence Lin (cl4317@columbia.edu), Lixia Chen Wu

## Overview

This project implements a parallelized CUDA-based solution to solve tridiagonal systems of equations using cyclic reduction, a method commonly applied to large sparse linear systems. The solver utilizes both forward reduction and backward substitution in a parallelized fashion, leveraging GPU capabilities for optimal performance. This project also includes functionality for handling both statically defined matrices and dynamically generated matrices for testing.

This notebook also includes the implementation of several CPU-based sequential algorithms to compare with our parallelized algorithm. Specifically, NumPy's np.linalg.solve() method as well as the Thomas algorithm were coded in Python. A sequential odd-even solver in C was also created.

The final section of this notebook includes a results section with customizable code to produce bar graphs, line plots, and tables representing the runtime performances of each of the 4 algorithms as well as their numerical stability represented by the first 10 elements of the solution vector.
