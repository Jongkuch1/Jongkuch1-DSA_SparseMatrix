# Jongkuch1-DSA_SparseMatrix
Sparse Matrix Implementation
Overview
This project implements a sparse matrix data structure optimized for memory and runtime efficiency.
The program supports loading sparse matrices from files, performing addition, subtraction, and multiplication operations, and saving results to output files.
It adheres to the requirements and instructions provided in the "Data Structures and Algorithms for Engineers" programming assignment.


Directory Structure

/Jongkuch1-DSA_SparseMatrix/sparse_matrix/code/src/ - Source code


/Jongkuch1-DSA_SparseMatrix/sparse_matrix/sample_inputs/ - Input files


/Jongkuch1-DSA_SparseMatrix/output/ - Output files


Ensure that the sample_inputs directory contains the input files (e.g., matrix1.txt, matrix2.txt) and that the output directory exists for storing results.

Features

File Parsing:

Reads sparse matrices from files in the format:

rows=8433

cols=3180

(0, 381, -694)

(0, 128, -838)

...
Handles whitespace, ignores invalid lines, and raises errors for incorrect formats.

Matrix Operations:

Addition: Adds two matrices with the same dimensions.

Subtraction: Subtracts one matrix from another with the same dimensions.

Multiplication: Multiplies two matrices where the number of columns in the first matrix matches the number of rows in the second matrix.

Efficient Storage:

Uses a dictionary to store only non-zero elements, minimizing memory usage.

Error Handling:

Ensures robust error handling for invalid inputs, mismatched dimensions, and out-of-bounds indices.

Output Format:

Saves results in the same sparse matrix format as the input files.

Requirements

Python 3.x

No external libraries are used; all functionality is implemented from scratch.

Installation and Setup

Clone the Repository:

git clone https://github.com/Jongkuch1/Jongkuch1-DSA_SparseMatrix.git

cd Jongkuch1-DSA_SparseMatrix
