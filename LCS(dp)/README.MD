# Longest Common Subsequence (LCS) Algorithm Using Dynamic Programming

## Description
The Longest Common Subsequence (LCS) algorithm using dynamic programming finds the longest subsequence shared between two strings. It creates a matrix to store intermediate results, filling it by comparing characters in the strings. The algorithm then traces back through the matrix to reconstruct the LCS. Its time complexity is O(m*n), where m and n are the lengths of the input strings.

## Algorithm
1. **Initialization:**
   - Initialize a 2D array `L[m+1][100]` to store the lengths of LCSs for substrings of X and Y.
   - Initialize the first row and column of `L` with zeros, as LCS with an empty string is zero.

2. **Dynamic Programming Loop:**
   - Iterate through the substrings of X and Y using nested loops.
   - If the characters at the current positions in X and Y match, increment `L[i][j]` by 1.
   - Otherwise, set `L[i][j]` to the maximum of `L[i-1][j]` and `L[i][j-1]`, as LCS can be formed by skipping characters in either string.

3. **Backtracking for LCS:**
   - Using the computed `L` array, backtrack to reconstruct the LCS by following the arrows (left, up, or diagonal) based on the values in `L`.

4. **Print LCS with Arrows:**
   - Print the LCS along with arrows (<- or ^|) to indicate the direction of backtracking.

5. **Main Function:**
   - Initialize strings S1 and S2.
   - Call the `lcs` function to compute the length of the LCS and print the LCS with arrows.

## Time Complexity
The time complexity of the Longest Common Subsequence (LCS) algorithm using dynamic programming can be summarized as follows:
- Best-case time complexity: O(m * n)
- Average-case time complexity: O(m * n)
- Worst-case time complexity: O(m * n)

Here, m and n are the lengths of the input strings X and Y, respectively.

## OUTPUT GENERATED

<img width="472" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/9842a7fe-b901-4cae-8d7b-2a0f88c5942d">
