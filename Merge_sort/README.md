Description:

The description provides an overview of the code's purpose and functionality. In this case, the code implements the Merge Sort algorithm, a divide-and-conquer approach to sorting. The algorithm divides an array into two halves, recursively sorts them, and merges them back together. This ensures a sorted order for the entire array.

Data Structures:

The primary data structure used in the code is an integer array. This array is manipulated during the sorting process. Subarrays are created during the divide phase, and the merging phase combines these subarrays back into a sorted array.

Output:

The output section showcases the expected result format when running the code. It displays the array sizes and their corresponding average execution times in nanoseconds. Users can use this output to analyze the algorithm's performance for different input sizes.
Overall, the README provides a comprehensive understanding of the Merge Sort algorithm, its implementation in C++, and how to experiment with the code to analyze its performance characteristics.

Time Complexity:

The time complexity of Merge Sort is analyzed. It is O(n log n), where "n" represents the number of elements in the array. This complexity arises from the logarithmic nature of the divide step (log n) and the linear time complexity of the merging step (n). The O(n log n) time complexity makes Merge Sort efficient for large datasets.

Time Complexity Graph:

A graphical representation of the time complexity is provided. The graph depicts the relationship between the input size (array size) and the corresponding time taken for the algorithm to execute. The graph visually shows the logarithmic nature of the time complexity.

<img width="513" alt="merge_sort" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/793ed1fd-9594-4688-a78b-f2081f554ae7">


Use Cases:

This section outlines scenarios where Merge Sort is particularly useful:
  1)Sorting Large Datasets: Merge Sort's efficiency with large datasets makes it suitable for scenarios where extensive          sorting is required.
  2)External Sorting in Databases: Merge Sort is commonly used in database management systems for external sorting due to        its ability to handle large amounts of data.
  3)Parallel Processing: The divide-and-conquer nature of Merge Sort allows for parallel processing, making it applicable in     parallel computing environments.

Instructions:

This part guides users on how to compile, run, and interpret the code. It includes steps to compile the C++ code, run the executable, and understand the output. Users are encouraged to experiment with different array sizes to observe the impact on execution times.

