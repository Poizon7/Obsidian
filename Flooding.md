Flooding is a way of [[Broadcast]] on a network using a distributed algorithm.
# Rules
- Send [[Packet]] that is to be flooded to all other neighbours
- Remember the [[Packet]] so that it is not re-flooded

# Notes
The algorithm is inefficient because a [[Node]] can receive the same [[Packet]] from several senders
Sequence numbers can be used to remember [[Packet]]
For reliability use [[Automatic Repeat Request|ARQ]]