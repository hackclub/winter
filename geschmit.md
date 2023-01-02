---
name: "@geschmit"
project: "MicroGeiger"
---

# MicroGeiger: A geiger counter running on MicroPython
Because nothing else supports the ST7789 display good enough.

## Summary
This is a DIY-style geiger counter, which can record and display nearby radiation levels. I've always been curious in obtaining my own counter, but due to them being either comically expensive, out of stock, or both, it's hard to obtain one. Instead, I'm buying a tube and using I2C to read the data it outputs, which is then displayed to the user. The radiation data will also be broadcasted via Bluetooth to view on a compatible device.

## Notes
- Although my original plan was to use a VFD display which would look more visually appealing, I've settled instead for on a ST7789 display, which should be more than enough to draw graphics.
- In the future, I may create a more permanant enclosure to store the parts inside.

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
| SBC(Adafruit ESP32 Feather V2) | https://www.adafruit.com/product/5400 | 19.95$ |
| Display(ST7789) | https://www.adafruit.com/product/5394 | 17.50$ |
| Wire spools | https://www.adafruit.com/product/1311 | 15.95$ |
| Bread Board | https://www.adafruit.com/product/239 | 5.95$ |
| Slightly overkill power switch | https://www.adafruit.com/product/3218 | 3.95$ |
| Piezo buzzer | https://www.adafruit.com/product/160 | 1.50$ |
| JST Cables | https://www.adafruit.com/product/3955 | 1.50$ |
| Tube module w/ I2C connections | https://www.tindie.com/products/climateguard/dosimeter-with-i2c-radsens-arduino/ | 53.00$ |
| Spare SBM-20 tube | https://www.tindie.com/products/atlasatomics/geiger-tube-sbm-20/#product-description | 19.99$ |
| Shipping | Adafruit | |
| Shipping | Tindie | | 
| Sales tax | Combined | |
| Total | | | 
