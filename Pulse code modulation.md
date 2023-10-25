Pulse code modulation is the process of converting from an [[Analogue Signal|analog]] to a [[Digital Signal|digital]] signal.
# Sampling
Sampling is the process of converting the continuous [[Analogue Signal]] to a signal that is discrete in time.
The sampling rate is decided using Nyquist's theorem
$$
f_{s} \geq 2 \cdot f_{max}
$$
No more information is gained by sampling at a higher rate.
## Quantisation
Quantisation is the process of constraining the continuous [[amplitude]] to a set of finite [[amplitude|amplitudes]].
This is done by rounding to the nearest amplitude level (decided upon by the [[Line coding]]). This process is non-reversible.

$$
f \left[ \frac{1}{s} \right] \cdot quanta [b] = bitrate \left[ \frac{b}{s} \right]
$$