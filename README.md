# AlgoVisualization: MST Algorithm Visualizer WebApp

This is a webapp build using JavaScript that visualizes 2 algorithms to get a Minimum Spanning Tree for the users: Prim's algorithm & Kruskal's algorithm. 
Prims's algorithm is designed to identify a minimum spanning tree in a weighted undirected graph. It accomplishes this by selecting a set of edges that form a tree encompassing all vertices, while minimizing the total weight of the included edges. The algorithm constructs the tree gradually, beginning with a user-selected starting vertex, and at each stage, it appends the most cost-effective link between the existing tree and a new vertex. 
Kruskal's algorithm is utilized to identify a minimum spanning tree within a weighted undirected graph as well. Its objective is to discover a subset of edges that construct a tree incorporating all vertices while minimizing the cumulative weight of the tree's edges. The algorithm begins by sorting the edges based on their weights and then incrementally adds them to the expanding forest. It ensures that no edges are added that would introduce a cycle into the tree. 


## How to use the project
1. Clone this project using https://github.com/ramisa7/AlgoVisualization.git
2. Open the Interactive.html file to run the project 


## Features of this Project 
- User Manual to help the users understnad how to opearte the WebApp: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/bb660751-9d1b-42b6-b897-216ea4e6e4ad)

- Two different spaces for Prim's and Kruskal's that allows user to run different algorithms at the same time: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/7805654c-36e9-4a08-8bab-8c25f36bfc0f)

- Lets the user add vertices in the separate boxes: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/31e9d524-e27a-463c-a021-117bd28e2719)

- Lets the user add vertices between two vertices with an edgeweight of user's choice: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/30a71dd8-eeb6-496d-a2b2-9891e801fd4f)

- Visualizing the vertices & the edges for better understanding of user: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/ad8476a6-3cc9-4a2d-8e1f-78c27e1ece15)

- Buttons to use built in graphs if the user wants & to clear the screen: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/fcb27d5d-35c4-47c1-b6f2-310229003bdd)

- Highlight edges to show the edges that build the Minimum Spanning Tree: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/c68ebc94-14a4-4fe7-8883-06bc82e68c18)

- Displaying the total cost using each algorithm: 

![image](https://github.com/ramisa7/AlgoVisualization/assets/92804590/3859566b-7cc0-41a2-a8d9-2bcdc4c75221)

- Prevents the user from adding any other nodes/vertices or edges while either of the algorithm is running. 

## Tech Stacks used to build this Project 

This WebApp has been built using HTML, CSS & JavaScript. 
To implement the algorithms, the following data structures has been used: 
- Adjacency List to keep note of the neighbors of the vertices.
- Priority Queue using minheap to always find the cheapest vertix from any vertix.
- Set to keep track of visited vertices.
- Breadth First Search(BFS) to detect a cycle in Kruskal's Algorithm while building the MST. 
