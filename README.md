# A* Pathfinding Visualizer

## Overview

This project is an interactive visualization of the A* (A-Star) search algorithm implemented using Python and Pygame. It demonstrates how the algorithm finds the shortest path between two points on a grid using heuristic-based search.

---

## Features

* Interactive grid-based interface
* Set start and end points
* Add and remove obstacles
* Visualize A* algorithm step-by-step
* Displays shortest path dynamically

---

## How It Works

The A* algorithm uses the function:

f(n) = g(n) + h(n)

* **g(n)** → actual cost from start node
* **h(n)** → heuristic estimate (Manhattan distance)
* The node with the lowest **f(n)** is explored first

The grid is represented as a graph where:

* Each cell is a node
* Movement is allowed in four directions (up, down, left, right)

---

## Controls

* **Left Click** → Set:

  * Start node (green)
  * End node (red)
  * Barriers (black)

* **Right Click** → Reset a node

* **SPACE** → Run A* algorithm

---

## Technologies Used

* Python
* Pygame

---

## Installation

```bash
pip install pygame
```

---

## Running the Project

```bash
python main.py
```

---

## Learning Outcomes

* Understanding of A* search algorithm
* Use of heuristic functions in AI
* Graph-based pathfinding concepts
* Event-driven programming with Pygame

---

## Author

Abbas Ahmed
