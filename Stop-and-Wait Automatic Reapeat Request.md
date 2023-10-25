---
aliases:
  - Stop-and-Wait ARQ
---

Stop and wait ARQ is an extension on the [[Stop-and-wait]] protocol, but the sender saves the last frame and only discards it when it has received an [[Acknowledgement|ACK]] requesting the next frame. The timer is started when the frame is sent. Can send an receiver not ready.