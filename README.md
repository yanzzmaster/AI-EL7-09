# Search Algorithms Implementation in Python

## Introduction
This repository provides implementations of fundamental Artificial Intelligence (AI) search algorithms using Python. Search algorithms are essential techniques used in problem-solving and pathfinding within state spaces or graphs. 

This project covers two main categories of search methods:
1. **Uninformed Search (Blind Search):**
   - **Breadth-First Search (BFS):** Explores nodes level-by-level to guarantee the shortest path in unweighted graphs.
   - **Depth-First Search (DFS):** Explores as deep as possible along each branch before backtracking.
2. **Informed Search (Heuristic Search):**
   - **A* (A-Star) Search:** Combines the actual cost to reach a node $g(n)$ and a heuristic estimate $h(n)$ to find the optimal path in weighted graphs ($f(n) = g(n) + h(n)$).

---

## Requirement
To run this project, make sure you have the following installed on your system:

* **Python 3.x** (Python 3.7 or higher recommended)
* **Visual Studio Code (VS Code)** (Optional, recommended code editor)
* **Git** (For cloning and managing the repository)

*Note: No external third-party Python libraries are required, as the implementation uses Python's built-in modules (`collections` and `heapq`).*

---

## How to Use

### 1. Clone the Repository
Clone this repository to your local machine using Git:
```bash
git clone [https://github.com/gerton123/AI-EL7-09.git](https://github.com/gerton123/AI-EL7-09.git)
cd AI-EL7-09
