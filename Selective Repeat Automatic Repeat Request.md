---
aliases:
  - SREJ
  - Selective Repeat ARQ
---
[[Selective Repeat Automatic Repeat Request|SREJ]] is an extension of [[Go-back-N Automatic Reapeat Request|Go-back-N ARQ]] but the receiver sends a negative acknowledgement for lost or dropped frames. This requires the receiver to sort frames that has come out of order. The usable window size is $2^{k-1}$ where k is the number of bits in the sequence number.