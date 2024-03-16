# Permutation Generation Algorithm Performance Analysis

## Aim
The aim of this program is to generate permutations of strings of varying lengths and analyze the performance of the permutation generation algorithm.

## Description

### Problem Statement
Given a string of characters, the task is to generate all possible permutations of the string.

### Method Used
The algorithm used to generate permutations is based on backtracking. It iterates through each character of the string, fixes it at the current position, and recursively generates permutations for the remaining characters. After generating permutations for each level, it backtracks by swapping characters back to their original positions.

## Algorithm Used
Backtracking Algorithm

## Pseudocode

- Function permutation(str, level, n)
- Input: 
    - str - String to generate permutations from
    - level - Current level in the permutation generation process
    - n - Length of the string
- Output:
    - Permutations of the string

1. If level equals n, return.
2. For i from level to n - 1:
    a. Swap str[level] with str[i].
    b. Recursively call permutation with incremented level.
    c. Swap str[level] with str[i] to backtrack.

### Output Generated
The output of the program is the time taken to generate permutations of strings of different lengths. The time taken is averaged over multiple iterations to provide a more accurate representation of performance.

## Time Complexity
The time complexity of generating permutations of a string of length `n` using backtracking is O(n!).

## Time Complexity Graph:

<img width="493" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/f0e411ee-bd52-4a76-8556-f19798dda8bd">


## Space Complexity
The space complexity of the backtracking algorithm depends on the implementation. In this case, it is O(n), where `n` is the length of the string.


