---
name: "@sankalparorame"
project: "TheMediBand"
---

# TheMediBand

## Summary
I am going to build a medical device that combines a number of devices in form of a compact and easy to use neckbandand also costs far less than all of them combined. It is aimed at overcoming the problem of delay in diagnosis and treatment of Cardiovascular Diseases (CVDs) due to lack of equipment, specially in rural areas in India. The device combines ECG, EEG and EKG modules alongside being a defibrillator for people undergoing cardiac arrest. It also comprises of a peizo modem that shall help in ascerating blood flow related issues including congestions.

## Plan
Firstly, shall connect all sensors to Pi and program them to make them functioning and cast data to app. Later once the aimed efficiency is achieved though trial error and program refinement, I shall design a neckband case to enclose all the sensors within it to match the design and finally work on PC Client and mobile app and their connectivity.

Update: Umm no I don't have a Pi and won't be requiring it as well for this particular project..
Talking about items in the budget, I would use the Esp 8299 for connecting the whole band through wifi to the mobile app and as it has very limited ports, I shall be coupling/ bridging it with Arduino nano (through Tx Rx pins of both boards) which has more ports comparatively and shall significantly help in reducing the load as well. The LED light strips shall be used to border the band around its curve and would be programmed again through Arduino to emit light colors according to preprogramed range of readings. All the other sensors are used in the band for collection of reading (image of blueprint attached).
I shall be using Arduino IDE for programming both the boards and for the design, after attaching all the sensors and board to a hairband type of structure, I shall be filling the empty spaces with paper Mache and layering it with resin to give it a hard outer body.

## Budget


| Product          | Supplier/Link                         | Cost   |
| ---------------  | ------------------------------------- | ------ |
| ESP 8266         | https://amzn.eu/d/hGUQiLB             | $5.09  |
| Arduino Nano     | https://amzn.eu/d/dtQwCuC             | $10.94 |
| LED Light Strip  | https://bit.ly/3QxxYLh                | $54.05 |
| ECG Sensor       | https://amzn.eu/d/9PO3Y2D             | $64.02 |
| LM35 Temp. Sensor| https://amzn.eu/d/dDBf69F             | $1.34  |
| Peizo Elements   | https://amzn.eu/d/39QZFCs             | $1.85  |
| Heartrate sensor | https://amzn.eu/d/dDBf69F             | $3.44  |
| Jumper Wire      | https://amzn.eu/d/er1h7wi             | $2.45  |
| Total            |                                       | $143.18|
