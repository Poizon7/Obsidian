Data transparency is making sure that the entire frame and only the frame is received. This is done using flags (0x7E) in the [[Frame]]. A problem that can occur is that the flap appears in the data.
# Solutions
## Character stuffing ([[Byte-Oriented Protocol]])
Adding an escape character (0x7D) before non valid flags, these are removed before the data is sent to a higher layer. The escape character must also be placed before escape characters in the data to prevent the resver from ignoring whats after.
## Bit stuffing ([[Bit-Oriented Protocol]])
Adding a 0 after every occurence of 5 concecutive 1s, due to flag 01111110