# Overview
A graph is composed of **vertices** and **edges**.

$$G = (V, E)$$

## Types Graph
* Directed Graphs
  * Directed Acyclic Graphs (DAG)
* Non-directed Graphs
* Connected Graphs
  * Strongly Connected Graphs
* Non-connected Graphs
* Weighted Graphs

## Representation of Graphs
Adjacency Matrix
* Data stored in a matrix (2D array) `G[i][j] = 1` (connected / outgoing edges)
* Space Complexity = $|V|^2 = O(n^2)$

Adjacency List
* Data stored in a list of linked lists.
* Space Complexity = $|V| + 2|E| = O(n)$

Compact List
* Data stored in a 1D list.
* Space Complexity = $|V| + 2|E| = O(n)$

## Graph Traversal
* BFS (Breadth First Search)
* DFS (Depth First Search)