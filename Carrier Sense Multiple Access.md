---
aliases:
  - CSMA
---

CSMA is based on the idea of listening to the [[Transmission medium]] and only sending when the medium is idle. This reduces the amount of collision not eliminating them completely. It also assumes that all nodes hear every other node. Works on wired networks or small scale radio communication. Busy medium synchronizes transmissions. Should always use non-persistence strategy.

# Persistence strategy
Sending immediately when the [[Transmission medium]] is idle

# Non-persistence strategy
Wait a random time between sensing the [[Transmission medium]]. This may avoid some collisions, but makes the link less effective, as well as introducing the possibility of capture. Capture being that one node has a shorter wait time and blocking other nodes from sending.

# Variants
- [[Carrier Sense Multiple Access with Collision Detection|CSMA/CD]]
- [[Carrier Sense Multiple Access with Collision Avoidance|CSMA/CA]]