---
name: "@rslohn81"
project: "DonkeyCar RC car"
---

# DonkeyCar RC car

## Summary
I am joining @RhysMP 's project see PR 118 (https://github.com/hackclub/winter/pull/118) 

I had the idea of adding onto Rhys's project by seeing the diffirences in pathfinding and how efficent and effective they would be from a Pi which vs a Jetson Nano which is a small computer build to run neural networks and AI. We both think it will drastically improve the bot's pathfinding but we are both curious to what degree.

We also decided to add a Servo Driver to be able to control the car without just using GPIO pins

## Plan

First I will order all of the products. 

Then I will send all the CAD files required for this car to my HS's Physics teacher to 3D print using the makerbots we have on campus.

I will then clean up all of these prints.

I will attach the parts together. (Pi > 3d printed plate) (Camera to Adatper) || (Jetson > Adapter)
Only for jetson then we will connnect the Wifi Module.

Then I will install the Donkeycare software and configure it all. 

Then using my own firmware that I will code, with what is going to be an extremely redimentary UI I would like to have fine control of the RC car. I would also like to be able to do basic autonomous pathfinding using the camera. 

With the addition of the Jetson Nano we want to see the effectiveness of each at pathfinding and using AI and deeplearning to navigate a space. We hope to be able to qualitatively measure the effectiveness of each's self driving but we see that it may be an issue. We will try to see if there is really a major diffierence using a Nano which is made for AI/ML and has a GPU.

http://docs.donkeycar.com/

This video gives a pretty good overview of using the Jetson nano for self-driving: https://www.youtube.com/watch?v=GOkYPXheWSY


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Red LaTrax® Desert Prerunner: 1/18-Scale 4WD Electric Truck       | https://latrax.com/products/prerunner | 142.30 (Includes tax) |
| USB Battery with microUSB cable | https://www.amazon.com/Anker-PowerCore-Compact-Portable-Smartphones/dp/B07211V9XG | ~~36.95~~ 0 already owned|
| Raspberry Pi 4 Model B 2019 Quad Core 64 Bit WiFi Bluetooth (4GB) | https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X | 174.08 (Includes tax)
| SainSmart Wide Angle Fish-Eye Camera Lenses for Raspberry Pi 3 Model B Pi 2 Model B+ Arduino, RoHS certified | https://www.amazon.com/gp/product/B00N1YJKFS | 24.08 
| GenBasic 80 Piece Female to Female Jumper Wires (4 and 8 Inch)  | https://www.amazon.com/GenBasic-Piece-Female-Jumper-Wires/dp/B01L5ULRUA | 6.49
| Donkey Screw Kit | https://store.donkeycar.com/products/plastic-thread-forming-screw-kit?variant=9486169276473 | 5.36
| SunFounder PCA9685 16 Channel 12 Bit PWM Servo Driver | https://www.amazon.com/gp/product/B014KTSMLA | 14.22 
| NVIDIA Jetson Nano Developer Kit | https://www.amazon.com/NVIDIA-Jetson-Nano-Developer-945-13450-0000-100/dp/B084DSDDLT | 133.16
| TP-Link Nano AC600 USB Wifi Adapter( | https://www.amazon.com/TP-Link-Mini-Wireless-Supports-10-9-10-14/dp/B07PB1X4CN/ | 14.41
| Total    ~ 514.1`
