# A-Star-Algortihm-Python
Implementation of the A* path finding algorithm in Python
A* is a popular pathfinding agorithm. It can be used to find the shortest path between any two nodes in a (weighted) graph.
It is used extensively in RPG and RTS games and AI due to it's efficiency and optimality. Here I've implemented the A* algorithm for an M-by-N grid, since a grid
can be considered a special case of a graph. Movement is only allowed in 4 directions (UP, DOWN, LEFT, RIGHT aka Von Neumann Neighbourhood). You can also place 
obstacles and see for yourself that it always succeeds in finding the shortest path. A* is a pretty interesting algorithm with quite some effort put into
research... If you wanna learn about it, a good resource is [this](http://theory.stanford.edu/~amitp/GameProgramming/AStarComparison.html). I'd suggest learning
about Dijkstra's algorithm and best-first search before looking into A*, since A* derives from those (The link I gave mentions both).

# Controls
* use mouse to place obstacles
* Hold CTRL or SHIFT while clicking to set start/end cell
* Press R to randomize obstacles
* Press SPACE to clear all obstacles

# Dependencies
pygame

# Screenshots
![a](https://i.ibb.co/vQ4HYbX/Screenshot-5.png)
![b](https://i.ibb.co/p0rQC44/Screenshot-6.png)
