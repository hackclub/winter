---
name: "@LinusSkucas"
project: "PlantPrint"
---

# PlantPrint

## Summary

PlantPrint at its core will be a device that senses the moisture in the soil of a plant. But what fun is a plant monitor that doesn’t try to do everything under the sun? So in addition to sensing soil moisture, PlantPrint has an air quality sensor that senses PM2.5 particles, like the ones for wildfire smoke. It makes this data available over the internet through an SparkFun Thing Plus (which has an ESP32) and over HomeKit. But what if you don’t have your phone? Well it also includes a really cool flexible eInk display that can be mounted on the side of the plant’s pot. Finally, like a true data collector, I will use a thermal printer to plot the change of moisture and air quality throughout the data, attached to a Raspberry Pi.

## Plan

I’ll start by assembling the sensor portion of the project. I’ll get the sensors reading data and reporting it to the ESP32. Then I’ll do some programming to connect it to the internet and integrate it with HomeKit. I’ll then connect the eInk display up and mount it to the side of the plant’s pot and program it to display the current air quality. Finally, I’ll set up the thermal printer so that I can print out the data.

## Budget

> View the entire cart on DigiKey (contains links to the products): https://www.digikey.com/short/z80hb2m9

| Product         | Cost   |
| --------------- | ------ |
| Raspberry Pi (Already Own) | $0.00 |
| 3D Printed Enclosure (Can print for free) | $0.00 |
| SparkFun Thing Plus | $$24.95 |
| Qwiic Cable Kit | $8.95 |
| Adafruuit PMSA003I Air Quality Sensor (Qwiic) | $44.95 |
| I2C to Dual UART Module | $8.00 |
| 3.7V 2.5 AH Lithium Battery | $14.95 |
| eInk Ribbon Cable Extension | $1.50 |
| Adafruit Monk Makes Plant Monitor | $11.94 |
| 24 Pin Ribbon Cable Extender | $0.95 |
| Adafruit eInk Breakout | $8.50 |
| 2.9in Flexible eInk | $24.95 |
| Thermal Receipt Printer Guts | $49.95 |
| Wall Mount Adapter 9V 1A | $9.63 |
| 2.1mm Barrel Jack to Thermal Screw Block Connector | $2.00 |
| *Shipping* | *~$11* |
| *Tariff (‽)* | *$1.76* |
| *Sales Tax (🤮)* | *$22.75* |
| **Total** | **$250.00** |

*Shipping depends on when backordered items are shipped
