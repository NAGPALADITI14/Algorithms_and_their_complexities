# Graph Coloring Problem Using Backtracking

## Description
- The graph coloring problem involves assigning colors to vertices of a graph such that no two adjacent vertices share the same color. 
- Backtracking is often employed to efficiently find a valid coloring for a graph by recursively trying different color assignments and backtracking when conflicts arise, until a solution is found or deemed impossible. 
- This approach is crucial for solving various real-world optimization problems such as scheduling, register allocation, and map coloring.

## Algorithm
### Define Global Variables:
- Create a global array `x` to store colors for vertices. Initialize all elements to 0 initially.
- Set a constant `infinity` to represent an invalid color.

### Define Functions: 
#### a. `nextval(k, n, m, G)`:
- Increment the color of vertex `k` by 1 (`x[k] = (x[k] + 1) % (m + 1)`).
- If the color becomes 0 (meaning all colors have been tried), return.
- Check if the new color conflicts with adjacent vertices:
  - For each vertex `i` connected to `k` (i.e., `G[k][i] != 0`), if `x[i] == x[k]`, there is a conflict. In this case, break the loop.
- If no conflicts are found, continue the loop.

#### b. `mcoloring(k, G, n, m)`:
- Call `nextval(k, n, m, G)` to assign colors to vertex `k`.
- If `x[k]` becomes 0 (no valid color found), return.
- If all vertices are colored (`k == n`), print the colors in `x` and return.
- Otherwise, recursively call `mcoloring(k + 1, G, n, m)` to color the next vertex.

## Main Function:
- Initialize the graph `G`, number of vertices `n`, and number of colors `m`.
- Call `mcoloring(0, G, n, m)` to start coloring the vertices.

## Time Complexity
Time complexity for coloring `m` nodes:
- Best-case Time Complexity: O(m^n)
- Average-case Time Complexity: O(m^n * n^2)
- Worst-case Time Complexity: O(m^n * n^2)

##OUTPUT GENERATED
<img width="472" alt="image" src="https://github.com/NAGPALADITI14/Algorithms_and_their_complexities/assets/138228231/b037526b-a203-41b2-8eca-6b3a969488ce">
