# Grid-Analysis-of-Pathfinding-Algorithms

Comparison of breadth first search (BFS), depth first serach (DFS), and dijkstra algorithms using a grid to find the optimal path from a start state to a goal state. The comparison is done on the basis of performance, time complexity, space complexity. Performace refers to the path cost and nodes explored by the algorithm to find a goal state. Different grids are generated with random obstacles to analyze the algorithms.

The initial and goal positions are generated randomly in the environment along with obstacles at the beginning of each mission. It is assumed that initial and final positions are known by the robot. So, the only difficulty for the robot is to compute the optimal path using the blind search algorithms.

Based on the analysis, it can be concluded that:
- Dijkstra can be used to find the shortest path in the grid as its path
cost is minimum.
- DFS performs with best space and time complexity but its path cost
is very high as compared to BFS and Dijkstra.
