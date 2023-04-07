---
name: ["@SiruX21", "@Look-Its-Sky", "@RartedRussian", "@Cimbobimb"]
project: "AI-Powered RC Car"
---
# AI Powered RC Car
## Summary

We plan on making a remote controlled car that can drive itself forwards and backwards. This car will be controlled with simple voice commands such as, "Forward!, Backward!, Stop!, Left!, Right!". It will also include on-board image detection in order to properly avoid obstacles along its' way.

## Plan

For the base RC vehicle, we are utilizing an off the shelf self-assembly frame kit to house the components. We will then connect the motors that come with the frame to our Raspberry Pi. After this, we will mount the battery bank on the underside of the vehicle. On both sides of the vehicle, we'll mount our Jetson Nanos. At the center of the vehicle, we will mount the low-power network switch to create our little internal network. We will connect both the Pi and both of the Jetson Nanos to this to facilitate communications between them.

Our main sensor will be our IMU. It comes with GPS tracking, an accelerometer, a gyroscope, and a barometric sensor. The GPS tracking in this unit is a bonus and not necessarily going to be used. These extra tracking mechanisms are just a bonus and allow us to gauge how fast the vehicle itself is moving as well as other useful data. We believe this data will be of use to us, we just don't exactly know how yet. Once we implement everything, we're 100% sure we will miss something and end up needing this data one way or another. We will also need a GPIO Expansion board in order to host all these various connecitons. 

For sound, this will be the main proponent of controlling the vehicle. There will be a microphone within one of the Jetson Nanos to power the entire thing. This speaker will sound verbal feedback, that way when you issue it a command, you know it received the command. Like when you say, "Forward!", it will reply saying, "moving forward". 

For image detection, once it detects an object in the camera sensor, it will move clear from it. We will put unique objects along its' path to try to get it to detect and identify these objects. Finally, once it sees a human face, it should be able to identify it and stop moving as soon as it detects a face.

The network switch will be there in order to facilitate communication between the two Jetson Nanos as well as the Raspberry Pi. This way, each Jetson Nano is responsible for one part of the AI work needed. The first Jetson Nano will run the AI model on image detection and be connected directly to the camera. The second Jetson Nano will process all the speech detection with the microphone attached to it. Both of these Jetson Nanos will send the information upstream to the Pi to process and react to this information. The Pi will directly process this information and change the speed of the motors and everything else basically.

Finally, to power the entire thing, we have a 40,000 mAh Power bank. This should be enough power to run the two Jetson Nanos as well as the Raspberry Pi. After heavy testing, we'll provide a rated battery time and how long the car can keep moving around a house.

To test the final product, we'll have it go around my house and make sure it avoids obstacles. We will also use voice commands to get it to move somehwat to where it goes, but we'll also rely a lot on the object detection for it to steer itself clear of obstacles.


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Jetson Nano (x2)|https://www.amazon.com/NVIDIA-Jetson-Nano-Developer-945-13450-0000-100/dp/B084DSDDLT/|$298.00|
| MicroSD Card (x2)|https://www.amazon.com/SanDisk-Extreme-microSDXC-Memory-Adapter/dp/B09X7BK27V/|$37.90|
| Network Switch|https://www.amazon.com/TP-Link-5-Port-Gigabit-Network-Switch/dp/B0863M7C1L/|$14.99|
| Small Ethernet Cables|https://www.amazon.com/Cat-Ethernet-Cable-Black-Connectors/dp/B01IQWGKQ6?th=1|$13.99|
| Car Chassis|https://www.amazon.com/LewanSoul-Mecanum-Chassis-Aluminum-Unassembled/dp/B093WDD9N5/|$36.99|
| SenseHAT|https://www.amazon.com/dp/B07W3WKMTG?psc=1&ref=ppx_yo2ov_dt_b_product_details|$29.99|
| RPI Camera|https://www.amazon.com/Arducam-Megapixels-Sensor-OV5647-Raspberry/dp/B012V1HEP4/|$29.15|
| GPIO Expansion Board|https://www.amazon.com/GeeekPi-Raspberry-Extension-Expansion-Screws/dp/B08C2XK25W|$9.99|
| Microphone|https://www.amazon.com/SunFounder-Microphone-Raspberry-Recognition-Software/dp/B01KLRBHGM/|$7.99|
| Mini-speaker|https://www.amazon.com/MakerHawk-Full-Range-Advertising-Connector-Separating/dp/B07GJ4GH67/|$12.99|
| Battery Bank|https://www.amazon.com/ROMOSS-40000mAh-Portable-Charger-External/dp/B087C23HPK/|$65.99|
| LED Strip|https://www.amazon.com/Backlight-DAYMEET-30-60in-Bluetooth-Control/dp/B098DVZZDQ|$10.99|
| Motor Drive|https://www.amazon.com/dp/B07GV8LKRZ?ref_=cm_sw_r_apan_dp_9CZPB6X213S2MV8F6YRN|$10.97|
| Raspberry Pi 4b|Owned|Owned|
| Taxes      |                                       | $45.22|
| Shipping | |$0|
|Total           |                                       | $590.63|
