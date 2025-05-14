# 🧭 Pathfinding Visualizer

Welcome to **Pathfinding Visualizer**!  
I built this project to explore and visualize the fascinating world of pathfinding algorithms. With an intuitive UI and animated steps, this tool helps you understand how different algorithms traverse a grid to find the optimal (or not-so-optimal) path.

> **🌐 Live Demo (Google Chrome Recommended):**  
> [https://clementmihailescu.github.io/Pathfinding-Visualizer/](https://clementmihailescu.github.io/Pathfinding-Visualizer/)

---

## 📌 Features

- 🎯 Visualize multiple pathfinding algorithms in action
- ⚙️ Choose between weighted and unweighted algorithms
- 🧱 Draw walls, set custom start and end nodes
- 🚀 Maze generation via recursive division
- 📐 Adjustable grid and animation speed
- 🧪 Real-time node exploration animation

---

## 🧠 Supported Algorithms

### 🔷 Weighted Algorithms

| Algorithm                     | Shortest Path Guaranteed | Notes                                              |
|------------------------------|---------------------------|----------------------------------------------------|
| **Dijkstra’s Algorithm**     | ✅ Yes                    | The father of pathfinding algorithms               |
| **A* Search**                | ✅ Yes                    | Heuristic-driven, faster than Dijkstra             |
| **Greedy Best-First Search** | ❌ No                     | Fast, but doesn't guarantee optimality             |
| **Swarm Algorithm**          | ❌ No                     | Balanced heuristic-based hybrid                    |
| **Convergent Swarm**         | ❌ No                     | Faster, more heuristic-heavy Swarm variant         |
| **Bidirectional Swarm**      | ❌ No                     | Swarm from both start and end                      |
| **Batched Swarm**            | ❌ No                     | Processes nodes in batches for performance tuning  |

### ⚪ Unweighted Algorithms

| Algorithm               | Shortest Path Guaranteed | Notes                              |
|------------------------|---------------------------|------------------------------------|
| **Breadth-First Search (BFS)** | ✅ Yes            | Ideal for unweighted graphs        |
| **Depth-First Search (DFS)**   | ❌ No             | Often inefficient for pathfinding  |

---

## 🌀 Maze Generation

- **Recursive Division Maze**:  
  A classic and visually satisfying method for generating complex mazes. It splits the grid recursively while adding walls to create challenging environments.

---

## 🐝 About the Swarm Algorithm

The **Swarm Algorithm** is a hybrid I co-developed with Hussein Farah. It blends elements of Dijkstra’s and A* Search:

- Like A*, it uses heuristics to target the end node.
- Like Dijkstra’s, it also updates distances from the start node and explores more broadly.

The result is a **triangle-shaped pathfinding pattern**, ideal for applications where enemies or agents must track both a goal and nearby threats—hence the name "Swarm."

---

## 🛠 How to Run This Project Locally

> 💡 Make sure you have **Node.js** and **npm** installed on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/clementmihailescu/Pathfinding-Visualizer.git
cd Pathfinding-Visualizer
```
### 2. Install Dependencies
```bash
npm install
```

### 3.Start the Development Server
```bash
npm start
```
This will run the app in development mode. Open http://localhost:3000 to view it in your browser.

### 4. Build for Production
```bash
npm run build
```

## 🚀 Tech Stack
-Frontend: React (JavaScript)
-Styling: CSS
-Visualization: DOM-based animation

## Author
[AKASUMITLAMBA](https://github.com/akasumitlamba)

