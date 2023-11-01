# Maze Visualizer
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Road Map](#road-map)
- [Installation](#installation)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Maze Visualizer is a powerful web-based tool written in Svelte Kit, designed to generate and solve mazes using various algorithms. It provides an interactive and intuitive interface for users to visualize the process of maze generation and solving. This application caters to both desktop and mobile platforms, ensuring a seamless experience for users across different devices. Check out the Maze Visualizer

## Features
- Interactive maze generation and solving visualization
- Support for a diverse range of maze generation algorithms, including Recursive Backtracker, Prim's Algorithm, Kruskal's Algorithm, Eller's Algorithm, Wilson's Algorithm, Hunt and Kill Algorithm, Binary Tree Algorithm, Sidewinder Algorithm, Aldous-Broder Algorithm, and Growing Tree Algorithm
- Implementation of various maze solving algorithms, such as Depth-First Search (DFS), Breadth-First Search (BFS), A* Search, Dijkstra's Algorithm, Wall Follower (Left Hand Rule, Right Hand Rule), Trémaux's Algorithm, Dead-end filling Algorithm, Pledge Algorithm, Flood Fill Algorithm, and Bellman-Ford Algorithm
- Responsive design for optimal user experience on both mobile and desktop platforms

## Road Map
### Current Version
The current version of the Maze Visualizer includes the basic framework for maze generation and solving algorithms, providing a robust and visually appealing interface for users to interact with.

### Future Versions
1. Enhanced customization options for maze generation parameters
2. Integration of additional maze solving algorithms to provide a comprehensive set of options for users
3. Performance optimization for smoother visualization and faster processing of complex mazes

## Installation
To run the Maze Visualizer locally, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/ISmillex/maze-visualizer.git
   ```
2. Navigate to the project directory:
   ```
   cd maze-visualizer
   ```
3. Install the necessary dependencies using your preferred package manager:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm run dev -- --host
   ```
5. Open your web browser and go to http://localhost:5173 to access the Maze Visualizer.

## How It Works
The Maze Visualizer operates by utilizing various maze generation and solving algorithms, each with its unique approach and characteristics. Below is a brief overview of the time and space complexities, as well as the advantages and disadvantages of the implemented algorithms:

### Maze Generation Algorithms:
1. **Recursive Backtracker**: Time complexity varies based on implementation. Space complexity is O(n).
2. **Prim's Algorithm**: Time complexity is O(E log V). Space complexity is O(V).
3. **Kruskal's Algorithm**: Time complexity is O(E log V). Space complexity is O(V).
4. **Eller's Algorithm**: Time complexity is O(n). Space complexity is O(n).
5. **Wilson's Algorithm**: Time complexity is O(n^2). Space complexity is O(n).
6. **Hunt and Kill Algorithm**: Time complexity is O(n^2). Space complexity is O(1).
7. **Binary Tree Algorithm**: Time complexity is O(n). Space complexity is O(1).
8. **Sidewinder Algorithm**: Time complexity is O(n). Space complexity is O(n).
9. **Aldous-Broder Algorithm**: Time complexity is O(n^2). Space complexity is O(1).
10. **Growing Tree Algorithm**: Time complexity varies based on implementation. Space complexity varies based on implementation.

### Maze Solving Algorithms:
1. **Depth-First Search (DFS)**: Time complexity is O(V + E). Space complexity is O(V).
2. **Breadth-First Search (BFS)**: Time complexity is O(V + E). Space complexity is O(V).
3. **A* Search**: Time complexity varies based on the heuristic. Space complexity is O(V).
4. **Dijkstra's Algorithm**: Time complexity is O((V + E) log V). Space complexity is O(V).
5. **Wall Follower (Left Hand Rule, Right Hand Rule)**: Time complexity is highly dependent on the maze structure. Space complexity is O(1).
6. **Trémaux's Algorithm**: Time complexity is O(n). Space complexity is O(n).
7. **Dead-end filling Algorithm**: Time complexity is O(n). Space complexity is O(n).
8. **Pledge Algorithm**: Time complexity varies based on the maze structure. Space complexity is O(1).
9. **Flood Fill Algorithm**: Time complexity is O(n). Space complexity is O(n).
10. **Bellman-Ford Algorithm**: Time complexity is O(VE). Space complexity is O(V).

Understanding these complexities helps in choosing the appropriate algorithm based on specific requirements, such as speed, memory constraints, and maze characteristics.

## ## Contributing
To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



