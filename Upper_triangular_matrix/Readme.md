## Aim
The aim of this program is to implement a function that computes the diagonal elements of a square matrix by summing up the elements on the upper diagonal of the matrix.

## Description
### Problem Statement
Given a square matrix, the task is to compute the diagonal elements of the matrix by summing up the elements on the upper diagonal of the matrix.

### Method Used
The program defines a function `diagonal_elements` which takes a 2D integer array and its size as input. It iterates through the upper diagonal elements of the matrix, starting from the second diagonal, and computes the sum of the adjacent elements on the upper diagonal. This sum replaces the current element. The process continues until all diagonal elements are computed.

## Pseudocode

function diagonal_elements(arr: 2D integer array, n: size of the array)
    for sub from 2 to n - 1
        set i = 0
        set j = sub
        while i < j and j < n
            arr[i][j] = arr[i][j - 1] + arr[i + 1][j]
            increment i
            increment j

function main()
    Input n as the size of the array
    Create a 2D integer array Arr of size n x n
    Initialize Values as a 5x5 array of integers
    Fill Arr with values from Values, padding with zeros where necessary
    Call diagonal_elements function with Arr and n as arguments
    Output "After applying the algorithm:"
    Output Arr
    Free memory allocated for Arr


## Output Generated

<img width="182" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/8db75aea-6f5e-47ec-9399-0efaeadd7e1a">

## Time Complexity
The time complexity of this algorithm is O(n^2), where n is the size of the matrix. This is because we iterate through each element of the upper diagonal of the matrix once.

## Space Complexity
The space complexity of this algorithm is O(n^2), where n is the size of the matrix. This is because we create a square matrix of size n x n to store the input matrix. Additionally, we use a constant amount of extra space for variables and temporary storage.
