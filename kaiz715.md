---
name: "@kaiz715"
project: "Super Accurate Waterproof Electronic Scale"
---

# Super Accurate Waterproof Electronic Scale

## Summary

I am planning on building an electronic scale that can read up to 0.01 grams accuracy. I was inspired to do this because my kitchen scale broke from water damage, and I was wondering how electronic scales measured weight. By doing this, I can create a functional scale to replace the broken one I have while expanding my knowledge on electrical engineering and CS, which I plan on majoring in when I go to college.

## Plan

First, I'll use the breadboard and wires to hook up the resistor, and load cell in a voltage divider. This allows me to read the voltage across the load cell using the HX711 ADC, which will correspond to the force (weight) that is being applied on the load cell. The HX711 reads the load cell through a wheatstone bridge setup internally. For the load cell to function correctly, I will design and 3d print a precise platform to adjust for uncentered weights. This part needs to be precise, hence the need for a resin 3d printer as opposed to using a traditional FDM printer. 

Second, I will calibrate the scale using standardized masses and hook up the arduino and code in the calibration equation to convert the voltage to a weight. The arduino will be able to connect to the HX711 through an I2C interface. I will also code a user interface which allows the calculated weight to be displayed on a computer. Having it be connected to the computer also potentially allows wireless access to the scale readings, if I decide to code that in later. The arduino that I have comes with batery pack, but when the arduino is connected to the computer, the computer supplies the power to the arduino. The arduino will then power the circuit using its 5v line.

Third, I will design and 3d print an enclosure to put the breadboard, arudino, and all the other materials into to make it look actually like a scale and finish the project. I hope to make this scale also waterproof, which is possible because the resin enclosure should be waterproof due to the resin printing process. The enclosure that I will design will consist of two parts that I will super glue together to form a watertight seal. No water should be able to leak through the 3d print because the small layer heights of resin printing. see https://www.liqcreate.com/supportarticles/waterproof-airtight-resin-3dprinted-part/

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Flashforge Foto 8.9 (orange cover)   | https://www.flashforgeshop.com/product/flashforge-foto-89-lcd-3d-printer-higher-speed-for-garage-kit-use?&cID=31 | $199.99  |
| Arduino Uno | already have  | $0.00 |
| Isopropyl Alchohol | aready have|$0.00 |
| Resin | will purchase with own money |$0.00 |
| Load Cell | https://www.sparkfun.com/products/13329 | $9.50 |
| Soldering iron + solder + flux| can borrow from dad's work | $0.00 |
| HX711 ADC | https://www.sparkfun.com/products/13879 | $10.95 |
| Wires | already have | $0.00 |
| Resistors | already have | $0.00 |
| Breadboard | already have | $0.00 |
| Super Glue | already have | $0.00 |
| Standardized masses | can borrow from school | $0.00 |
| Shipping (sparkfun) | | $10.80 |
| Free shipping (flash forge)| |
| Tax | | $18.50|
| Total           |                                       | $249.74 |