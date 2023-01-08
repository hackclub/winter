---
name: "@BHTY"
project: "SuperNova"
---

# SuperNova 32-bit RISC Microprocessor

## Summary

I am building a 32-bit RISC microprocessor based on existing designs such as MIPS, RISC-V, and the Hitachi SuperH series. It will execute binary code that has been written for it using my toolchain, which is to include a macro assembler, software simulator, linker, and C compiler.

I am excited to build this because while I have extensive experience programming microprocessors in C and assembly language, I have never actually built a processor, but believe that I have sufficient knowledge of digital logic to accomplish this.

The CPU's logic design will be programmed onto an FPGA, which will also include a small set of peripherals including 1-bit audio output, VGA, and keyboard input, to allow it to run software.

## Plan

To build the CPU, I will need to construct each of the different components, starting with the ALU (Arithmetic-Logic Unit), and then building the parts of the CPU that decode and execute instructions, and finally adding on the peripheral devices.

The main tool at my disposal is Verilog, which allows me to describe the layout of the hardware, and eventually program it onto an FPGA.

Some progress has already been made on the processor's ALU using Verilog simulations, including:
* 32x32=64-bit Multiplier
* 64/32=32-bit Divider
* 32-bit Barrel Shifter
* 32-bit Equality Comparison Unit
* 32-bit Full Adder

Additionally, I have already completed a preliminary (though incomplete and subject to change) reference document outlining the instruction set that will be implemented on the SuperNova CPU.

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product           | Supplier/Link                                                     | Cost     |
| ----------------- | ----------------------------------------------------------------- | -------- |
| Arty A7-35T FPGA^ | https://digilent.com/shop/arty-a7-artix-7-fpga-development-board/ | $163.00  |
| PMOD PS/2 adapter | https://digilent.com/shop/pmod-ps2-keyboard-mouse-connector/      | $8.99    |
| PMOD VGA adapter  | https://digilent.com/shop/pmod-vga-video-graphics-array/          | $12.99   |
| Female 3.5mm to bare pins | https://www.amazon.com/Fancasee-Replacement-Female-Connector-Repair/dp/B07Y8KR21P | $8.99 |
| Total             |                                                                   | $193.97   |

^The base list price for this item is $159.00, but I configured it with the included USB A to Micro-B cable, which increases the price slightly to $163.00
