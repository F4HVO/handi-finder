# handi-finder
F4HVO implementation of Handi Finder.

This circuit was made in a hurry but fortunately it works.

![Board](/images/front.png)

## How to make it

- Send the gerber files to your favorite PCB factory (OSH Park, Elecrow, AllPCB, ...).
- Get the components (see BOM below)
- Assemble (hot air station or reflow oven recommended, but a frying pan and sand can do the trick)
- Then add antennas : rigid wire of 48cm on each side, between ANT1 and ANT1GND (and ANT2-ANT2GND respectively). Make a bow shape by bending the wire to form 3 edges (two of 17cm and one of 12cm).
- Have fun.


## BOM
All capacitors and resistors are 0805.

- U1 : CD4047 (smd version)
- C1 : 0.2 uF
- C2, C3, C4, C5, C6, C7 : 1nF
- C8 : 0.1 uF
- R1, R2, R3 : 10k
- D1, D2 : 1n4148 (or any switching diode, or PIN diode)
- Switch : good luck, or no switch
- SMA connector
- 9V battery (and connector)


## Remarks

- The package for the diodes (SOD-323) might not be the more standard. Bigger diodes can still be soldered to the board. Just take some silk mask off or modify the eagle board :).
- The switch package is also unfamiliar, a more standard one might be better. I did not use a switch, I soldered a jumper on my assembled board.
