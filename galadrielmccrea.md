---
name: "@galadrielmccrea"
project: "Graphing Calculator of Doom"
---

# Graphing Calculator of Doom
## Summary

Face it, most graphing calculator are quite boring. They are these massive contraptions that lack any true modern programability,
with none really pushing past a couple of hundred megahertz in a single 32-bit core or so, using stripped down languages
such as TI-Basic. That's a little hard to do stuff on.


I personally love the graphing calculator format, it looks cool and retro while still being utilizable. Why?
* Nice large physical buttons (those are hard to find these days in a device)
* Convenient form factor (fits in a pocket, but isn't too big to be a pain to use)
* Super easy to use. Everything has a button, you aren't hunting in menus.

***
What am I doing? Putting the fun back into graphing calculators. I'm going to stuff an Nvidia Tegra SoC into a graphing calculator, including a few extras.
* Google Coral Dual TPU ML Accelerator
* Camera
* Wi-Fi+bluetooth
* NOAA Weather Satellite communication stack

Is this a bad idea? Probably. Can I pull it off? I hope so. Here's my qualifications
* I've made PCB's in the past, and utilized chipsets such as the ESP32, ATMEGA328, and the RP2040
* I'm proficient in a bunch of programming languages (Python, C, JS, the normal suspects), and I have worked with a ton of stuff in the past, even nitty-gritty
  stuff like verilog (Ok, that's not technically a programming language, but close enough)
* I've done plenty of hardware projects in the past, including recently a smart barbecue grill controller (it was for my dad, I
 honestly am not a huge fan of meat). Also in the past year I've made a low-cost braille display for my science fair project, and won a bunch of awards for that. 
## Plan

Hopefully I can start ordering some of the PCB's before the end of winter break. From there, it's simply time to 
assemble the PCB, debug, debug some more, fix any issues as they arise, and then slowly integrate the parts together to create
the final product.

With the current plan, there is going to be three separate PCB's:

* Carrier Borg: This is the main board that interfaces with the jetson nano. It's responsible for a lot of the compute and IO.
This board also holds an esp32 that handles a lot of the data processing and communication with the outside world.

* Keyborg: This is the keyboard. Pretty self-explanatory.

* Head Borg: This board simplifies a lot of the interconnections between various components. It also hosts elements such as
the battery charger.


I'm trying to keep this as painless as possible, so I intend for the entire design to be modular to reduce the complexity
and hopefully help resolve an issues that may arise. 
## Budget

I'm not going to list every component I may use here (I honestly don't think you want to hear about every single SMT resistor, but if you do, let me know, and I will oblige).
The PCBs are still being designed, so I don't have a hyper-accurate estimate on that yet, but I believe it's a decent ballpark estimate. 

Edit: 27.1.22 - Updated Components


| Product                               | Supplier/Link                                         | Cost             |
|---------------------------------------|-------------------------------------------------------|------------------|
| Jetson Nano                           | https://www.sparkfun.com/products/16271               | $0 (already own) |
| Coral Dual TPU board                  | https://coral.ai/products/m2-accelerator-dual-edgetpu | $0 (already own) |
| RTL-SDR                               | https://www.amazon.com/dp/B01HA642SW                  | $0 (already own) | 
| 3.5in TFT LCD display                 | https://www.adafruit.com/product/2050                 | $27.99           |
| 1000mah LiPo Battery                  | https://a.co/d/hPCsPyL                                | $25.99           |
| Simple USB-C Breakout                 | https://www.adafruit.com/product/5180                 | $1.75            |
| Breadboard Friendly SDPT Slide Switch | https://www.adafruit.com/product/805                  | $0.95            |
| Adafruit USB type c Breakout Board    | https://www.adafruit.com/product/4090                 | $2.95            |
| Printed Circuit Boards                | https://jlcpcb.com/                                   | ~$30             |
| 8MP Autofocus Camera                  | https://www.amazon.com/dp/B082NSDP5L                  | $39.94           |
| 55x Tactile Switches                  | https://mou.sr/3DH0EML                                | $15.73           |
| 55x Diodes                            | https://mou.sr/3DnkWdN                                | $6.53            |
| ATMEGA3209-AFR                        | https://mou.sr/3HAfA1r                                | $1.96            |
| 10x 10k resistor                      | https://mou.sr/3Y35zPK                                | $0.40            |
| 10x 100nf capacitor                   | https://mou.sr/3j6SmGE                                | $0.45            |
| Other Misc. Components                | https://www.mouser.com/                               | ~$50             |
| Solder Paste                          | https://a.co/d/87Ca21u                                | $18.95           | 
| Shipping                              | Mouser, Adafruit                                      | $17.99           |
| Taxes                                 | State Sales Tax                                       | $13.96           |
| Total                                 |                                                       | ~$250            |
