# Knapsack Problem Solutions

## Aim
The aim of this program is to implement three different approaches to solving the knapsack problem and analyze their time complexity for different input sizes.

## Description

### Problem Statement
The knapsack problem is a classic optimization problem where the goal is to maximize the total value of items that can be included in a knapsack without exceeding its capacity. This program implements three different approaches to solving the knapsack problem: 
1. Sorting items based on weights and filling the knapsack.
2. Sorting items based on profits and filling the knapsack.
3. Sorting items based on the ratio of profit to weight and filling the knapsack.

### Method Used
The methods used are variations of the greedy algorithm for the knapsack problem. Each approach sorts the items differently before selecting items to include in the knapsack based on specific criteria.

### Algorithm
1. Sort the items based on specific criteria (weights, profits, or profit-to-weight ratio).
2. Iterate through the sorted items and include items in the knapsack until its capacity is reached or all items are considered.

## Output Generated
The output is the time taken by each approach to solve the knapsack problem for different input sizes. The output is tabulated with the input size and the average time taken for 10 iterations.

## Time Complexity
### Approach 1: Sorting items based on weights
- Best Case: O(n log n)
- Average Case: O(n log n)
- Worst Case: O(n log n)

### Approach 2: Sorting items based on profits
- Best Case: O(n log n)
- Average Case: O(n log n)
- Worst Case: O(n log n)

### Approach 3: Sorting items based on profit-to-weight ratio
- Best Case: O(n log n)
- Average Case: O(n log n)
- Worst Case: O(n log n)

## Graph for Time Complexity

<img width="472" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/8fdd7d88-f8b5-405f-b96a-eaadcd1d053a">

## Space Complexity
- Best Case: O(n)
- Average Case: O(n)
- Worst Case: O(n)

## Use Cases
- Resource allocation problems where items have varying weights and profits.
- Applications in finance, logistics, and resource management where optimization is required.

