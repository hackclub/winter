---
name: ["@SiruX21", "@Look-Its-Sky", "@RartedRussian", "@Cimbobimb"]
project: "AI Powered Self-Driving Delivery System"
---
# AI Powered Self-Driving delivery system
## Summary

We plan on making a remote controlled car that can drive itself to and from different locations in a small web-based interface. This interface would ask for you to input a destination and it will go there with a small little pathfinding algorithim that utilizes various APIs. The car will also hold items in a 3D-printed encasing that automatically closes and opens.

## Plan

For the base RC vehicle, we are utilizing an off the shelf self-assembly frame kit to house the components. We will then connect the motors that come with the frame to our Raspberry Pi. Ater we do this, we will then mount our various sensors. The important sensors that have to be mounted in a visible area would be our ultrasonic, camera, and LIDAR sensor. The ultrasonic sensor generates high frequence sound then basically echolocates objects. This is similar to how a bat works in echolocation, except we can't hear the sound with our ears. Through this way, we are able to add one way of object detection. The next form of object detection we are implementing is a LIDAR sensor. This sensor fires invisible lasers all around the environment and generates a map of objects around it. We'll have this sensor up on the front alongside our ultrasonic sensor. The last most important sensor is of course the camera sensor. This sensor will use AI in order to identify objects and give them a specific name. This will also be used to facilitate facial recognition through TensorFlow. 

The next part of our sensors to facilitate the car is an IMU, or an inertia measuring unit. We found an extremely reliable part that integrates this and much more. It comes with GPS tracking, an accelerometer, a gyroscope, and a barometric sensor. The GPS tracking in particular is the most important part as it will allow us to pinpoint the location of the car. We will also need a GPIO Expansion board in order to host all these various connecitons. 

For sound, we intend to use it to signal warnings to people around the car. This will be facilitated by the mini-speakers we are mounting to the car. This speaker will sound, "Turning Left, Turning Right", and so on. Then, there will be a microphone attached to the Raspberry Pi in order to assist it with speech recognition. This speech recognition will be used as a safety feature. For example, whenever the car is going somewhere where it really shouldn't be, anyone can just yell, "STOP!", and the car will stop.

For the delivery part, we will include servos in order to unload the items. Whilst the chassis itself has housing for the parts we listed, it absolutely cannot hold anything. Therefore, we are 3D Printing various parts in order to create a container around the chassis. This will work in conjunction with our servos to unload things and open/close a lid. We will also have an LED strip in order to light up the car when its' night.

Next, we will have a 4G and Sim Card Data adapter for the Pi. This will allow it to connect to the internet and connect to our computer. In order to keep a constant IP, it will connect to a VPN hosted on the Computer through OpenVPN. This will allow it to send all its' data upstream and recieve instructions from the computer. It will also allow for us to track the car in conjunction with the GPS module. 

Finally, to power the entire thing, we have a 40,000 mAh Power bank.

As for testing whether or not our project is success, we are going to try to deliver a phone from my house to a park that's roughly 2 blocks away. Not a lot of cars go along this road and it's short enough that we can monitor the car as it goes, but long enough that it isn't simply going in a straight line. If it's able to do this, it's a complete success.

Extra note on software:

We plan on writing out all the software backend for this project. We will make a small little cross-platform website on where you can manage your delivery and see the real time location of the car. It will include various options to the control the car such as just automatically dropping it off at the destination, or requiring facial confirmation and actual manual control of the car. This means that we will coordinate and collect all the data on the sensors, process it, then send an action. To do this, we will need a computer outside of the Raspberry Pi to process all these intensive calculations and data. We plan on running all the calculations an outside CPU for this project. It's absolutely possible however to do all of these hosted on the Pi, we just think it's going to be absolutely detrimental to the experience. This system will act as the brain of the computer rather than the Pi because we simply cannot mount this system in an RC car without having Tesla style batteries. If need be, the computer components can be taken away from this project and we can instead host everything on the Pi. This will however necessitate a huge cutdown in the scope of the project and instead revolve around self-driving within a house.

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| AMD Ryzen 9 5950x | https://www.microcenter.com/product/630282/amd-ryzen-9-5950x-vermeer-34ghz-16-core-am4-boxed-processor-heatsink-not-included | $499.99 |
| DDR4 2 x 16GB |https://www.amazon.com/dp/B07PV7GL6C?tag=pcpapi-20&linkCode=ogi&th=1| $65.97 |
| SSD|https://www.amazon.com/dp/B08CKFDPJ3?tag=pcpapi-20&linkCode=ogi&th=1|$46.99|
| Car Chassis|https://www.amazon.com/LewanSoul-Mecanum-Chassis-Aluminum-Unassembled/dp/B093WDD9N5/|$36.99|
| 4G LTE Data Adapter|https://www.amazon.com/AZURAOKEY-Wireless-150Mbps-Adapter-Hotspot/dp/B0B99L6QF|13.99|
| LIDAR Sensor|https://www.amazon.com/Single-Point-Compatible-Rasppbarry-Communication-Interface/dp/B088NVX2L7/|$25.99|
| Ultrasonic Sensor|https://www.amazon.com/XiaoR-Geek-Ultrasonic-Distance-Raspberry/dp/B07B94C7KT|$9.99|
| IMU Board|https://www.amazon.com/BerryGPS-IMUv3-Raspberry-Accelerometer-Magnetometer-Barometric/dp/B072MNBC9M|$71.20|
| RPI Camera|https://www.amazon.com/Arducam-Megapixels-Sensor-OV5647-Raspberry/dp/B012V1HEP4/|$9.99|
| GPIO Expansion Board|https://www.amazon.com/GeeekPi-Raspberry-Extension-Expansion-Screws/dp/B08C2XK25W|$9.99|
| Microphone|https://www.amazon.com/SunFounder-Microphone-Raspberry-Recognition-Software/dp/B01KLRBHGM/|$6.99|
| Mini-speaker|https://www.amazon.com/MakerHawk-Full-Range-Advertising-Connector-Separating/dp/B07GJ4GH67/|$12.99|
| Servos|https://www.amazon.com/Adeept-Digital-Helicopter-Arduino-Raspberry/dp/B0B1TS1NNP|$19.99|
| Battery Bank|https://www.amazon.com/ROMOSS-40000mAh-Portable-Charger-External/dp/B087C23HPK/|$52.69|
| LED Strip|https://www.amazon.com/Backlight-DAYMEET-30-60in-Bluetooth-Control/dp/B098DVZZDQ|$10.99|
| Raspberry Pi 4b|Owned|Owned|
| 3D Printer (Owned through School| Owned | Owned|
| Motherboard |Owned|Owned|
| PSU |Owned|Owned|
| Taxes      |                                       | $68.74|
| Shipping | |$0|
|Total           |                                       | $963.50 |
