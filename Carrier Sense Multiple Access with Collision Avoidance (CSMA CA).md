CSMA/CA works on [[Local Area Network (LAN)]]
Uses [[Stop-and-wait ARQ]]
Also known as Distributed Coordination Function
Nodes that wish to send on the [[Transmission medium]] when it is busy get backlogged. Non-backlogged nodes can send after confirming that the medium is idle. Backlogged nodes must wait for a [[Distributed coordination function IFS (DIFS)]] and a random number of contention spaces ($20\mu s$). The random number being minimum 32 (default) and that is double each colision to a maximum of 5 times ($32 \cdot 2^{5}$). If busy during time slots wait another [[Distributed coordination function IFS (DIFS)]] 

# Optional
CSMA CA optionally uses [[Request to send (RTS)]] and [[Clear to send (CTS)]]. After reciving a [[Request to send (RTS)]] the reciver has to wait a period of one [[Short IFS (SIFS)]] before sending a [[Clear to send (CTS)]] to allow the sender to switch to listening mode. [[Request to send (RTS)]] and [[Clear to send (CTS)]] contians a time estimet that is used to update the [[Network Allocation Vetcor (NAV)]]. This can create a lot of overhead.