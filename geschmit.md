---
name: "@geschmit"
project: "MicroGeiger"
---

# MicroGeiger: A geiger counter running on MicroPython
Because nothing else has good display drivers.

## Summary
This is a DIY-style geiger counter, which utilizes a SBM-20 Geiger tube to detect beta and gamma radiation. I've always been curious in obtaining my own counter, but due to them being either comically expensive, out of stock, or both, it's considerably hard to obtain one. Instead, I'm buying a tube and using I2C to read the data it outputs, which is then displayed to the user. The radiation data will also be broadcasted via Bluetooth to view on a compatible device.

## Notes
- Although my original plan was to use a VFD display which would look more visually appealing, I've settled instead for on a ILI9341 display, which should be more than enough to draw graphics and provide user input.
- In the future, I may create a more permanant enclosure to store the parts inside; I'm going to use a black case from Adafruit to contain the counter, for now.
- I'm ordering a spare tube in case the one shipped with the I2C Dosimeter breaks in-transit. If both are intact upon arrival, I'll either keep one for a spare or return the excess tube.
- I need to locate a test isotope in order to ensure my counter can successfully operate.

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
| Shipping | Amazon | 0.00$ :trollface:	| 
| **TOTAL** | | 244.50$ |
