---
aliases:
  - CSMA/CD
---

[[Carrier Sense Multiple Access|CSMA]] but add sensing while sending. If detecting a collision, back off and wait a random time before sensing the [[Transmission medium]] again. At repeated collisions, double the wait time. This is not suitable for [[Radio wave]] signals due to the high [[Attenuation]]. It also does not work with hidden terminals. This does not reduce the risk of collisions but reduces the time cost.