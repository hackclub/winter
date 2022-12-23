---
name: "@LuanderFarias"
project: "simplo-vr"
---

# Simplo VR

## Summary

Simplo VR is a cheap virtual reality headset with 6-dof and hand tracking with support for steamvr. made for the community by the community, simplo is the easiest way to enter in the virtual reality worlds without paying a fortune...

Fully open-source and customizable, made to be refined and improved.

## Plan

Simplo is gonna be roadmaped based on "modules". which is basically the functions necessary till it gets ready.
- chasis - the basic process of building a pretty simple frame just to support the screen and cameras. gonna make it from cardboard or popsticks at first but when i finally make a final design i'm gonna 3d print it.
- 6-dof -  Code the accelerometer/gyroscope in a arduino and the webcam app to full-body tracking and positioning the headset to make the headset go 6-dof.
- steamvr - Code the main thing. A communication with steam to transfer the headset information to the game. gonna try to offer support for all games but i don't promise it lol.
- hand-tracking - Finally, code the hand tracking thing using computer vision and cameras, which is supposed to be a replacement for the controllers. using gestures instead of buttons.
- Simplo-software/website - code the website to present the project to the world and the software for configuration, calibration, setup, etc...
- Finishing - gonna make the new frame (probably 3D printed), make the code more readable, etc...

## Research
Simplo is developed based on other open-source vr headsets out there. Here are some of the links for the repositories that inspires simplo:
- https://github.com/HadesVR/HadesVR
- https://github.com/HadesVR/Wand-Controller
- https://create.arduino.cc/projecthub/138706/relativty-is-a-low-cost-vr-headset-you-can-build-yourself-fa6e7d
- https://www.notebookcheck.net/Build-an-Arduino-based-VR-headset-with-this-cheap-project.469070.0.html

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 1x Arduino Micro | https://store-usa.arduino.cc/products/arduino-micro | $38.61 |
| 1x Acelerometer and gyroscope mpu6050 | https://www.ebay.com/itm/295005468005?chn=ps&mkevt=1&mkcid=28&srsltid=AeTuncrx8Nd6PKD56swU6q1U-7z0kxZe6F_kvLrvcyVwZBaKHMdjDY9cypM | $0.99 |
| 1x 5-inch Raspberry Pi LCD Screen with HDMI interface | https://www.crowpi.cc/products/rr050-5-inch-raspberry-pi-screen-touchscreen-monitor-tft-display-for-raspberry-pi-4b-3b-3b-2b-bb-black-banana-pi-windows-10-8-7?variant=39701621014661&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AeTuncr8B4F9Q7yh7FjVHqnMsxJRtYMvFLyGgjXL76QPDOjYqyzIV27kEU8 | $53.10 |
| 4x Arduino camera module | https://tinkersphere.com/arduino-compatible-components/944-ov7670-vga-camera-module-for-arduino.html | $44.95 |
| 5x Led | gonna buy, close here :) | $2.00 |
| Jumper wires | gonna buy, close here :) | $7.00 |
| Total | Changed a lot of itens cause everything is way expansive where i live | $146.65 |
