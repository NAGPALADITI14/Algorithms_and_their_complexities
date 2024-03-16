
# Randomized Quick Sort Performance Analysis

## Aim
The aim of this program is to analyze the performance of the Randomized Quick Sort algorithm by sorting arrays of varying sizes.

## Description

### Problem Statement
Given an array of integers, the task is to sort the array in non-decreasing order using the Randomized Quick Sort algorithm.

### Method Used
- **Randomized Quick Sort**: Randomized Quick Sort is an extension of the Quick Sort algorithm. Instead of selecting the first element as the pivot, it selects a random element as the pivot. This helps avoid worst-case scenarios and ensures better average performance.

### Output Generated
The output of the program is the time taken to sort arrays of varying sizes using the Randomized Quick Sort algorithm. The time taken is averaged over multiple iterations to provide a more accurate representation of performance.

## Time Complexity
- Best Case: O(n log n) where n is the number of elements in the array.
- Average Case: O(n log n)
- Worst Case: O(n^2) where n is the number of elements in the array. However, the probability of encountering the worst-case scenario is very low due to the random selection of the pivot.

## Graph for Time Complexity  :

<img width="486" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/333903c0-2cf5-4478-a2df-c9530ec977f1">

## Space Complexity
- Best Case: O(log n) where n is the number of elements in the array. This is the space required for the recursive call stack.
- Average Case: O(log n)
- Worst Case: O(n) where n is the number of elements in the array. This occurs when the recursion depth is equal to the number of elements in the array.

## Use Cases
- Randomized Quick Sort is commonly used in situations where the input data is unsorted or partially sorted. It provides efficient performance across a wide range of input distributions and is favored for general-purpose sorting.

