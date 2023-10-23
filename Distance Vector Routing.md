Distance Vector Routing is a distributed version of the [[Bellman-Ford Algorithm]].
# Setting
1. Each [[Node]] only knows the cost to its neighbours
2. Each [[Node]] can only talk to its neighbours
3. All [[Node]] run the algorithm in parallel
4. [[Node]] may fail or messages get lost
# Initialisation
Set the source to 0 and all others to $\infty$ (they are called "Tentative").
# Algorithm
1. Periodically send vectors to neighbours
2. Update your own vectors based on the vectors you have recived plus the cost of that link
3. Use the best one for forwarding
# Examples
## [[Routing Information Protocol (RIP)]]