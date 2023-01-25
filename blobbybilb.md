---
name: ["@blobbybilb", "@unstoppableblob"]
project: "Plant Watering System"
---

# Plant Watering System 🌱

## Summary

### What
Me and my brother will build an automated plant watering system for our house plants, which will be used in an area where there are no power outlets available.

Basic functionality:
- uses data from data from soil humidity sensors, a temperature sensor, and light sensors to water plants when they need it
- waters plants using a pre-set schedule
- has a remotely accessible interface to water plants, check if/when your plants were watered, and allow for configuration

Additional requirements:
- able to run for a long time without needing any intervention (including adding water, replacing batteries, etc.)
- fully solar powered (except server for remote interface)
- makes minimal noise
- all visible parts of the system look good
- fits in with the plants (not obtrusive)

### Why

Me and my family often forget to water the plants, and figuring out what to do about our plants is always a problem whenever we are away from home for more than a few days. With this project, we want to create a solution to this. We're also looking forward to learning more about electronics, microcontroller programming, and more. Most of this is completely new to my brother, and I'm excited to be working with him on this!

Thanks for giving us this opportunity to learn about electronics/hardware, to create something that will help us, and to have fun while doing it!

### How

The easiest way to move water would be to pump it to the plants, however a water pump wouldn't work for this project because it would take too much energy, make too much noise, and wouldn't look good. Instead, we will have a large container of water, stored at a higher level than the plants' pots. This brings with it its own challenges, but they seem much more approachable than using a pump.

We'll use a solenoid valve to release water when we need it, along with a 3D printed mechanism (and a motor) to deliver the water, through flexible plastic tubes, to the right plant.

Everything will be controlled by two RPi Pico W microcontrollers. Two, because they'll be far apart, and we don't want to have wires everywhere; also, we'll need more GPIOs, especially analog ones to read sensor data. These send data to a Libre Computer AML-S905X-CC SBC—RPi 4s are in short supply and too expensive currently—that will be running a web server to recieve and save the data. The SBC will also serve data and configuration options to a web interface. This is necessary to store data, keep the microcontrollers from being overwhelmed, or using the limited solar power available to them too quickly.

We'll also have an small 8x8 LED matrix, a joystick, and some buttons to perform basic actions without the need of a different device. It will also be used as a status indicator, to let you know how your plants are doing at a glance.

We are 3D printing a lot of things (including our "plant choosing" system, enclosures/mounts for boards, etc.), and each will take multiple iterations of printing, testing, and modifying to be ready. Using a 3D printing service wouldn't be feasible: it would be too expensive, and take too much time. Also, we wouldn't be able to predict costs in advance, so it wouldn't work with the process of recieving the grant. Instead, we went for buying a 3D printer as part of our budget, which will allow for much faster and cheaper protyping.

### [@unstoppableblob](https://github.com/UnstoppableBlob)
> I'm very excited to work on this project, and learn about hardware and microcontroller programming. I've only done software stuff before, and want learn about electronics too. Thanks!

## Plan

1. I will make and test circuits for each part of the project; I'll be using micropython with the RPi Pico.
2. My brother will make the web server to run on the SBC, using Flask.
3. We'll both work on the web interface, along with anything we're missing.
4. Once we have the circuits and the web interface made and tested, we'll start designing the 3D printed parts using Fusion 360/Shapr3D.
5. We'll 3D print our components, and assemble each part of the device.
6. Finally, we'll install the system and watch our plants get the water they deserve!


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Solenoid Valve | [Amazon](https://www.amazon.com/4inch-Normally-Closed-Electric-Solenoid/dp/B074Z5SDG3/ref=sr_1_5?crid=2CB2WL7PD95FI&keywords=solenoid+valve&qid=1673732780&sprefix=solenoid+valve,aps,167&sr=8-5) | $9.35 |
| Solder wire | [Amazon](https://www.amazon.com/MAIYUM-63-37-Solder-Electrical-Soldering/dp/B075WB98FJ/ref=sr_1_5?crid=1IJLBPR14I8KL&keywords=solder+wire&qid=1673748284&sprefix=solder+wi,aps,323&sr=8-5)  | $8.99 |
| 3D Printer | [Amazon](https://www.amazon.com/Official-Creality-Motherboard-Carborundum-8-66x8-66x9-84/dp/B07FFTHMMN?ref_=ast_sto_dp) | $259.99 |
| 3D Filament | [Amazon](https://www.amazon.com/OVERTURE-Filament-Consumables-Dimensional-Accuracy/dp/B07PGY2JP1/ref=sr_1_4?keywords=pla+filament&qid=1673725575&sprefix=pla,aps,280&sr=8-4) | $19.59 |
| Solar panel + charge controller | [Amazon](https://www.amazon.com/ECO-WORTHY-Grid-Small-Solar-Panel/dp/B09RZRY4QB/ref=sr_1_3?crid=3V3RMW6F24XYT&keywords=10w+solar+panel+kit&qid=1673748012&sprefix=10w+solar+panel+kit,aps,202&sr=8-3) | $33.99 |
| 12v battery | [Amazon](https://www.amazon.com/TalentCell-Rechargeable-3000mAh-Lithium-External/dp/B01M7Z9Z1N/ref=sr_1_3?crid=3HK2R8OWRVGGO&keywords=li+ion+battery+12v&qid=1673748055&sprefix=liion+battery+12v,aps,207&sr=8-3) | $28.99 |
| RPi Pico W (x2)| [PiShop](https://www.pishop.us/product/raspberry-pi-pico-w/) | $12.00 |
| Libre Computer AML-S905X-CC SBC | [Amazon](https://www.amazon.com/Libre-Computer-AML-S905X-CC-Potato-64-bit/dp/B074P6BNGZ/ref=sr_1_3?keywords=single+board+computer&qid=1673724605&sprefix=singl,aps,194&sr=8-3) | $35.00 |
| SBC Case | [Amazon](https://www.amazon.com/LoveRPi-Cooling-Raspberry-Computer-Translucent/dp/B0792VH52T/ref=sr_1_2?crid=AGZV7EB0JFD6&keywords=libre+computer+case&qid=1673725895&sprefix=libre+computer+le+case,aps,427&sr=8-2) | $14.99 |
| Humidity Sensor | [PiShop](https://www.pishop.us/product/odseven-yl-69-soil-hygrometer-humidity-detection-module-soil-moisturewater-sensor-for-arduino/) | $11.85 |
| Photoresistor | [PiShop](https://www.pishop.us/product/5549-photoresistor-pack-of-10/) | $3.45 |
| Joystick | [PiShop](https://www.pishop.us/product/analog-2-axis-thumb-joystick-with-select-button/) | $2.45 |
| LED matrix (x2)| [PiShop](https://www.pishop.us/product/8-8-led-dot-matrix-display/) | $6.90 |
| Buttons | [PiShop](https://www.pishop.us/product/colorful-square-tactile-button-switch-assortment-15-pack/) | $5.75 |
| Soldering Iron | Owned | - |
| Jumper wires | Owned | - |
| Hot glue gun/glue | Owned | - |
| Reed switches | Owned | - |
| Magnets | Owned | - |
| Shipping (approx.) | - | $15.00 |
| Tax (approx.) | - | $51.51 |
| --- | --- | --- |
| **Total** | - | $519.80 |
