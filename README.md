# Robot Navigation — BFS vs DFS Pathfinding Visualizer

## Overview

This project is an interactive web-based visualization tool designed to demonstrate the working of fundamental pathfinding algorithms—**Breadth-First Search (BFS)** and **Depth-First Search (DFS)**—in a grid environment.

It enables users to simulate real-time navigation by placing obstacles, adjusting start and target nodes, and observing how each algorithm explores the search space and determines a path.

---

## Objectives

* To understand and visualize classical search algorithms used in Artificial Intelligence
* To compare the behavior and performance of BFS and DFS
* To provide an intuitive interface for experimenting with grid-based pathfinding problems

---

## Features

* Interactive grid for environment simulation
* Dynamic wall (obstacle) creation and removal
* Adjustable start and target positions
* Execution of BFS and DFS algorithms
* Real-time visualization of:

  * Nodes explored
  * Path discovered
  * Algorithm used
* Clean and responsive user interface

---

## Algorithms Implemented

### Breadth-First Search (BFS)

Breadth-First Search explores nodes level by level and guarantees the shortest path in an unweighted grid. It utilizes a queue-based approach (FIFO).

### Depth-First Search (DFS)

Depth-First Search explores nodes by going as deep as possible before backtracking. It uses a stack-based approach (LIFO) and does not guarantee the shortest path.

---

## Technology Stack

* HTML
* CSS
* JavaScript (Vanilla JS for algorithm implementation and DOM manipulation)

---

## Project Structure

```id="qgqvyy"
project/
│── robot-navigation.html
```

---

## Execution Instructions

1. Clone the repository:

```bash id="4jdl0h"
git clone https://github.com/your-username/your-repository-name.git
```

2. Navigate to the project folder and open the file:

```id="1yz0cw"
robot-navigation.html
```

3. Run the application in a web browser.

---

## Usage

* Use the **Draw Walls** mode to create obstacles
* Use **Move Start** and **Move Target** to reposition nodes
* Click on **BFS** or **DFS** to run the respective algorithm
* Use **Clear** to reset the grid

---

## Learning Outcomes

* Practical understanding of uninformed search algorithms
* Visualization of algorithmic traversal strategies
* Insight into efficiency and path optimality differences between BFS and DFS

---

## Future Enhancements

* Implementation of A* Search Algorithm
* Support for weighted graphs
* Adjustable visualization speed
* Improved mobile responsiveness

---

## Conclusion

This project provides a practical and visual approach to understanding fundamental pathfinding algorithms. It bridges theoretical concepts from Artificial Intelligence with an interactive implementation, making it useful for both learning and demonstration purposes.

---

## Author

Arpita Hanwatkar

---
