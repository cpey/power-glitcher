# Power Glitcher

Power glitcher circuit for voltage fault injection. Similar to [1], it includes
a DAC, a non-inverting amplification stage, and a push-pull follower output
circuit.

The board can function as ON/OFF switch, bypassing the DAC, by connecting a GPIO
output to the J5 connector and short-circuiting JP1. Refer to the
[schematic](https://github.com/cpey/power-glitcher/blob/main/power_glitcher/power_glitcher.pdf)
for more details.

![Rendered 3D view of the Power Glitcher.](https://github.com/cpey/power-glitcher/blob/main/power_glitcher/power_glitcher_3d.jpg)


[1] D. Oswald, *A Versatile Framework for Implementation Attacks on Cryptographic RFIDs and Embedded Devices*, 2010.
