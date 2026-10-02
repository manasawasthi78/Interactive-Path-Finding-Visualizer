# PathVision

A React + Vite pathfinding visualizer for BFS, DFS, Dijkstra, A*, and Greedy Best-First Search.

## Features
- Interactive 20×20 grid
- Walls and weighted terrain (2 / 5)
- Animated pathfinding
- BFS, DFS, Dijkstra, A*, Greedy Best-First Search
- Pause / resume and speed controls
- Algorithm comparison benchmark
- Maze generator preview
- Performance and settings pages
- Responsive dark/light UI

## Run locally

```bash
npm install
npm run dev
```

For a production build:

```bash
npm run build
npm run preview
```

## Project structure

- `src/algorithms/pathfinding.js` — search algorithms and grid helpers
- `src/pages/Visualizer.jsx` — interactive visualizer
- `src/pages/Algorithms.jsx` — algorithm reference
- `src/pages/Comparison.jsx` — benchmark runner
- `src/pages/MazeGenerator.jsx` — maze UI
- `src/pages/Performance.jsx` — metrics view
- `src/pages/Settings.jsx` — visualization settings
- `src/pages/About.jsx` — project information
- `src/App.jsx` / `src/App.css` — application shell and styling
