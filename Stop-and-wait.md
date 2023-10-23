The stop and wait protocol involves the sender sending one [[Frame]], then waiting for an [[Acknowledgement (ACK)]] before sending the next one.

# Utilisation

## Transition time
Time between first and last bit of message
$$T_{tr} = \frac{b}{\frac{b}{s}} = \frac{length}{capacity}$$

## Propagation time
Time a bit to go from one end of the [[Transmission medium]] to the other
$$T_{pr} = \frac{m}{m/s} = s$$
## Total time
The time it takes before the sender can send again

## General
$$
U = \frac{T_{tr}}{T_{tot}} = \frac{T_{tr}}{T_{tr} + T^{F}_{pr} + T^{A}_{pr}}
$$
The desired is $U \geq 1$

## Symmetrical
$$
T^{F}_{pr} = T^{A}_{pr} = T_{pr}
$$
$$
a = \frac{T_{pr}}{T_{tr}}
$$
$a < 1$ less than 1 frame at a time in the [[Transmission medium]] $a \geq 1$ more than 1 frame at a time
$$
U = \frac{T_{tr}}{T_{tr} + T^{F}_{pr} + T^{A}_{pr}} = \frac{T_{tr}}{T_{tr} + 2T_{pr}} = \frac{1}{1 + 2a}
$$