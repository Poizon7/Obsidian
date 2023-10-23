# 1
## a
$$S/N_{new} = 10 \cdot $$
# b
True becaus sampling frequency is dubble max frequency and human audible is 20kHz
## c
False, all types of transmisson need synced clocks to determain that the bits are decoded corectly
## d
False it has 5 bits
## e
False, quantization means rounding the amplitude to predetermed levels, this results in information loss.
## f
True, there needs to be some sort of multiplexing to avoid the two senders from interfereing with eachother.
## g
False, only 7 numbers can be used in a single window but all 8 numbers are used.
## h
True, this reduces the risk of desynchronisation of the clockes due to long streatches of the same bit
# 2
Attenuation is the loss of power in the signal as it propagates through the medium. Distortion is drifting out of sync of different frequencies. Noise is the addition of unwanted frequencies to the medium.

The radion link is most suseptible to all types of transmission imparmets. Next in sesativity is the UTP cable, and last the optical fibre.
Optical no distorsion
# 3
I would try and emulate IEEE 802.3a (Fast Ethernet). Using a shielded twisted pair wire (to protect agains the noise from the building) using CSMA CD. 

# 4
When the link is busy, all the senders will continusly listen and when the medium becomes idle they will all try to send at the same time. They will all send their entinre frame and then wait for an ACK. When they do not get one, they will conclude that there has been a collison. They will all pick a random wait time and then try to re-transmit. This process will continue untill all the senders have gotten their frames accros.
# 5
## a
There are 4 addresses in the frame. Sending a frame between to stations in a BSS in infrastructure mode.
## b
Stop and wait ARQ
## c
If the node is not backlogged it seses the network for a DIFS if idle it sends its frame and then waits for an ACK.
## d
If the node is backlogged, it waits for a DIFS and a randam number of time slots up to a maximum of 31 (default). The time slots are only decreased when the medium is idle. When the time slots are all waited out the node sends its frame.
# e
RTS (Right to send) and CTS (Clear to send) are frames sent to coordinate transmissions between stations. They do this by garanteeing that all nodes that could send at that time know that the medium is going to be busy, they know this when they hear either the RTS or CTS.

NAV (network alocation vector) is a number that says for how long the network is going to be busy. The value is updated from the timing information in the RTS and the CTS.
## f
$$U = 1 - p$$
# g
$$U = 1 - Np$$
