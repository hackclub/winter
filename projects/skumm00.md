---
name: "@Skumm00"
project: "ArduinArm"
---

# ArduinArm

##  Summary

My project is going to be a custom-controlled, Arduino-powered, robot arm. I've used 3D printers and worked with Arduino circuits at my middle school, so I believe
this project shadows my skills well while still being a challenging build. Plus, this project would be a great introduction into the field of mechatronics, which is
the usage of automated engineering (like 3D printers and CNCs) for industrial development, which is a field I would like to consider in the future. 

##  Plan

I will be using a pre-existing set of [3d models](https://thangs.com/designer/m/3d-model/38899) for the overall structure of the robot arm. For the first 3 axes, 
the waist, the shoulder, and the elbow, I will be using the MG996R servos - for the wrist roll/pitch I will use the smaller SG90 micro servos. The servos will come 
with screws for installation. The circuitry for this project is simple, with 6 servo motors being connected to six digital pins on the Arduino board. The servos will 
require at least 5V of power coming from the external power source. As for the software behind the arm, there are a number of tutorials I am planning on following 
(such as this one's servo arm code: https://create.arduino.cc/projecthub/ryanchan/simple-programmable-robotic-arm-bd28a0). The overall code will be a perpetual loop 
that constantly checks for outside input via bluetooth to the arm - if there is any, the corresponding motor will move. I will likely be using MIT App 
Inventor in order to create the app to communicate with the robot.

##  Budget

| Product  | Supplier/Link  | Cost  |
| --------------- | ------------------------------------- | ------ |
| 3D printer  | [Amazon](https://www.amazon.com/Voxelab-Structure-Certified-Removable-8-66x8-66x9-84in/dp/B09BNG5884/ref=sr_1_8?crid=51ZBDXLXFTJD&keywords=3d%2Bprinter&qid=1671945440&sprefix=3d%2Bprint%2Caps%2C148&sr=8-8&ufe=app_do%3Aamzn1.fos.f5122f16-c3e8-4386-bf32-63e904010ad0&th=1) | $159.99  |
| Arduino UNO kit (w/ breadboard, USB, and power cable) | [Amazon](https://www.amazon.com/ELEGOO-Starter-Tutorial-Compatible-Official/dp/B01DGD2GAO/ref=mp_s_a_1_7?crid=3IAE05UHSNUUD&keywords=arduino+uno+kit&qid=1672039761&sprefix=arduino+uno+kit%2Caps%2C445&sr=8-7)  | $26.99 |
| 3d Printer Filament | [Amazon](https://www.amazon.com/dp/B09LV3TXMG?pd_rd_i=B0936Z3G14&pf_rd_p=72255690-0c34-414f-8ce9-39b891076bd4&pf_rd_r=2F2SZ8B91YF2N7YNMQRX&pd_rd_wg=YNB3c&pd_rd_w=Jse9Z&pd_rd_r=eebf8941-bac8-4de3-ba4d-154fd39cfcfe&th=1&psc=1)  | $15.49 |
| 4x Torque Gears | [Amazon](https://www.amazon.com/MG996R-Torque-Digital-MELIFE-Helicopter/dp/B09BQP2F6M/ref=sr_1_2?crid=32O5XP6EFSTGS&keywords=Metal+Gear+Torque+Digital+Servo+with+Arm+Horn&qid=1671949142&s=toys-and-games&sprefix=metal+gear+torque+digital+servo+with+arm+horn%2Ctoys-and-games%2C139&sr=1-2)  | $17.99 |
| Bluetooth Module | [Amazon](https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR/ref=as_li_ss_tl?ie=UTF8&qid=1533394818&sr=8-3&keywords=HC-05&linkCode=sl1&tag=howto045-20&linkId=86cdebbcfc701f763369f68487f8bbc9)  | $10.39 |
| Micro Servo Motors | [Amazon](https://www.amazon.com/Micro-Servos-Helicopter-Airplane-Controls/dp/B07MLR1498?crid=GE0AQEOIKH0G&keywords=SG90&qid=1668339645&sprefix=9g%2Bservo%2Bmotor%2Caps%2C539&sr=8-8&th=1&linkCode=sl1&tag=howto045-20&linkId=6fdd2d64320cbe9133dc62e4ee9e75d5&language=en_US&ref_=as_li_ss_tl)  | $10.57 |
| Total  | 231.53 + $17.85 tax  | $249.38 |

Shipping is included. 
