## Tower of Hanoi Performance Measurement

### Aim:
The aim of this program is to measure the performance of the Tower of Hanoi algorithm by solving the problem for different numbers of disks and recording the time taken.

### Description:
The Tower of Hanoi is a classic problem that involves moving a stack of disks from one rod to another, with the constraint that only one disk can be moved at a time and a larger disk cannot be placed on top of a smaller disk. The problem can be solved recursively.

### Algorithm:
1. Define a function Tower_of_Hanoi(int n, char source, char spare, char destination) to implement the Tower of Hanoi algorithm:
    1.1. If n is greater than or equal to 1:
        1.1.1. Move the top n-1 disks from the source rod to the spare rod using the destination rod as a spare.
        1.1.2. Move the nth disk from the source rod to the destination rod.
        1.1.3. Move the n-1 disks from the spare rod to the destination rod using the source rod as a spare.


## Output:
The program generates output in the form of pairs of numbers representing the number of disks and the average time taken to solve the Tower of Hanoi problem for that number of disks. This output can be used to analyze the performance of the Tower of Hanoi algorithm.



## Time Complexity:
- The time complexity of the Tower of Hanoi algorithm is O(2^n), where n is the number of disks.

## Graph for Time Complexity:  

<img width="472" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/95fd1e9d-e184-42ad-9aec-046faa2efd15">

## Space Complexity:
- The space complexity of the Tower of Hanoi algorithm is O(n) due to the recursive calls on the stack.

## Use Cases:
- Performance analysis of the Tower of Hanoi algorithm for different numbers of disks.

