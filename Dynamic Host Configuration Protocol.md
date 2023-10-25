---
aliases:
  - DHCP
---

A [[Dynamic Host Configuration Protocol|DHCP]] server is used to lease [[IP address]] to [[host]] on a [[Local Area Network|LAN]]. [[Dynamic Host Configuration Protocol|DHCP]] is an [[Application Layer]] protocol sitting on top of [[User Datagram Protocol (UDP)]] on [[Port]] 67 or 68.
# Protocol
## Bootstrap issue
There is the issue of how a computer is supposed to contact the [[Dynamic Host Configuration Protocol|DHCP]] server before it knows its own [[IP address]] or the servers. This is solved by using [[Broadcast]] address both for [[Internet Protocol|IP]] and [[Medium Access Control|MAC]].
## Discover (DHCPDISCOVER)
The client sends a message on the limited broadcast address (255.255.255.255) or on the specific subnet broadcast (directed broadcast). In the DHCPDISCOVER the [[Client]] may request an [[IP address]].
## Offer (DHCPOFFER)
In response to a DHCPDISCOVER the server will reserve an [[IP address]] and send a message offering the [[IP address]], as well as giving some other information such as , the networks [[Subnet Mask]], the lease duration, and the [[IP address]] of the [[Dynamic Host Configuration Protocol|DHCP]] server.
## Request (DHCPREQUEST)
Before the [[Client]] accepts the [[IP address]] the client will use [[Address Resolution Protocol|ARP]] to confirm that no one else is using this address. The [[Client]] may receive offers from several [[Dynamic Host Configuration Protocol|DHCP]] servers, but will only accept one.
## Acknowledgement (DHCPACK)
The server responds with a DHCPACK including the lease duration and any other configuration information that has been requested.

# Sources
[Wikipedia](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol)