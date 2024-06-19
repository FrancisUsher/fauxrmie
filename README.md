# fauxrmie

A derivative of the [2040rmie](https://github.com/shinkaimayano/2040rmie) drop-in PCB for the [40rmie](https://p3dstore.com/products/40rmie-invisibolt-acrylic-keyboard-case-and-pcb) family of keyboards using 40s modifiers.

The original [40s-2040rmie](https://github.com/shinkaimayano/40s-2040rmie) USB
port and rotary encoder position were slightly off. This probably didn't matter
for the acrylic or 3d printed cases, but for the 40rmie LX the tolerances seem
to have gotten a bit tighter, so I adjusted them to the correct position.

Additionally I simplified the layout options to only use the ones I am
interested in. It should be pretty straightforward to add additional e.g.
bottom-row layouts though.

## Status: Limited testing

I have tested this in my 40rmie LX using the no-blockers, no-encoders layout.

There should be no problems using the other layouts as I put quite a bit of
effort into checking the component positions matched the original PCB. However
_Order at your own risk!_

## Production

Dimensions: 309.5625mm x 112.0325mm

The files in `jlcpcb` should contain everything you need to need to order PCBA
from JLCPCB as of their January 2024 component selection.

The cost of production for 5 units was roughly $20 per unit with a 5 day turnaround:

- `$17` for PCB production (1 day)
- `$35.91` for components + PCB assembly (2 days)
- `$50` for DHL Express delivery (2 days)

## Renders

![Front](/Images/front.png)  
![Back](/Images/back.png)
