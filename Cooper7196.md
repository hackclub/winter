---
name: "@Cooper7196"
project: "Tangerine II"
---

# Tangerine II

## Summary

I am going to design and build a computer fully from scratch that is at least equivilent to to the Apple II. This will involve creating a custom architechture for the CPU and GPU. I then want to try to write an OS for it, potentially something like BASIC, as this will let it be used as an actual PC. I also want to try to develop some games / useful apps for it.

## Plan

First I will design the architechture and instruction for the assembly language this computer will be based on. Next I will start with the actual design of the CPU, first by outlining the components of it, then actually implementing in using Verilog. After that I will write a basic assembler so that I can write programs for it more easily. 

Then I'll synthesize it using the FPGA and begin debugging any issues with the CPU itself. Debugging the hardware will be done with an Analog Discovery 2, A tool I already have that will allow me to measure signals in and out of the processor using the probes I am buying.

After I'll design the GPU, which will allow me to display text and graphics in an easily accesible format, VGA.

I will then add support for some of the various peripherals such as the PS2 for mouse and keyboard, the ESP32 for internet access, and the microSD for external storage.

Finally, I'll begin writing more advanced software, such as an OS or games. I'll likely do this mostly in assembly, but I might try to create a compiler to allow for more high level code, either in a language of my own creation, or an established language such as C.

## Budget

| Product                | Supplier/Link                                                       | Cost               |
| ---------------------- | ------------------------------------------------------------------- | ------------------ |
| ARTY A7 FPGA           | https://digilent.com/shop/arty-a7-artix-7-fpga-development-board/   | $138.55            |
| Pmod PS2 Adapter       | https://digilent.com/shop/pmod-ps2-keyboard-mouse-connector/        | $7.64              |
| Pmod VGA Adapter       | https://digilent.com/shop/pmod-vga-video-graphics-array/            | $11.04             |
| Pmod Wireless Adapter  | https://digilent.com/shop/pmod-esp32-wireless-communication-module/ | $25.49             |
| Pmod MicroSD Adapter   | https://digilent.com/shop/pmod-microsd-microsd-card-slot/           | $5.94              |
| Analog Discovery 2     | https://bit.ly/AnalogDiscovery2                                     | $0 (already owned) |
| BNC Adapter            | https://digilent.com/shop/bnc-adapter-for-analog-discovery/         | $14.99             |
| BNC Probes             | https://digilent.com/shop/bnc-oscilloscope-x1-x10-probes-pair/      | $23.74             |
| BNC Minigrabber Probe  | https://digilent.com/shop/bnc-to-minigrabber-cable/                 | $7.99              |
| Minigrabber Test Clips | https://digilent.com/shop/mini-grabber-test-clips-with-leads/       | $7.99              |
| Shipping               | N/A                                                                 | $44.54             |
| Coupon Code (MOBILE15) | N/A                                                                 | -$36.51            |
| Total                  |                                                                     | $251.40            |
