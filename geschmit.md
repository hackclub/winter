---
name: "@geschmit"
project: "MicroGeiger"
---

# MicroGeiger: A geiger counter running on MicroPython

## Summary
This is a DIY-style geiger counter, which utilizes a SBM-20 Geiger tube to detect beta and gamma radiation. Utilizing a nRF52840 and ILI9341 touchscreen display, users can control and monitor radiation levels around them, while being able to also optionally log the data to a supported Bluetooth device.

All future source code relating to this project can be found [here](https://github.com/geschmit/microgeiger).

## Notes
- This project originally used a ESP32 feather board, which would also allocate enough pricing to include a spare SBM-20 tube. Due to supply issues, I've switched to using a nRF-based feather board and removed the spare tube from the order.
- Although my original plan was to use a VFD display which would look more visually appealing, I've settled instead for on a TFT display, which should be more than enough to handle button presses.
- In the future, I may create a more permanant enclosure to store the parts inside; I'm going to use a black case from Adafruit to contain the counter, for now.
- I have yet to locate a test isotope in order to ensure my counter can successfully operate. If I'm unable to locate a legitimate sample, I'll disassemble a smoke alarm and use it's Americium sample.

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
| Adafruit Feather nRF52840 Sense | https://www.adafruit.com/product/4516 | 39.50$ |
| Wiring | https://www.adafruit.com/product/1311 | 15.95$ |
| Wire strippers | https://www.adafruit.com/product/4747 | 11.95$ |
| Slightly overkill toggle switch | https://www.adafruit.com/product/3218 | 3.95$ |
| Buzzer | https://www.adafruit.com/product/160 | 1.50$ |
| JST XH 4-pin | https://www.adafruit.com/product/4874 | 0.95$ |
| ILI9341 Display | https://www.adafruit.com/product/1770 | 29.95$ |
| LiPo Charger | https://www.adafruit.com/product/1304 | 5.95$ |
| 3.7V Battery | https://www.adafruit.com/product/258 | 9.95$ |
| Black case | https://www.adafruit.com/product/3703 | 2.50$ |
| Half breadboard | https://www.adafruit.com/product/4539 | 5.00$ |
| F/M Jumper wires | https://www.adafruit.com/product/1953 | 1.50$ |
| Shipping | Adafruit | 14.90$ |
| Sales tax | Adafruit | 8.39$ |
| I2C Dosimeter | https://www.tindie.com/products/climateguard/dosimeter-with-i2c-radsens-2-arduino/ | 50.00$ |
| Shipping | Tindie | 17.00$ |
| Sales tax | Tindie | 0.00$ |
| **TOTAL** | | 222.94$ |
