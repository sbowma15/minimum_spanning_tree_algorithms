Minimum Spanning Tree Algorithms

This Python file, minimum_spanning_tree_algorithms.py, provides implementations of two popular algorithms for finding the Minimum Spanning Tree (MST) of a graph: Prim's algorithm and Kruskal's algorithm.

Overview
File: minimum_spanning_tree_algorithms.py
Usage
Ensure the file minimum_spanning_tree_algorithms.py is in the same directory as your Python script or Jupyter Notebook.

Import the required functions:

python
from minimum_spanning_tree_algorithms import adjMatFromFile, prims, kruskals, assign04_main
Create an adjacency matrix from a file:

python
graph = adjMatFromFile("your_graph_file.txt")
Run Prim's algorithm:

python
result_prim = prims(graph)
Run Kruskal's algorithm:

python
Copy code
result_kruskal = kruskals(graph)
(Optional) Demonstrate both algorithms and compare their MST costs:

python
assign04_main()
Functions
adjMatFromFile: Creates an adjacency/weight matrix from a file with vertices, neighbors, and weights.

prims: Uses Prim's algorithm to find the MST.

kruskals: Uses Kruskal's algorithm to find the MST.

assign04_main: Demonstrates the functions, starting with creating the graph.

Feel free to adapt the provided code to suit your specific needs. If you have any questions or encounter issues, please refer to the comments within the code or seek additional assistance.
