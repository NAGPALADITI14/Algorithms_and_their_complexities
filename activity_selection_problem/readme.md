# Lecture Scheduling Problem

## Aim
The aim of this project is to analyze different algorithms for solving the lecture scheduling problem and evaluate their performance in terms of time complexity and space complexity.

## Description
The lecture scheduling problem involves scheduling a set of lectures in such a way that no two overlapping lectures are scheduled at the same time. Three different methods are implemented to solve this problem:

1. **Method 1: Sort by End Time:** In this method, lectures are sorted based on their end times, and then a greedy approach is used to select non-overlapping lectures.
   
2. **Method 2: Sort by Duration:** Here, lectures are sorted based on their duration (end time - start time), and a greedy approach is applied to select non-overlapping lectures.
   
3. **Method 3: Sort by Start Time:** Lectures are sorted based on their start times, and a greedy approach is employed to select non-overlapping lectures.

## Algorithms
### Method 1: Sort by End Time
1. Sort lectures by end time in ascending order.
2. Initialize solution to 1 and i to 0.
3. Iterate over lectures from index 1 to n-1:
    - If the start time of the current lecture is greater than or equal to the end time of the previous lecture:
        - Increment solution by 1.
        - Update i to the current index.
4. Return the value of solution as the maximum number of non-overlapping lectures.


### Method 2: Sort by Duration
1. Calculate the duration (end time - start time) for each lecture.
2. Sort lectures by duration in ascending order.
3. Initialize solution to 1 and i to 0.
4. Iterate over lectures from index 1 to n-1:
    - If the start time of the current lecture is greater than or equal to the end time of the previous lecture:
        - Increment solution by 1.
        - Update i to the current index.
5. Return the value of solution as the maximum number of non-overlapping lectures.


### Method 3: Sort by Start Time
1. Sort lectures by start time in ascending order.
2. Initialize solution to 1 and i to 0.
3. Iterate over lectures from index 1 to n-1:
    - If the start time of the current lecture is greater than or equal to the end time of the previous lecture:
        - Increment solution by 1.
        - Update i to the current index.
4. Return the value of solution as the maximum number of non-overlapping lectures.


## Output Generated
The output of each method includes the number of lectures scheduled and the time taken to schedule them.

## Time Complexity
The time complexity of each method varies based on the sorting algorithm used and the approach for selecting non-overlapping lectures.

- **Method 1:** Best case - O(n log n), Average case - O(n log n), Worst case - O(n log n)
- **Method 2:** Best case - O(n log n), Average case - O(n log n), Worst case - O(n log n)
- **Method 3:** Best case - O(n log n), Average case - O(n log n), Worst case - O(n log n)

## Graph for Time Complexity

<img width="468" alt="activity _selection_problem" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/a0b2ba40-f2ce-4f54-9a5d-c10ad6eee15f">

## Space Complexity
The space complexity of each method depends on the data structures used for sorting and storing the lectures.

- **Method 1:** Best case - O(n), Average case - O(n), Worst case - O(n)
- **Method 2:** Best case - O(n), Average case - O(n), Worst case - O(n)
- **Method 3:** Best case - O(n), Average case - O(n), Worst case - O(n)

## Use Cases
The lecture scheduling problem has applications in various fields, including academic scheduling, conference scheduling, and event management.






