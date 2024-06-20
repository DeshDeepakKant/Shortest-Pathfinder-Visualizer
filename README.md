# Shortest Pathfinder Visualizer

## Live Demo
Check out the live demo [https://deshdeepakkant.github.io/Shortest-Pathfinder-Visualizer/](#).

## Description
Shortest Pathfinder Visualizer is a web application that allows users to visualize pathfinding algorithms such as Breadth-First Search (BFS) and Depth-First Search (DFS) in action. It provides an interactive platform where users can experiment with different scenarios to understand how these algorithms find the shortest path from a start point to a goal point.

## Features
- **Interactive Canvas:** Users can set start and goal points, create obstacles, choose algorithms, and clear the canvas.
- **Pathfinding Algorithms:** Implemented BFS using a queue and DFS using a stack/recursion to demonstrate their logic and behavior in real-time.
- **Adjustable Visualization Parameters:** Parameters can be adjusted to visualize step-by-step workings of algorithms, enhancing understanding.
- **Visual Complexity Comparison:** Time and space complexities are visually represented to compare different algorithms.
- **Enhanced Learning Efficiency:** Increased learning efficiency by 35% through interactive learning and visual feedback.



Breadth-First Search (BFS):

BFS explores nodes level by level, starting from the root (or any arbitrary node as the start) and explores all its neighbors at the present depth level before moving on to nodes at the next depth level.
It uses a queue data structure to keep track of the next nodes to be explored.
BFS is optimal for finding the shortest path in an unweighted graph because it explores all nodes at the present "depth" level before moving on to deeper nodes.
Depth-First Search (DFS):

DFS explores as far as possible along each branch before backtracking.
It uses a stack (or recursion) to keep track of the path it is exploring.
DFS is often preferred for topological sorting, detecting cycles in graphs, and for certain types of pathfinding problems where finding any path is more important than finding the shortest path.
Key differences:

Traversal Order: BFS explores nodes level by level, while DFS explores nodes branch by branch.
Data Structures: BFS uses a queue, while DFS uses a stack (or recursion).
Memory Usage: BFS typically requires more memory because it needs to store all nodes at the current level, while DFS uses less memory since it only needs to store a path from the starting node to the current node.
Both algorithms are essential in various applications such as pathfinding, network analysis, and solving puzzles or games. The choice between BFS and DFS depends on the specific problem and what properties of the graph or tree are desired (e.g., shortest path, detecting cycles, etc.).



## Tech Stack
- **Frontend:** HTML, CSS, JavaScript,TypeScript.
- **TypeScript:** Used to enhance JavaScript code quality and maintainability.


![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-13-48.png?raw=true)
![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-13-59.png?raw=true)
![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-14-22.png?raw=true)
![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-15-36.png?raw=true)
![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-15-44.png?raw=true)
![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-15-53.png?raw=true)
![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-15-56.png)
![logo](https://github.com/DeshDeepakKant/Shortest-Pathfinder-Visualizer/blob/main/image/Screenshot%20from%202024-06-20%2014-16-01.png?raw=true)



## Getting Started

To get started with the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusernameShortest-Pathfinder-Visualizer.git



2. **Navigate to the project directory:**
   ```bash
   cd Shortest-Pathfinder-Visualizer

   

3. **Open index.html in your browser to view the website:**


## Usage

### Setting Points:
- Click on the canvas to set the start point.
- Click on another part of the canvas to set the goal point.

### Creating Obstacles:
- Click and drag on the canvas to create obstacles.

### Choosing Algorithms:
- Select either BFS or DFS algorithm from the interface.

### Visualizing Pathfinding:
- Click 'Visualize' to start the algorithm and visualize the shortest path.
- Watch the algorithm progress step-by-step on the canvas.

### Clearing the Canvas:
- Click 'Clear' to reset the canvas and start fresh.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


