# Binary Search Algorithm

## Aim
The aim of this program is to implement the binary search algorithm and analyze its time complexity for different input sizes.

## Description

### Problem Statement
Binary search is an efficient algorithm for finding an item from a sorted list of items. It works by repeatedly dividing in half the portion of the list that could contain the item, until you've narrowed down the possible locations to just one. This program implements binary search and measures its performance for various input sizes.

### Method Used
The method used is the iterative implementation of the binary search algorithm. Given a sorted array and a target value, the algorithm repeatedly divides the search interval in half until the target is found or the interval is empty.

### Algorithm
1. Initialize low to 0 and high to size - 1.
2. Repeat until low is less than or equal to high:
   - Calculate mid as (low + high) / 2.
   - If arr[mid] equals the target, return mid.
   - If arr[mid] is greater than the target, set high to mid - 1.
   - If arr[mid] is less than the target, set low to mid + 1.
3. If the loop exits, return -1 indicating the target was not found.

## Output Generated
The output is the time taken by the binary search algorithm to find a target element in arrays of different sizes. The output is tabulated with the size of the array and the average time taken for 10 iterations.

## Time Complexity
- Best Case: O(1) (when the target is found at the middle of the array)
- Average Case: O(log n)
- Worst Case: O(log n)

## Graph for Time Complexity

<img width="494" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/0c2491d3-5e84-4c6b-928b-95704a6e7850">

## Space Complexity
- Best Case: O(1)
- Average Case: O(1)
- Worst Case: O(1)

## Use Cases
- Searching in sorted arrays efficiently.
- Applications where quick searches in large datasets are needed, such as databases or search engines.


