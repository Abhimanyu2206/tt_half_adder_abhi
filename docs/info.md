<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This design implements a 1-bit half adder using two logic gates:
- XOR gate generates the SUM output
- AND gate generates the CARRY output

Inputs:
- ui[0] → A
- ui[1] → B

Outputs:
- uo[0] → SUM (A XOR B)
- uo[1] → CARRY (A AND B)

## How to test

Check with the following inputs:
1. A=0, B=0, then sum=0, carry=0
2. A=1, B=0, then sum=1, carry=0
3. A=0, B=1, then sum=1, carry=0
4. A=1, B=1, then sum=0, carry=1

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
