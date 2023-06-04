# AlgoVisualization: MST Algorithm Visualizer WebApp

This is a webapp build using JavaScript that visualizes 2 algorithms to get a Minimum Spanning Tree for the users: Prim's algorithm & Kruskal's algorithm. 
Prims's algorithm is designed to identify a minimum spanning tree in a weighted undirected graph. It accomplishes this by selecting a set of edges that form a tree encompassing all vertices, while minimizing the total weight of the included edges. The algorithm constructs the tree gradually, beginning with a user-selected starting vertex, and at each stage, it appends the most cost-effective link between the existing tree and a new vertex. 
Kruskal's algorithm is utilized to identify a minimum spanning tree within a weighted undirected graph as well. Its objective is to discover a subset of edges that construct a tree incorporating all vertices while minimizing the cumulative weight of the tree's edges. The algorithm begins by sorting the edges based on their weights and then incrementally adds them to the expanding forest. It ensures that no edges are added that would introduce a cycle into the tree. 


## How to use the project
1. Clone this project using https://github.com/ramisa7/AlgoVisualization.git
2. Open the Interactive.html file to run the project 


## Features of this Project 
- User Manual to help the users understnad how to opearte the WebApp: 
[image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/a68c68ef-69d8-4555-92e5-3ceff708d570)


## Tech Stacks used to build this Project 

This WebApp has been built using HTML, CSS & JavaScript. 
To implement the algorithms, the following data structures has been used: 
- Adjacency List to keep note of the neighbors of the vertices.
- Priority Queue using minheap to always find the cheapest vertix from any vertix.
- Set to keep track of visited vertices.
- Breadth First Search(BFS) to detect a cycle in Kruskal's Algorithm while building the MST. 
