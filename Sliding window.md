Sliding window is an improvement on [[Stop-and-wait]] 
It involves sending N [[Frame]] before stopping
[[Acknowledgement (ACK)]] acknowledge all [[Frame]] received before it is sent
When [[Frame]] are acknowledged the window moves forward

# Utilisation
$$
U = \frac{N \cdot T_{tr}}{T_{tr} + 2T_{pr}} = \frac{N}{1 + 2a}
$$

$U \geq 1$ results in full use of the [[data link]]
$U < 1$ the protocol becomes the limiting factor
$N = 1$ it becomes [[Stop-and-wait]]
$N \propto a$
Bigger networks require larger N