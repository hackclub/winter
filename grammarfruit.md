---
name: ["@grammarfruit", "@roseappletpe"]
project: "LucidVR Haptic Gloves with RC Car and Robot Arm"
---

# Project Name

LucidVR Haptic Gloves with RC Car and Robot Arm

## Summary

Me and my sister are going to build an open source project that aims to create VR Haptic Gloves for much cheaper than commercial products. It involves 3D printing and soldering as well as modifying cables, we currently just got a 3D printer and have a soldering station. We will be using the driver provided as well as programming our own interface to control an RC Car with a Robot Arm attached, using the gloves as a controller. We have no idea what will act as driving the car or moving the arm but we will figure it out along the way.

## Plan

[Haptic Gloves](https://github.com/LucidVR/lucidgloves/wiki/Prototype-4-Parts-List)=
[Arm and Vehicle](https://howtomechatronics.com/projects/arduino-robot-arm-and-mecanum-wheels-platform-automatic-operation/)

1. Following the Haptic Gloves guide, we will attach the base parts to the gloves then the servos
2. We will then connect everything to the ESP32 and program it
3. Connect the gloves to the computer and get used to how it interfaces with the computer
4. Build the RC Car and Arm using the 3D print models
5. Program the arduino in the vehicle with custom code modeled off the guide, but instead using the gloves to interact with the car

## Budget

Everything will be from amazon so shipping is free, and extra cost will be sponsored by our parents

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Piezoelectric Sensor | [Amazon](https://www.amazon.com/gp/product/B07Q9J5C4G/ref=ox_sc_act_title_1?smid=A30QSGOJR8LMXA&psc=1) | $8.49 |
| Stepper Motor x4 | [Amazon](https://www.amazon.com/gp/product/B00PNEQI7W/ref=ox_sc_act_title_2?smid=AWQBCGWISS7BL&psc=1) | $51.96 |
| Stepper Motor Driver | [Amazon](https://www.amazon.com/gp/product/B01NCE3ZW1/ref=ox_sc_act_title_3?smid=A30QSGOJR8LMXA&psc=1) | $14.99 |
| Torque Digital Servo | [Amazon](https://www.amazon.com/gp/product/B07MFK266B/ref=ox_sc_act_title_4?smid=A2QTZX14X1D97I&psc=1) | $20.99 |
| SG90 Micro Servos | [Amazon](https://www.amazon.com/gp/product/B07MLR1498/ref=ox_sc_act_title_5?smid=A2QTZX14X1D97I&psc=1) | $9.99 |
| HC-05 Bluetooth | [Amazon](https://www.amazon.com/gp/product/B071YJG8DR/ref=ox_sc_act_title_6?smid=A30QSGOJR8LMXA&psc=1) | $10.39 |
| 3S Lipo Battery | [Amazon](https://www.amazon.com/gp/product/B091T3T2NP/ref=ox_sc_act_title_7?smid=A2YFGUYOOPVJZ2&psc=1) | $23.99 |
| Mega R3 Atmega 2560 | [Amazon](https://www.amazon.com/gp/product/B01H4ZLZLQ/ref=ox_sc_act_title_8?smid=A2WWHQ25ENKVJ1&psc=1) | $20.99 |
| Micro USB Cable | [Amazon](https://www.amazon.com/gp/product/B095JZSHXQ/ref=ox_sc_act_title_9?smid=A1FYORZ4MBN3U4&psc=1) | $7.99 |
| Power Bank x2 | [Amazon](https://www.amazon.com/gp/product/B094G1GL8T/ref=ox_sc_act_title_10?smid=A1648LC4ZXGT54&psc=1) | $59.90 |
| WD-40 | [Amazon](https://www.amazon.com/gp/product/B00ITS7LRU/ref=ox_sc_act_title_11?smid=ATVPDKIKX0DER&psc=1) | $11.72 |
| Crimping Kit | [Amazon](https://www.amazon.com/gp/product/B07ZK5F8HP/ref=ox_sc_act_title_12?smid=ANYK2SEFS0EGZ&psc=1) | $36.99 |
| Velcro Straps x2 | [Amazon](https://www.amazon.com/gp/product/B00006IC2R/ref=ox_sc_act_title_13?smid=ATVPDKIKX0DER&psc=1) | $13.96 |
| Bike Gloves Small | [Amazon](https://www.amazon.com/gp/product/B07VHR1ZD3/ref=ox_sc_act_title_14?smid=AUB0SXVRBYFTD&psc=1) | $13.56 |
| Bike Gloves Large | [Amazon](https://www.amazon.com/gp/product/B07VFPY722/ref=ox_sc_act_title_15?smid=AUB0SXVRBYFTD&psc=1) | $13.56 |
| Badge Reel Clips | [Amazon](https://www.amazon.com/gp/product/B0732Z7T8W/ref=ox_sc_act_title_16?smid=A12N14GC39SHEQ&psc=1) | $16.95 |
| WiFi Antenna | [Amazon](https://www.amazon.com/gp/product/B07R21LN5P/ref=ox_sc_act_title_17?smid=A3QGQTWHPH4WOA&psc=1) | $8.99 |
| ESP32-WROOM x2 | [Amazon](https://www.amazon.com/gp/product/B09BM1QW29/ref=ox_sc_act_title_18?smid=A14XFIGSXQ69KC&psc=1) | $21.98 |
| MG90S Servo x2 | [Amazon](https://www.amazon.com/gp/product/B07R3ZYQLC/ref=ox_sc_act_title_19?smid=A3H1S8HVHBGDBK&psc=1) | $63.98 |
| Potentiometer x2 | [Amazon](https://www.amazon.com/gp/product/B07XQ1Q9RN/ref=ox_sc_act_title_20?smid=A1LH3TFU4S09BS&psc=1) | $25.32 |
| PLA Filament | [MatterHackers](https://www.matterhackers.com/store/l/175mm-pla-filament-lightblue-1-kg/sk/M4M03KA6) | $20.87 |
| PLA Filament Natural | [MatterHackers](https://www.matterhackers.com/store/l/175mm-pla-filament-natural-1-kg/sk/M0QV78YA) | $20.87 | 

| Sub-Total           |                                       | $498.43 |
| Tax                 |                                       | $31.15  |
| Total + Tax         |                                       | $529.58 |
