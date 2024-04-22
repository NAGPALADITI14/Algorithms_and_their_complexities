# Knapsack Problem Using Backtracking

## Description
The Knapsack problem using backtracking involves finding the optimal combination of items to maximize the value while respecting a weight constraint. It explores different combinations recursively, making decisions at each step based on whether adding an item is feasible and improves the total value. Backtracking is employed when a dead-end is reached, optimizing the selection process for efficiency.

## Algorithm

### Function `print(s)`:
- Print the elements of the set.

### Function `find_max_value(s)`:
- Find the maximum value (first element) in the set.

### Function `find_max_path(s, max_value, p, w)`:
- Find the path of items that contribute to the maximum value.
- Iterate through the set and select items that contribute to the maximum value without exceeding weight constraints.

### Function `merge_purge(s1, s2, W)`:
- Merge two sets while purging elements that violate weight constraints.
- Iterate through elements of both sets, checking weight constraints and maximizing value.

### Function `knapsackMP(n, p, w, W)`:
- Initialize an empty set `s1` with a single element `{0, 0}`.
- Iterate through each item:
  - Create a new set `s2` by adding the current item to each element of `s1`.
  - Merge `s1` and `s2` while purging elements violating weight constraints.
  - Print the resulting set `s1`.
  - Find the maximum value in `s1` using `find_max_value`.
  - Find the path of items contributing to the maximum value using `find_max_path`.
  - Print the maximum value and the selected items contributing to it.

## Main Function
- Initialize input variables (number of items `n`, values `p`, weights `w`, and knapsack capacity `W`).
- Call `knapsackMP` with the input parameters.

## OUTPUT GENERATED
<img width="472" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/9577f5af-a912-4220-94de-13e3cdb8aa60">
