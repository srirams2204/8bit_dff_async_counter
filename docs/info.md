<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project implements an 8-bit asynchronous binary counter using D flip-flops, where each flip-flop toggles based on the output of the previous stage, creating a ripple effect that counts upward from 0 to 255 in binary. Designed in Verilog and compatible with Tiny Tapeout, the counter showcases fundamental principles of sequential logic and asynchronous design. It operates without a shared clock across all stages, making it ideal for educational purposes and visual demonstrations in Wokwi, where each output bit can be mapped to LEDs or logic probes to observe the counting sequence in real time.

## How to test

Just give a continuous clock signal or manual clock signal from a push button to see the incrementing.

## External hardware

Can connect a LED to via the output.
