# AI Maze Solver (DFS & BFS)

A Python-based AI search agent that solves text mazes using Depth First Search (DFS) and Breadth First Search (BFS).  
Inspired by concepts from the CS50 AI WITH PYTHON course.

---

## Features
- Maze parsing into a 2D state-space representation
- Custom Node class (state, parent, action)
- Stack frontier for DFS
- Queue frontier for BFS
- Explored set to prevent revisits
- Path reconstruction using parent pointers
- Terminal visualization of solution

---

## Maze Format
#→ wall
space → path
A → start
B → goal


Example:

  #####B#
  ##    #
  ## ## #
  ## ## #
  #     #
  #A#####

---

## How It Works
1. Maze file is converted into a boolean wall grid  
2. Graph search explores nodes using a frontier and explored set  
3. Goal detection triggers parent-pointer path reconstruction  
4. Solution stored as:

self.solution = (actions, cells)


---

## Run

python search.py maze.txt


---

## Concepts Demonstrated
- Graph search
- DFS vs BFS
- State representation
- Frontier management
- Cycle avoidance
- Parent-pointer path reconstruction

---

## Future Improvements
- A* search
- Weighted mazes
- GUI visualization
- Performance comparison (DFS vs BFS vs A*)

---

## Author
Tanmay Jagtap  
Student exploring Artificial Intelligence through hands-on projects.
