---
aliases:
  - CSMA/CA
---

[[Carrier Sense Multiple Access with Collision Avoidance|CSMA/CA]] works on [[Local Area Network|LAN]].
Uses [[Stop-and-Wait Automatic Reapeat Request|Stop-and-Wait ARQ]].
Also known as Distributed Coordination Function.
Nodes that wish to send on the [[Transmission medium]] when it is busy get backlogged. Non-backlogged nodes can send after confirming that the medium is idle. Backlogged nodes must wait for a [[Distributed Coordination Function Interframe Space|DIFS]] and a random number of contention spaces ($20\mu s$). The random number being minimum 32 (default) and that is double each collision to a maximum of 5 times ($32 \cdot 2^{5}$). If busy during time slots wait another [[Distributed Coordination Function Interframe Space|DIFS]].

# Optional
[[Carrier Sense Multiple Access with Collision Avoidance|CSMA/CA]] optionally uses [[Request to send|RTS]] and [[Clear to Send|CTS]]. After receiving a [[Request to send|RTS]] the receiver has to wait a period of one [[Short Interframe Space|SIFS]] before sending a [[Clear to Send|CTS]] to allow the sender to switch to listening mode. [[Request to send|RTS]] and [[Clear to Send|CTS]] contains a time estimate that is used to update the [[Network Allocation Vetcor (NAV)]]. This can create a lot of overhead.