---
name: "@acornitum"
project: "mini keyboard"
---

# Mini Keyboard

## Summary

I want to build a mini-keyboard. It will have programmable keys. 

My plan is two build two of different sizes. The first would be a 4-key keyboard, where I mostly follow instructions for wiring and hardware. The second is a 40% key keyboard, in which I'll be designing the base case around the keyboard in Tinkercad, designing the frame in CAD, then 3D printing it and lazercutting it out. 

My hope is that I would be able to program them to do various shortcuts in apps - for example, in Davinci Resolve (an editing software), I would be able to press a single button on that keyboard to do something that would normally require multiple button presses. This would save time by a lot, and would just overall be really convenient. My plan is to then build multiple of these, since they are small, and I would be able to program each one differently so that I could just plug in whichever one I need most at any given time. Hopefully, after built, it would also resemble and function sort of like a Stream Deck, which is a device used by streamers to quickly be able to switch between different screens, etc, on the fly, with a simple press of a key instead of needing to click around multiple steps.

I'll still be able to use the 40% as a normal keyboard, however I would also like to program shortcuts into it. 

I'm excited to build it because this is the first time I'm working with a lot of hardware - first time doing anything related to wires, switches, boards, etc. I currently know very little about this all, and am very excited to learn. I'm also very excited to code up the software portion of the project, and to see how far I can take that. I also have very little experience with this - although I like to think I'm decent at competitive programming, I don't know much about programming this stuff. 

Here is the project it is based on: https://learn.adafruit.com/pico-four-key-macropad


## Plan

What steps are you going to take to build it? What tools are you going to use? What will you do first, second, third, etc.?

I'm going to loosely follow these instructions for the hardware part of the project: https://learn.adafruit.com/pico-four-key-macropad/build-the-keypad
More things I'll be loosely following in attempt to handwire everything: 
https://docs.google.com/document/d/1Eqvy9FG-OiuZov82HrgYj6GCGPKYLzweQbluhq92vxI/edit
https://geekhack.org/index.php?topic=87689.0
https://www.crackedthecode.co/a-complete-guide-to-building-a-hand-wired-keyboard/#row-wire-installation

Here's a brief layout of what I'll be doing:

Firstly, I'll be designing the case in Tinkercad, and 3D printing it out. I'll also be designing a frame in CAD, and lazercutting that out. 

Then, I'll connect the switches with the microcontroller. After everything has been lined up, I will solder them together. 

Then, I'll put the switches into the board, and screw in all of that together. These two steps are probably going to take a while, since I have practically no experience with hardware. 

After all the hardware has been done, I'll code the keys do certain tasks when pressed. 

## Budget

Since I don't really own any hardware, I'll need to buy almost all of parts needed. 

Materials are from Keeb.io, Amazon, and Home Depot. For the 3D printing, I'm eyeing a couple of local 3D printing shops around me. They charge per gram of material printed, and since I can't determine the exact price before I print it out, I'm making a rough estimate there. 

| Product                                | Supplier/Link                         | Cost        |
| ---------------------------------------| ------------------------------------- | ----------- |
| Elite-C V4 microcontroller             | https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4?variant=32023682646110 | $17.99       |
| Elite-Pi microcontroller               | https://keeb.io/products/elite-pi-usb-c-pro-micro-replacement-rp2040?variant=39669504507998 | $12.99   |
| 3D printing/lazercutting services      | [probably will be printing at a local store] | ~$30.00      |
| Durock Shrimp Switches                 | https://keeb.io/products/durock-shrimp-silent-tactile-t1-switches?variant=39846263193694 | $39.99       |
| Keycaps                                | https://www.amazon.ca/gp/product/B09XF1W9Z5/ref=ox_sc_act_title_2?smid=A3JGTQ06HRVA6E&th=1 | $36.57       |
| Coiled USB-C to USB-C Cable            | https://keeb.io/products/coiled-usb-c-to-usb-c-cable?variant=39828807680094 | $3.99       |
| 1N4148 Diodes                          | https://keeb.io/products/1n4148-diodes?variant=42525667334 | $2.99       |
| 18 awg Solid Wire                      | https://www.amazon.ca/gp/product/B086WDKXXX/ref=ox_sc_act_title_1?smid=A2FBSO766XM36V&th=1 | $17.91      |
| Soldering Iron                         | https://www.homedepot.ca/product/weller-30w-solder-iron-kit-led-halo-ring/1001649526 | $24.66       |
| Solder Wire                            | https://www.homedepot.ca/product/aim-solder-dura-pure-96-4-1oz-solder-wire-coil/1001659546 | $8.96       |
| Shipping                               | [all the sites combined]              | $25.00      |
| Sales Tax                              | [all the sites combined]              | $28.60      |
| Total                                  |                                       | $248.60     |
