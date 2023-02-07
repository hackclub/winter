---
name: "@StevenJohnson12 (Steven Johnson)"
project: "Custom auto alert door security system"
---

# Door security system

## Summary

My home has been broken into 2 times in the last year when I was not home. I don't currently have a proper security system installed for my doors & windows, because my parents are unable to afford one. So for my project I plan on creating an automatic wireless alert system for my front door using a Flipper Zero device to receive input from a door sensor & then use the radio frequency transmitter on the flipper to send out a signal to my Arduino Uno with a radio receiver antenna connected to my wifi network, running an automatic notification system to automatically send me a text message to my phone using the twilio API. I will then be notified by text every time the door is opened when i'm not home and hopefully this will prevent and future break-ins. 

## Plan

What steps are you going to take to build it? What tools are you going to use? What will you do first, second, third, etc.?
1. Buy all required items listed in the budget. I already own most of the items needed for this project (connectors, many other arduino components. 
2. Connect the Prototyping Board to the Flipper Zero using the GPIO ports
3. Connect a distance sensor (already own) to the flipper and once the sensor's distance from the door jam & the door changes by 1cm, it will trigger the send signal
4. Design and flash a custom software to the flipper to trigger a 500 MHz signal to be sent via an antenna connected to the flipper (already own)
5. Configure the arduino uno (already own) to recieve this signal sent by the flipper via an antenna.
6. Set up the software on the arduino to run a program sending a request to the twilio API to send an SMS message to my phone saying "Front door opened at: TIME"

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Flipper Zero Device   | https://shop.flipperzero.one/ | $169.00 + $4.50 shipping cost & $10.70 in taxes  |
| WIFI Dev Board | https://shop.flipperzero.one/products/wifi-devboard  | $29.00  + $3.60 shipping cost & $1.84 in taxes |
| Prototyping Boards   | https://shop.flipperzero.one/products/proto-boards | $10.00 + $4.10 shipping cost & $0.60 in taxes |
| Flipper Casing   | https://shop.flipperzero.one/collections/flipper-zero-accessories/products/flipper-silicone-case | $15.00 + $2.50 shipping cost & $0.90 in taxes  |
| Arduino Uno   | https://store-usa.arduino.cc/products/arduino-uno-rev3?selectedStore=us | $0.00 (Already Own)  |
| Cables/Connectors   | ALREADY OWN | $0.00  |
| HC-SR04 Distance Sensor   | ALREADY OWN | $0.00  |
| 2x Antenna SX1278 LoRa Radio Wireless Transmitter/Receiver   | ALREADY OWN | $0.00  |
| Soldering Equipment   | ALREADY OWN | $0.00  |
| Twilio Subscription   | ALREADY OWN | $0.00  |



| Total           |                                       | $251.79 |
