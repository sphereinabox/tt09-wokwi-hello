<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

I've built 8-input logic gates, all using each of the 8 inputs....

- OUT0 is 8-bit and of IN0..7
- OUT1 is 8-bit nand of IN0..7
- OUT2 is 8-bit or of IN0..7
- OUT3 is 8-bit nor of IN0..7
- OUT4 is 8-bit xor if IN0..7
- OUT5 is MUX(sel=IN0, A=IN1, B+IN2)
- OUT6,OUT7 driven by D-flip-flop: DFF(D<=IN0,CLK<=CLK, Q=>OUT6,QNOT=>OUT7)

## How to test

Set the inputs 0..7 to your desired 8 inputs.

Observe the outputs the corresponding output pins.

## External hardware

No specific external hardware is expected for this project.
