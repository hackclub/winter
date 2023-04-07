---
name: "@TheScientist101"
project: "Smart RC Car With AI Camera"
---

# Smart RC Car With AI Camera

## Summary

I am going to build an RC car chassis that carries a smart camera. This car will have a smart camera that can detect objects and can inform the driver to react accordingly. The car will be controlled with an app on my phone and data from the car will be sent back to the phone. I am excited to build this because this is a unique project for me. I have never worked on a hardware related project before, but combining my knowledge about software and hardware will create a product that is (hopefully) fun to play with, and easy to use.

## Plan

Once my parts arrive, I will first assemble the chassis without the camera and raspberry pi, but with the microcontroller for control. The microcontroller will have a different battery pack than the motors, listed below. This should take the first 2-3 days of the challenge. For the hardware in the chassis, I will loosely follow this. https://learn.adafruit.com/my-mini-race-car/introduction. I will create a Python library to allow the user to write simple directions for the robot. Next, I will work on the app to control just the robot without any of the sensory information. I will build the app using Xcode on my macbook. I am using Xcode because I need to build the app for my iPhone and this will allow me to reference the source code for Bluefruit Connect which has the ability to control the robot in the tutorial. The source code for Bluefruit Connect is located at https://github.com/adafruit/Bluefruit_LE_Connect_v2. The app will connect with the Adafruit Feather with bluetooth. The app will have one joystick that controls its direction and speed on the right side of the screen. The left side of the screen will have live video feed with identified objects and text showing the temperature and humidity data. The left side, however, will not be added to the app until after the raspberry pi and camera are mounted. The data from the raspberry pi will be sent through Bluetooth; however, if this is too slow, it will be sent through the local network. This will approximately take another 2-3 days. Third, I will add the raspberry pi and its camera. The raspberry pi will be powered by another battery powerbank. The raspberry pi will not be directly connected to the motors or the feather. The raspberry pi will be used for data collection and will be connected to the camera and simply mounted on the chassis. The reason that I will be using the raspberry pi for the camera and not the drivetrain is because the image processing may need all of the Raspberry Pi's computing power. I will perform the image processing through Tensorflow Micro with Google's trained computer vision model; however, if i run into errors while working with Tensorflow, I will use Teachable Machine due to its simplicity and ease of use. All of the computer vision processing will be done on the raspberry pi. The user can then write a script to react if a certain object is seen. For example, if the user wrote a script for a surveillance loop, the robot could react if a face isn't recognized. Any alerts or processed FPV information will then be relayed to the app. This will allow the raspberry pi to communicate with the drivetrain, even though they aren't directly linked. This should take approximately 1-2 days depending on the other work I have that day. Finally, I will add the sensory functionality to the app. This should take approximately 3-4 days and the project will be complete.

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Adafruit Feather | https://www.adafruit.com/product/2829 | $29.95 |
| DC Motor+Stepper | https://www.adafruit.com/product/2927 | $19.95 |
| Temperature & Humidity Sensor Breakout Board | https://www.adafruit.com/product/1899 | $10.95 |
| Robot Chassis | https://www.adafruit.com/product/3244 | $24.95 |
| Lithium Ion Battery | https://www.adafruit.com/product/1578 | $7.95 |
| AA Battery Holder | https://www.digikey.com/en/products/detail/adafruit-industries-llc/830/5353623 | $2.95 |
| AA Batteries | https://www.adafruit.com/product/3349 | $2.95 |
| Jumper Wire | https://www.adafruit.com/product/1956 | $1.95 |
| Jumper Wire Extender | https://www.adafruit.com/product/1954 | $1.95 |
| Breadboard (I own) |  | $0.00 |
| USB A to Micro USB (I own) |  | $0.00 |
| Shield Stacking Headers | https://www.adafruit.com/product/85 | $1.95 |
| Small Screwdriver For Electronics | https://www.adafruit.com/product/3284 | $1.50 |
| Bump Absorber For Electronics | https://www.adafruit.com/product/550 | $0.95 |
| Camera For Raspberry Pi | https://www.adafruit.com/product/3099 | $29.95 |
| Raspberry Pi 4 (Ordered, but need reimbursement, have receipt) | https://mycroft.ai/product/raspberry-pi-4-model-b-2gb/ | $45.00 |
| SD Card for RPi | https://www.adafruit.com/product/2820 | $9.95 |
| Battery Pack For Raspberry Pi | https://www.adafruit.com/product/1959 | $14.95 |
| Tax + Shipping (Adafruit) | | $28.19 |
| Tax + Shipping (Mycroft) | | $6.88 |
| Tax + Shipping (Digikey) | | $5.65 |
| Total           |         | $249.52 |
