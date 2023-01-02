---
name: "@geschmit"
project: "MicroGeiger"
---

# MicroGeiger: A geiger counter running on MicroPython

## Summary
This is a DIY-style geiger counter, which utilizes a SBM-20 Geiger tube to detect beta and gamma radiation. Utilizing a ESP32 and ILI9341 touchscreen display, users can control and monitor radiation levels around them, while being able to also optionally log the data to a supported Bluetooth device.

All future source code relating to this project can be found [here](https://github.com/geschmit/microgeiger).

## Notes
- Although my original plan was to use a VFD display which would look more visually appealing, I've settled instead for on a TFT display, which should be more than enough to handle button presses.
- In the future, I may create a more permanant enclosure to store the parts inside; I'm going to use a black case from Adafruit to contain the counter, for now.
- I'm ordering a spare tube in case the one shipped with the I2C Dosimeter breaks in-transit. If both are intact upon arrival, I'll either keep one for a spare or return the excess tube.
- I have yet to locate a test isotope in order to ensure my counter can successfully operate. If I can't find one online or in-person, I'll disassemble a smoke alarm and use an Americium sample.

## Plan
My plan is, as followed:
- Order parts from suppliers
- Test parts(primarily the tube) to ensure working order
- Assemble geiger counter
- Bootload MicroPython and flash program code
- Share source & design with Hack Club!

## Budget

| Product | Supplier/Link | Cost |
| --- | --- | --- |
| Adafruit ESP32 Feather V2 | https://www.adafruit.com/product/5400 | 19.95$ |
| Wiring | https://www.adafruit.com/product/1311 | 15.95$ |
| Wire strippers | https://www.adafruit.com/product/527 | 14.95$ |
| Slightly overkill toggle switch | https://www.adafruit.com/product/3218 | 3.95$ |
| Buzzer | https://www.adafruit.com/product/160 | 1.50$ |
| JST Cables | https://www.adafruit.com/product/3955 | 1.50$ |
| ILI9341 Display | https://www.adafruit.com/product/1770 | 29.95$ |
| LiPo Charger | https://www.adafruit.com/product/1304 | 5.95$ |
| 3.7V Battery | https://www.adafruit.com/product/258 | 9.95$ |
| Black case | https://www.adafruit.com/product/3703 | 2.50$ |
| Half breadboard | https://www.adafruit.com/product/4539 | 5.00$ |
| F/M Jumper wires | https://www.adafruit.com/product/1953 | 1.50$ |
| Shipping | Adafruit | 14.90$ |
| I2C Dosimeter | https://www.tindie.com/products/climateguard/dosimeter-with-i2c-radsens-2-arduino/ | 50.00$ |
| Shipping | Tindie | ~17.00$ |
| Spare SBM-20 tube | https://www.amazon.com/MightyOhm-SBM-20-Geiger-Muller-Tube/dp/B08MJ2Z3H3/ | 49.95$ |
| Shipping | Amazon | 0.00$	| 
| **TOTAL** | | 244.50$ |
