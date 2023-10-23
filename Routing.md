# Requirements
## Universal
Every destination should be reachable.
## Correct
The rout should lead to the destination.
## Optimal
It should use the network resources efficiently.
## Simple
It should be able to run on each switch and have a fast convergence.
## Robust
It should be able to handle changes in topology.
## Stable
It should not oscillate between different paths.
## Fair
It should not lock out [[Packet]] or destinations
# Strategies
- Fewest links
- Highest capacity
- Lowest end-to-end delay
- Administrator policies
# Routing with Multiple Parties
[[Internet Service Provider (ISP)]], [[Content Delivery Network]], and other parties are richly interconnected often through [[Internet Exchange Points (IXP)]].
## Problems
### Scaling
- IP prefixes
- [[Hierarchical Routing]]
- [[Prefix Aggregation]]
### Incorporating Policy Decisions
# Routing Policies
A routing policy can be anything, for instance Internet2 only sends non-commercial data.
## Transit
This is usualy given to customers. It involves the [[Internet Service Provider (ISP)]] sending the customers data to the rest of the internet. The customer pays for this service.
## Peer
A service between [[Internet Service Provider (ISP)]]. Transmits data from another [[Internet Service Provider (ISP)]] to its customer. This is done without payment.
# Calculation
## [[Dijkstra's Algorithm]]
## [[Distance Vector Routing]]
## [[Flooding]]
## [[Link-State Routing]]
## [[Hierarchical Routing]]
## [[Border Gateway Protocol (BGP)]]
