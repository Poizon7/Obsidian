---
aliases:
  - Go-back-N ARQ
---

[[Go-back-N Automatic Reapeat Request|Go-back-N ARQ]] is an extension of [[Sliding window]] with the [[Acknowledgement|ACK]] acknowledging all frames before the one it requests. If it times out, it resends all frames not acknowledged. The window size can be $2^{k} - 1$ where k is the number of bits in the sequence number. It is a continues [[Automatic Repeat Request|ARQ]] (no errors the link has full utilisation).