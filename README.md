# Matrix Chain Multiplication
A Python implementation of the matrix chain multiplication problem solved using dynamic programming. The matrix chain multiplication problem aims to find the most efficient way to multiply a chain of matrices, minimizing the number of scalar multiplications.

## Features
Dynamic programming solution to the matrix chain multiplication problem
Calculation of the minimum number of multiplications required
Output of the optimal parenthesization

## Usage
Modify the p list in the example usage section of the code to represent the dimensions of the matrices in the chain:
p = [30, 35, 15, 5, 10, 20, 25]
Run the script to compute the minimum number of multiplications and optimal parenthesization:
matrix_chain_multiplication.py

## Example
For a chain of matrices with dimensions 30x35, 35x15, 15x5, 5x10, 10x20, and 20x25, the output will be:
Minimum number of multiplications: 15125
Optimal parenthesization: ((A0(A1A2))((A3A4)A5))
