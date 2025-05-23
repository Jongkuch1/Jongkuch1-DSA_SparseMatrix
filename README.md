# Jongkuch1-DSA_SparseMatrix
# DSA HW01 - Sparse Matrix Implementation

## Academic Integrity Statement
**I confirm that this submission is my own original work and complies with all academic integrity policies.** All code was written independently without using unauthorized sources or external libraries beyond basic Python standard libraries.

## Implementation Overview
A memory-efficient sparse matrix implementation supporting:
- Matrix addition
- Matrix subtraction  
- Matrix multiplication
- File I/O operations

## Features
✅ Strict file format validation  
✅ Handles whitespace and malformed input  
✅ Efficient sparse storage (O(n) space)  
✅ Full exception handling  
✅ Interactive command-line interface  

## File Structure
sparse_matrix/
├── code/
│ ├── src/
│ │ ├── sparse_matrix.py # Main implementation
│ │ └── main.py # CLI interface
├── sample_inputs/ # Test matrices
│ ├── matrix1.txt
│ └── matrix2.txt
├── output/ # Generated results
│ ├── addition_result.txt
│ └── multiplication_result.txt
└── tests/ # Unit tests
└── test_sparse_matrix.py


## How to Run
### Command Line Interface
```bash
python3 sparse_matrix/code/src/main.py
Unit Tests
bash
python3 -m unittest discover sparse_matrix/tests
Matrix File Format
rows=<integer>
cols=<integer> 
(<row>, <column>, <value>)
...
Example:

rows=3
cols=3
(0, 0, 1.5)
(1, 2, 3.0)
Implementation Details
Key Algorithms
Addition/Subtraction

O(n + m) time complexity

Union of non-zero coordinates

Multiplication

O(n * k) time complexity

Column-major optimization

Custom Functions
_parse_matrix_element() - Strict format validator

_validate_dimensions() - Matrix operation checker

save_to_file() - Standardized output writer

Academic Compliance
No External Libraries

Pure Python implementation

No regex or matrix libraries

Complete Documentation

Method-level docstrings

Inline comments for complex logic

Error Handling

ValueError for invalid operations

File format validation

Sample Test Cases
Test File	Operation	Verification
matrix1.txt + matrix2.txt	Addition	Sum of corresponding elements
matrix1.txt × matrix2.txt	Multiplication	Dot product validation
