"Rotate 2D Matrix" project:

```markdown
# Rotate 2D Matrix

This project provides a function to rotate a 2D matrix (square matrix) by 90 degrees in place.

## Overview

In certain applications, it's necessary to rotate a 2D matrix, and this project offers a simple and efficient solution. The rotation is performed in place, meaning the original matrix is modified without using additional space.

## Features

- Rotate a square 2D matrix by 90 degrees clockwise in place.

## Usage

### Example

```python
from matrix_rotator import rotate_matrix

# Example 3x3 matrix
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

# Rotate the matrix
rotate_matrix(matrix)

# Display the rotated matrix
print("Rotated Matrix:")
for row in matrix:
    print(row)
```

### Input

The input to the `rotate_matrix` function should be a square 2D matrix.

### Output

The function modifies the input matrix in place, rotating it by 90 degrees clockwise.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
