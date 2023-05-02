---
name: "@karmanyaahm"
project: "Project Oreo"
---

# Project Oreo

## Summary

A fleet of USB Rubber Duckies that change everyone's background into Oreos (or something else funny). 
I have previously made some with Digisparks, but having to download the images from the internet makes injection slower and less reliable.
So, I plan to make v2.0 with RP2040 based boards which have 8MB of flash. They store the image locally and have enough processing power to be a USB Mass Storage device at the same time as two HID devices (Mouse and Keyboard).

There are two main challenges:
1. Technical: Implement OS Detection based on USB Fingerprints in CircuitPython (maybe even contribute it upstream depending on how complicated it is).
2. Logistical: giving these to all my friends and acquaintances for them to deploy it on prank day, and teaching them to make sure they only prank people consensually, and safely, to avoid accidentally causing data loss.

## Plan

Already done:
- Write scripts to open a terminal, get permissions and set a desktop background using a USB Rubber Ducky [1](https://www.youtube.com/watch?v=FbiJCnHBr70) [2](https://github.com/karmanyaahm/rubber_ducky/tree/v1/v2win) [3](https://hackclub.slack.com/archives/C0M8PUPU6/p1672451844899509)

Will do before the 10 days:
- Study how USB Rubber Ducky OS detection works and collect OS fingerprints

Will do during the 10 days:
- Ask my friend to design and 3D print cases for the Trinkeys.
- Write OS Detection - different keystroke sequences for different operating systems - based on USB field order fingerprinting in TinyUSB (the library CircuitPython uses).
- Add old wallpaper backup to scripts, just in case people lost it.
- Assemble the Trinkeys, USB Ports, and cases.

After the 10 days:
- Give this to my friends and let them have fun with it :) 

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 20x Adafruit Trinkey QT2040 | https://www.adafruit.com/product/5056 | $143.20  |
| Soldering Iron (etc.) | | Already have |
| Solder Wick | https://www.adafruit.com/product/149 | $3.00 |
| Simple Pliers | https://www.adafruit.com/product/146 | $3.00 | 
| Diagonal Cutters | https://www.adafruit.com/product/152 | $7.25 | 
| Wire Stripper | https://www.adafruit.com/product/147 | $6.95 |
| NinjaFlex 500g TPU Filament | https://www.adafruit.com/product/2245 | $29.95 |
| Adafruit Free Shipping | | $0 |
| Adafruit Sales Tax | | $15.96 |
| Adafruit Total | | $209.31 | 
| 20x USB Jacks | https://www.aliexpress.us/item/3256801442936921.html | Already have |
| SuperPP Clear Resin | https://www.amazon.com/dp/B08RSB1B6Q | $39.80 |
| Amazon Tax | | $3.28 |
| Amazon Total | | $43.08 |
| Total           |                                       | $252.39 |

### Explanation
I originally bought the filament and was planning to get a friend nearby to print it, but his printer refused to work :(. So, I asked @kaiz715 to print with his resin printer, and the resin is for him. (I'll cover the 2.39 myself)
