# Matrix Chain Multiplication Using Dynamic Programming

## Description
The algorithm aims to minimize scalar matrix multiplication by determining the optimal order of multiplying matrices. It employs dynamic programming, creating a matrix to store intermediate results and recursively computing the minimum cost.

## Algorithm
### Initialization:
- Create a 2D array `m[n][n]` to store the minimum number of multiplications for matrix multiplication.
- Create a 2D array `brac[5][5]` (fixed size for demonstration) to store optimal parentheses placement information.

### Base Case:
- Set `m[i][i] = 0` for all diagonal elements, indicating that a single matrix multiplication requires no additional multiplications.

### Dynamic Programming Loop:
- Use nested loops to fill the `m` array diagonally.
- Iterate over different chain lengths `L` (from 2 to `n`, where `n` is the number of matrices).
- For each chain length, iterate over all possible starting indices `i`.
- Compute the minimum number of multiplications `m[i][j]` required to multiply matrices from index `i` to `j` using a third index `k` as a split point.
- Update `m[i][j]` and `brac[i][j]` if a better (minimum) number of multiplications is found.

### Optimal Parenthesization:
- Use a recursive function `printParenthesis` to print the optimal placement of parentheses for matrix multiplication based on the information stored in the `brac` array.

### Main Function:
- Initialize an array `arr` with the dimensions of matrices.
- Call the `MatrixChainOrder` function to compute the minimum number of multiplications and print the optimal parenthesization.

## Time Complexity
The time complexity of the Matrix Chain Multiplication algorithm using dynamic programming is as follows:
- Best-case time complexity: O(n^3)
- Average-case time complexity: O(n^3)
- Worst-case time complexity: O(n^3)
