# Setting
1. Each [[Node]] only knows the cost to its neighbours
2. Each [[Node]] can only talk to its neighbours
3. All [[Node]] run the algorithm in parallel
4. [[Node]] may fail or messages get lost
# Algorithm
1. [[Flooding]] the network with a [[Link State Package (LSP)]]
2. Each [[Node]] computes its source tree using [[Dijkstra's Algorithm]] or similar

# Handling Changes
## Link Failure
The [[Node]] on both sides of the link notice and send updated [[Link State Package (LSP)]]
## Node Failure
All the neighbouring [[Node]] notice that the link fails and resend [[Link State Package (LSP)]]
## Adding Node
The new [[Node]] sends a [[Link State Package (LSP)]] and all [[Node]] recompute their source tree
# Complications
- Sequence number reaching mak
- Node crashes and leses the sequence number
- Network splits, evolves and then heals
# Strategy
- Add age to [[Link State Package (LSP)]]
# Examples
## [[Intermediate System To Intermediate System (IS-IS)]]
## [[Open Shortest Path First (OSPF)]]