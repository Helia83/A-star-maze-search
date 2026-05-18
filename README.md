# A-star-maze-search
This project implements the A* (A-Star) Search Algorithm in Python to help a chick navigate through a maze and reach its mother with the minimum possible cost.
The environment contains:

* Walls (blocked paths)
* Bridges with higher traversal cost
* Rivers with additional traversal cost

The algorithm uses:

* Path cost g(n)
* Manhattan heuristic h(n)
* Evaluation function f(n) = g(n) + h(n)

to determine the optimal path.

# Features

* A* Search Algorithm implementation
* Manhattan Distance heuristic
* Recursive maze traversal
* Backtracking for dead-end handling
* Cost calculation for bridges and rivers
* Node visitation tracking
* Fixed movement priority:

  * Left
  * Down
  * Right
  * Up
    
# Maze Description

The maze is represented as a 5x5 grid.

Special paths include:

* Walls → blocked movement
* Bridges → additional traversal cost
* Rivers → additional traversal cost

The chick starts from:
(0, 0)


and tries to reach:
(0, 3)

# Heuristic Function

The heuristic used is Manhattan Distance:
h(n)=|x_1-x_2|+|y_1-y_2|

The evaluation function for A*:
f(n)=g(n)+h(n)

Where:

* g(n) = total path cost
* h(n) = estimated distance to goal

## Advantages of A*

* Finds optimal path efficiently
* Uses heuristic guidance
* Faster than uninformed search algorithms
* Reduces unnecessary exploration
* Combines advantages of UCS and Greedy Search


## Technologies Used

* Python
* A* Search Algorithm
* Artificial Intelligence Concepts

## Author

Implemented by Helia for Artificial Intelligence course project.
