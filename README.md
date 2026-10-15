# Pathfinding Visualizer

A browser-based React app by **Tayyaba** for exploring pathfinding algorithms on a grid. Choose an algorithm, add obstacles, and watch the visited nodes and resulting route animate from the start node to the end node.

## Features

- Visualize Dijkstra's algorithm, breadth-first search (BFS), and depth-first search (DFS).
- Edit the 25 × 30 grid by toggling wall-creation mode and clicking or dragging across cells.
- Drag the start and end nodes to new positions.
- Animate the explored nodes and route to the end node.
- Clear walls or reset visited nodes to try another search.

DFS explores one branch at a time and does not guarantee a shortest route. Dijkstra's algorithm and BFS find a shortest route on this unweighted grid.

## Getting Started

You need Node.js and npm installed.

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

- `npm start` starts the development server.
- `npm test` runs the test suite in watch mode.
- `npm run build` creates a production build in the `build` directory.

## Author

Created by Tayyaba.
