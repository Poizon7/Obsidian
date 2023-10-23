Dijkstra's algorithm is a [[Single Shortest Path Algorithm]] which finds the least cost path from one [[Node]] to all others. For the algorithm to work there can be no non-positive costs.
# Initialisation
Set the source to 0 and all others to $\infty$ (they are called "Tentative").
# Algorithm
While there are tentative nodes:
1. Add a link to the node with the lowest cost to the tree
2. Reduce the cost of the once adjacent to it
3. Repeat
# Result
Dijkstra's algorithm finds the least cost path in increasing distance from the source.
The calculation time is superlinear (grows quickly in proportion to the size of the network)
It gives the complete source/sink tree which is more than what is needed.
It also requires knowledge of the complete topology.