The transmission capacity is the number of [[bits]] that can be sent through a [[Transmission medium]] each second.

# Calculation
## General
The transmission capacity can be calculated using:
$$
C=R \log_{2} L
$$
or
$$
C = 10 \cdot \log_{10} \left( \frac{P_{in}}{P_{out}} \right)
$$
Where $C$ is the capacity, $R$ is the [[Baud rate]], and $L$ is the number of levels or [[bits]] per signal

## Nyquist bit rate
The Nyquist bit rate is calculated using:
$$
C_{max} = 2B \log_{2} L
$$
## Shannon's formula
It is used to calculate the highest /possible bitrate in a channel with [[white noise]]
$$
C = B \log_{2} \left( 1+S/N \right)
$$

$S/N$ is the ratio between the signal and the noise
It is calculated with division when mesured in [[Watts]] and subtraction when messured in [[decibel]]
# Limitations
The transmission capasity is limited by:
- [[Attenuation]]
- [[Power]]
- [[Distortion]]
- [[Noise]]
# Countermeasures
Possible countermessures are:
- [[Amplification]]
- [[Regeneration]]
- [[Noise filters]]