﻿# Graphs
A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.


Here is some common terminology used when working with Graphs:

- Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
- Edge - An edge is a connection between two nodes.
- Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
- Degree - The degree of a vertex is the number of edges connected to that vertex.

# Challenge

Implement your own Graph. The graph should be represented as an adjacency list, and should include the following methods:

- add node  
- add edge  
- get nodes  
- get neighbors  
- size  

# API

- AddNode()
Arguments: value.
Returns: The added node.
Add a node to the graph .
- AddEdge()
Arguments: 2 nodes to be connected by the edge, weight (optional).
Returns: nothing.
- Adds a new edge between two nodes in the graph.
If specified, assign a weight to the edge.
Both nodes should already be in the Graph.
- GetNodes()
Arguments: none.
Returns all of the nodes in the graph as a collection (set, list, or similar).
- GetNeighbors()
Arguments: node.
Returns a collection of edges connected to the given node.
Include the weight of the connection in the returned collection.
- Size()
Arguments: none.
Returns the total number of nodes in the graph.