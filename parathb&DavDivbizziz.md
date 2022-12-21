---
name: ["@parathb", "@DavDivbizziz"]
project: "Artermis"
---

# Robot Puppy

## Summary

<!-- What are you going to build? What does it do? Why are you excited to build it? -->

This project will be done with my younger brother [@DavDivbizziz](https://github.com/DavDivbizziz)

A Robot Puppy, a smaller version of Spot from Boston Dynamics, that is self-aware and can interact with humans, whilst being able to learn and adapt to its environment using sensors. In addition, it will have the ability to be controlled by a human using a DualShock 4 Controller. I am excited about building it because 2 years ago I built a small car with a Raspberry Pi that uses Ultrasonic sensors to avoid bumping into obstacles but I win terms ofas quite limited parts to where I ended up changing the code to add support for controlling the car via a PS4 Controller via Bluetooth to a Phone on a Web Browser that has websocket connection with the raspberry pi on LAN. This was great and it expanded my knowledge on controlling such devices that are self-aware of it's surrounding and made me understand the debugging required to make something like this. So I would like to take this to another step in terms of autonomous functionality with building this robotic puppy, as I will gain many things such as the extended coding that will be required to control the servos for movement in the joints and the data from the sensor that will help control the servos to avoid any obstacles. I would like to also introduce my brother into the more depths of computing with a project like this where he is intrigued already to spend the time together to build something amazing and learn from it as he can expand his knowledge of programming languages such as Python that will be used here. In addition, this project will help my future significantly with my passion and love for programming that I will pursue as a career. 

## Plan

<!-- What steps are you going to take to build it? What tools are you going to use? What will you do first, second, third, etc.? -->

I will be using the following tools to build this robotic puppy:
- 3D Printer
- Soldering Iron
- Laser Cutter
- Heat Gun
- Drill/Screwdriver

The materials that I will be using to build this robotic puppy:
- PLA Filament
- Wires
- Soldering Wire
- Acrylic Sheets

These are the main steps with brief summaries entitling the work that will be done to achieve this build of a robotic puppy:
- Coding a Python Script that controls all the servo motors and sensors with the data logging for debugging purposes, making sure that servo motors are able to move in the correct direction and the sensors are able to detect objects in the correct direction before attaching onto the robotic puppy.
- Designing a model of the robotic puppy then in CAD using softwares such as TinkerCAD/Blender.
- 3D Printing the robotic puppy with the PLA Filament (Printed in multiple parts and assembled together later)
- Laser Cut the main body of the robotic puppy with the Acrylic Sheets that will be used to hold the servo motors and sensors.
- Combine the 3D Printed and Laser Cut parts together to form the shell of the robotic puppy
- Solder the wires to the servo motors/sensors and connect them to the Raspberry Pi to ensure that they are working correctly without any issues.
- Attach the Micro Controller to the robotic puppy and make ensure that it is still working correctly without any issues after assembling it on the body with all sensors and servos working afterwards.
- Continuing the Python Script to control the robotic puppy with the DualShock 4 Controller for manual control and the Raspberry Pi for autonomous control with LiDAR and ultrasonic sensors.
- Creating a GUI that be access via Web Browser for visualisation of the robotic puppy's surroundings with the data logging of the sensors/LiDAR.

## Budget

| Products         | Suppliers/Links                         | Costs   |
| --------------- | ------------------------------------- | ------ |
| LX-16A Servo Motors (x3) | https://www.aliexpress.com/item/4001171374081.html | £13.62 * 3 = £40.86 |
| LX-16A Servo Motors (x5) + Servo Controller + Screws | https://www.aliexpress.com/item/32950283038.html | £78.38 + £3.24 (Shipping) =  £81.62 |
| LiDAR Sensor + Controller | https://www.aliexpress.com/item/1005003788925347.html | £81.31 |
| **AliExpress Total** |  | **£203.79 + £41.01 (Tax) + (Free Shipping) = £244.80** |
|  |  |  |
| 12V 6000mah Rechargeable Battery | https://www.amazon.co.uk/gp/product/B072HR211P | £64.99 |
| Step Down Voltage Regulator  | https://www.amazon.co.uk/gp/product/B07JZ2GQJF | £22.08 |
| M2 Standoffs | https://www.amazon.co.uk/gp/product/B07Y81V64S/ | £8.59 |
| M2 Female Threaded Inserts | https://www.amazon.co.uk/gp/product/B0B8GN63S2 | £5.99 |
| M2 Screws/Washers Kit | https://www.amazon.co.uk/gp/product/B09SH5N5T4 | £6.99 |
| **Amazon Total** |  | **£108.64 + (Tax Included) + (Free Shipping - (Amazon Prime)) = £108.64** |
|  |  |  |
| 4 Servo Horns | https://www.ebay.co.uk/itm/284836448858 | £5.14 |
| **eBay Total** |  | **£5.14 + (Tax Included) + (Free Shipping) = £5.14** |
|  |  |  |
| Ulrasonic Sensor | N/A| Already Own |
| Raspberry Pi  | N/A | Already Own |
| Tools such as 3D Printer/Laser Cutter | N/A | Using my School's 3D Printer/Laser Cutter |
|  |  |  |
| **Total** |  | **£358.58 ≈ $435.36** |
