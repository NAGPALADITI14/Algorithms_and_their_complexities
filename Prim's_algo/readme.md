# Minimum Spanning Tree (Prim's Algorithm) Performance Analysis

## Aim
The aim of this program is to find the Minimum Spanning Tree (MST) of a given graph using Prim's algorithm and analyze its performance.

## Description

### Problem Statement
Given a weighted undirected graph, the task is to find the minimum spanning tree, which is a subset of the edges that forms a tree that includes every vertex, where the total weight of all edges in the tree is minimized.

### Method Used
The algorithm used to find the minimum spanning tree is Prim's algorithm. Prim's algorithm is a greedy algorithm that grows a solution from a starting vertex by adding the cheapest edge to the growing tree at each step until all vertices are included in the tree.

### Algorithm
1. Initialize a set of vertices near[], where near[i] stores the nearest vertex to vertex i that is included in the MST.
2. Initialize a set of minimum costs minCost[] for each vertex, where minCost[i] stores the cost of the cheapest edge connecting vertex i to a vertex in the MST.
3. Start with an arbitrary vertex as the starting point.
4. At each step, select the vertex with the minimum minCost[] value that is not yet included in the MST.
5. Update near[] and minCost[] based on the newly added vertex.
6. Repeat steps 4 and 5 until all vertices are included in the MST.

### Output Generated
The output of the program is the set of edges forming the Minimum Spanning Tree.

## Time Complexity
- Best Case: O(V^2) where V is the number of vertices. This occurs when the graph is a complete graph.
- Average Case: O(V^2)
- Worst Case: O(V^2)

## Space Complexity
- Best Case: O(V) where V is the number of vertices. This occurs when the graph is sparse.
- Average Case: O(V)
- Worst Case: O(V)

## Use Cases
- Finding the minimum spanning tree is useful in various scenarios such as network design, circuit design, clustering, and routing algorithms.

