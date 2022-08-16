# A* PathFinder Visualizer ![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)


![python License](https://img.shields.io/badge/MADE%20WITH-Pygames-green.svg)

<p align="center">
  <a href="https://github.com/arevish/A-Pathfinding-Visualizer" rel="noopener">
    
  ![Pathfinding visualizer](https://user-images.githubusercontent.com/91308138/184955087-b58ebf71-53dd-44e2-9ba6-e2fc61eba300.png)

  </a>
</p>

Built pathfinding visualizer in Python using pygame. Using A star algorithm to find the shortest-path and Generate the grid using maze-generation algorithm and add the ability of controlling the grid structure and the distribution of the blocks and the position of the source and the destination.

This astar pathfinding algorithm is an informed search algorithm which means it is much more efficient that your standard algorithms like breadth first search or depth first search

## ⚙ How it Works

1. Users can select the start and end node and set them in any place on the grid by clicking left mouse button.
2. Users can optionally choose to clear the nodes or draw walls by dragging the right mouse button and left mouse button respectively.
3. Users can optionally randomize the walls in the maze and add more walls by dragging the mouse.
4. user can clear and reset the grid by just pressing the ` C ` key.
5. Finally to start the path visualization algorithm  press `SPACEBAR`, sit back and watch the vizualization algorithm run.

# Algorithms
- A* is a graph traversal and path search algorithm, which is often used in computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its O(bd) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, as well as memory-bounded approaches; however, A* is still the best solution in many cases.
 
### DEMO - 
![pathvizudemo](https://user-images.githubusercontent.com/91308138/184954955-f242b75c-d761-4d91-805a-d42803decea0.gif)

PLEASE FEEL FREE TO FORK THE PROJECT AND START CONTRIBUTING. :)

### Module used
python modules
```
import pygame
```

## PRE-REQUISITES
Your laptop with python 3.6.x (onwards) installed.

**NOTE:** Those with Linux and MacOSX would have Python installed by default, no action required.

Windows: Download the version for your laptop via https://www.python.org/downloads/

**NOTES**
In your preferred editor, make sure indentation is set to "4 spaces".

* Make sure you have **pygame** installed in python otherwise code may fail, to install pygame in your machine > open python in your terminal then type `pip install pygame` to install. :warning:

---

## Run using Python3.8+
1. Clone or download repositiory: https://github.com/arevish/A-PathFinding-Visualizer.git
2. In source folder, run `python3 'main.py'` to start program, optionally, run with `--help` argument to see other runtime options.
 
### ThankYou!
<img src ="https://user-images.githubusercontent.com/91308138/184955004-fbbb507e-7c97-46a8-bea6-17f133a8514e.png" width="100" height="100">

