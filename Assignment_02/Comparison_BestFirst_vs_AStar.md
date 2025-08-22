# Best-First Search vs A*

## Best-First Search (Greedy)
Best-First Search chooses the node that looks closest to the goal using only the heuristic.  
It usually finds a path quickly but may not always give the shortest one since it ignores the cost already covered.  
For example, in a grid it may rush toward the target but end up taking a longer route.

## A* Search
A* considers both the distance already traveled and the estimated distance left to reach the goal.  
This makes it explore more nodes and take extra time, but it guarantees the shortest possible path.  

**In short:**  
- Best-First is faster but less reliable.  
- A* is slower but always accurate.  
