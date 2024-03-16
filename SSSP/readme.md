# Single Source Shortest Path (SSSP) Algorithm Performance Analysis

## Aim
The aim of this program is to analyze the performance of the Single Source Shortest Path (SSSP) algorithm by finding the shortest path from a source vertex to all other vertices in a graph.

## Description

### Problem Statement
Given a graph represented as an array of edges with their corresponding costs, and a source vertex, the task is to find the shortest path from the source vertex to all other vertices in the graph.

### Method Used
- **SSSP Algorithm**: The Single Source Shortest Path algorithm is used to find the shortest path from a source vertex to all other vertices in a graph. In this program, a simplified version of the algorithm is implemented using arrays to represent the graph and the distances from the source vertex to each vertex.

### Algorithm: Single Source Shortest Path (SSSP) using Dijkstra's Algorithm

- Input: Graph G, Source vertex S
- Output: Shortest distances from source vertex S to all other vertices in the graph

1. Initialize an empty priority queue (min-heap) Q to store vertices based on their tentative distances from the source vertex.
2. Initialize an array dist[] to store the shortest distances from the source vertex S to all other vertices in the graph.
3. Initialize dist[S] = 0 and dist[v] = ∞ for all other vertices v in the graph.
4. Insert all vertices of the graph into the priority queue Q with their corresponding distances as the key.
5. While Q is not empty:
   5.1. Extract the vertex u with the minimum distance from Q.
   5.2. For each neighbor v of u:
        - Calculate the tentative distance from the source vertex S to v through u as dist[u] + weight(u, v).
        - If the tentative distance is smaller than the current distance dist[v], update dist[v] with the new distance.
        - Update the priority queue Q with the updated distance of vertex v.
6. Return the array dist[], which contains the shortest distances from the source vertex S to all other vertices.



### Output Generated
The output of the program is the time taken to compute the shortest paths from the source vertex to all other vertices in the graph. As input, the program accepts the graph's edges and their corresponding costs.

## Time Complexity
- **Overall Time Complexity**: O(V^2), where V is the number of vertices in the graph.
- **Explanation**: The SSSP algorithm has a time complexity of O(V^2) for an adjacency matrix representation of the graph, where V is the number of vertices. This is because, in each iteration, the algorithm scans through all vertices to find the vertex with the minimum distance, resulting in a total time complexity of O(V^2).

## Space Complexity
- **Space Complexity**: O(V), where V is the number of vertices in the graph.
- **Explanation**: The space complexity of the SSSP algorithm is determined by the arrays used to store the distances from the source vertex to all other vertices and the parent pointers. Since these arrays have a size equal to the number of vertices, the space complexity is O(V).

## Use Cases
- SSSP algorithms are commonly used in various applications such as network routing protocols, GPS navigation systems, and pathfinding algorithms in video games.

