---
name: "@yutarour"
project: "Resin Printed Weather Proof Arduino Temperature Logger Case"
---

# Resin Printed Weather Proof Arduino Temperature Logger Case

## Summary

I am going to build a enclosure for a BMP280 based arduino temperature, humidity and pressure logger. Since resin is waterproof, it can be used for outdoor applications. 
I will be making a model of the enclosure in fusion 360 and printing it with a resin printer.

## Plan

1. Acquire all of the materials: 
  - Resin printer
  - Arduino Uno -Already have at home
  - BMP280 -Already have at home
  - Resin
  - Female to Male wires -Already have at home
  - Isopropyl alchohol - Already have at home
  - Resin wash and cure machine
  - 9V battery for arduino -Already have at home
2. In Fusion 360, design a case that fits all of the components in.
  - About 9x9x3 (LxWxH)
  - Should have mounting screws on it
3. Using the slicing software that comes with the printer, slice the model
4. Assemble the printer according to the instructions that come with the printer
5. Load the model onto a MicroSD card and put into printer and press print
6. Remove the model from the print bed
7. dunk in isopropyl alchohol for 15 minutes
8. To cure the resin, place under UV light for 15 minutes
9. Assemble the electrical circuit
  - BMP280 is a I2C enabled device; therefore SCL, SDA, VCC, GND are the pins that are required to be connected
  - Connect the SCL pin to analog pin 5 and SDA to analog pin 4. 
  - Connect VCC to arduino 5V (the BM280 has a voltage regulator)
  - Connect GND to arduino GND
10. Write The code
  - All data will be stored in EEPROM or in a micro SD card (TBD)
  - The BMP280 is on I2C address 0x76
  - CSV file format will be used to log data since it is the simplest and compatible with most systems.
  - The time will be logged as minutes away from start time using the arduino millis() function. 
    - In order to avoid overflow of the long which stores millis() a if statement will exist that will reset the variable. 
    - The data will not be deleted since the microSD card is non volatile. 
11. Assemble the entire thing
  - Put the electronics in the housing
  - Close housing
12. Testing
  - Place the box outside in preferably rain or snow for 24 hours and see if it breaks
  - If it is alive after 24 hours, extract the data and use python matplotlib to graph the temperature change over time
13. Done

## Budget

| Product                   | Supplier/Link                         | Cost   |
| ------------------------- | ------------------------------------- | ------ |
| Voxelab Proxima 6.0       | https://a.co/d/2MQH0pi                | $119.00|
| ELEGOO Mercury 2 in 1 Washing and curing machine     | https://a.co/d/60ervD3                | $111.99|
| Arduino Uno               | Already Own                           | $0.00  |
| BMP280 sensor             | Already Own                           | $0.00  |
| Isopropyl Alchohol        | Already Own                           | $0.00  |
| 9V battery                | Already Own                           | $0.00  |
| Female to Male wires      | Already Own                           | $0.00  |
| Translucent Resin         | https://a.co/d/cN24vPx                | $17.99 |
| Total                     |                                       | $248.98|
