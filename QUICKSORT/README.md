# Quick Sort vs. Iterative Quick Sort Performance Analysis

## Aim
The aim of this program is to compare the performance of Quick Sort and Iterative Quick Sort algorithms by sorting arrays of varying sizes.

## Description

### Problem Statement
Given an array of integers, the task is to sort the array in non-decreasing order using the Quick Sort and Iterative Quick Sort algorithms.

### Method Used
- **Quick Sort**: Quick Sort is a comparison-based sorting algorithm that employs a divide-and-conquer strategy. It selects a pivot element from the array and partitions the array into two subarrays: elements less than the pivot and elements greater than the pivot. The algorithm then recursively sorts the subarrays.
- **Iterative Quick Sort**: Iterative Quick Sort is an iterative version of the Quick Sort algorithm. Instead of using recursive calls, it employs a stack to simulate recursion and sort the array.

### Output Generated
The output of the program is the time taken to sort arrays of varying sizes using both Quick Sort and Iterative Quick Sort algorithms. The time taken is averaged over multiple iterations to provide a more accurate representation of performance.

## Time Complexity
### Quick Sort
- Best Case: O(n log n) where n is the number of elements in the array. This occurs when the partition process always picks the middle element as the pivot.
- Average Case: O(n log n)
- Worst Case: O(n^2) where n is the number of elements in the array. This occurs when the partition process always picks the greatest or smallest element as the pivot, resulting in an unbalanced partition.

### Iterative Quick Sort
- Best Case: O(n log n) where n is the number of elements in the array.
- Average Case: O(n log n)
- Worst Case: O(n^2) where n is the number of elements in the array.

## Graph for Time Complexity

<img width="513" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/71e5a729-c708-4ede-bae7-d9cba17f633a">

## Space Complexity
### Quick Sort
- Best Case: O(log n) where n is the number of elements in the array. This is the space required for the recursive call stack.
- Average Case: O(log n)
- Worst Case: O(n) where n is the number of elements in the array. This occurs when the recursion depth is equal to the number of elements in the array.

### Iterative Quick Sort
- Best Case: O(log n) where n is the number of elements in the array. This is the space required for the stack used in the iterative approach.
- Average Case: O(log n)
- Worst Case: O(n) where n is the number of elements in the array. This occurs when the stack size becomes equal to the number of elements in the array.

## Use Cases
- Quick Sort and Iterative Quick Sort are widely used in various applications such as sorting large datasets, sorting elements in programming languages, and implementing efficient search algorithms.

