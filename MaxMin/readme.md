# Maximum and Minimum Finding Algorithms

## Aim
The aim of this program is to implement and analyze algorithms for finding the maximum and minimum elements in an array.

## Description

### Problem Statement
Finding the maximum and minimum elements in an array is a common problem in computer science. This program implements two different algorithms for solving this problem: linear search and divide and conquer.

### Algorithms Used

#### 1. Linear Search
- **Description**: Involves iterating through the array and updating the maximum and minimum values.
- **Time Complexity**:
  - Best Case: O(n) (when the maximum and minimum elements are at the ends of the array)
  - Average Case: O(n)
  - Worst Case: O(n) (when the array is sorted in non-increasing or non-decreasing order)
- **Space Complexity**:
  - Best Case: O(1)
  - Average Case: O(1)
  - Worst Case: O(1)

#### 2. Divide and Conquer
- **Description**: Involves dividing the array into two halves and finding the maximum and minimum in each half recursively.
- **Time Complexity**:
  - Best Case: O(n) (when the array has only one element)
  - Average Case: O(n log n)
  - Worst Case: O(n log n)
- **Space Complexity**:
  - Best Case: O(log n)
  - Average Case: O(log n)
  - Worst Case: O(log n)

## Graph for Time Complexity

<img width="525" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/314541ae-8ce3-4935-a6ac-24651181b981">

## Output Generated
The output is the time taken by each algorithm to find the maximum and minimum elements in arrays of different sizes. The output is tabulated with the size of the array and the average time taken for 10 iterations.

## Use Cases
- Finding the largest and smallest elements in an array.
- Applications requiring basic statistics or data analysis.

