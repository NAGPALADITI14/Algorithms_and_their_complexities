Binary Search

Overview
    Binary search is a powerful and efficient algorithm for finding a specific element in a sorted array. This algorithm follows the divide and conquer paradigm, reducing the search space by half in each step. This README provides a concise guide to understanding and implementing binary search.

Algorithm:
    Binary search works by repeatedly dividing the search interval in half. It compares the middle element of the interval to the target value and eliminates half of the remaining elements from consideration.

Initialize: Set the left and right pointers to the beginning and end of the array, respectively.

Iterate: While the left pointer is less than or equal to the right pointer, repeat the following steps.

Calculate Midpoint: Compute the midpoint index as mid = (left + right) / 2.

Compare: Compare the element at the midpoint with the target value.

If they are equal, the search is successful, and the index of the element is found.
If the target is less than the midpoint element, update the right pointer to mid - 1.
If the target is greater than the midpoint element, update the left pointer to mid + 1.
Repeat: Continue the process until the target element is found or the left pointer exceeds the right pointer.


Time Complexity : 
Binary search has a time complexity of O(log n), where n is the number of elements in the array. This efficiency makes it significantly faster than linear search algorithms, especially for large datasets.

Graph for time complexity :

<img width="494" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/0c2491d3-5e84-4c6b-928b-95704a6e7850">


Space Complexity :
Binary search has a space complexity of O(1), meaning it uses a constant amount of extra space regardless of the size of the input array.

Usage
Binary search is suitable for situations where the data is sorted, and quick retrieval of a specific element is required. It is commonly used in various applications, such as searching in databases, spell checking, and in algorithms like merge sort.

Implementation Tips:
Ensure that the input array is sorted before applying binary search.

Take care to handle edge cases, such as empty arrays or arrays with a single element.

Consider variations of binary search for specific use cases, such as binary search in rotated sorted arrays.
