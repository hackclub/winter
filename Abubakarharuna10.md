---
name: "@Abubakarharuna10"
project: "Artificial Rescuer"
---

# Project Name
Artificial Rescue

## Summary

With the increasing threat of climate change, greater populations and consequently, more extreme environmental events
the need for better emergency rescue services is paramount
As time moves forward, natural disasters will continue to wreak havoc on cities and counties around the world, 
causing many people to die. Bolstering the power of search and rescue teams with autonomous UAVs that can identify people
in disaster relief zones could significantly reduce the impact tornadoes, earthquakes, tsunamis, floods, etc...
My solution to strengthening search and rescue operations is to outfit an autonomous unmanned aerial vehicle (UAV) 
with a computer vision system that detects the location of people as the vehicle flies over ground. The powerful neural-network capabilities
of the Jetson Nano Dev Kit will enable fast computer vision algorithms to achieve this task. Joseph Redmon's YOLOv3 algorithm will be used 
to do the actual object-detection (people) in the camera's view While the UAV is flying a waypoint mission using ArduPilot, PX4, or any other autonomous flight control stack, the absolute location of people in the camera view can be calculated based on the altitude, orientation, and GPS location of the UAV.

## Plan

I will use  NVIDIA Jetson Nano Developer Kit to run computer vision algorithms to detect people as the vehicle flies overhead along with an Edimax EW-7811Un 150Mbps 11n Wi-Fi USB Adapter that will allow me to connect to the Jetson Nano and monitor processes while the vehicle is in a flight setting then the CanaKit 5V 2.5A Power Supply will provide a stable power source while setting up the Jetson Nano and the Raspberry Pi Camera Module V2 will be mounted to the underside of the vehicle to capture video of the ground below then Anker PowerCore 5000 This power pack was selected for its 2A output and compact size. then the PX4 Pixhawk on an autonomous drone or airplane will communicate with the Jetson Nano over a wired MAVLink connection.

1) Having requirements to use in this project.
2) Hardware components,
  -NVIDIA Jetson Nano Developer Kit
  -Edimax EW-7811Un 150Mbps 11n Wi-Fi USB Adapter
  -CanaKit 5V 2.5A Power Supply
  -Raspberry Pi Camera Module V2
  -Anker PowerCore 5000
   -PX4 Pixhawk
3) Implimentation

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi Camera Module V2.1  |https://www.amazon.com/Official-Raspberry-Pi-8-megapixel-XYGStudy/dp/B01G01JJJ0/ref=sr_1_2?crid=J818MRHDX9ED&keywords=Raspberry+Pi+Camera+Module+V2.1&qid=1672020961&sprefix=raspberry+pi+camera+module+v2.1%2Caps%2C355&sr=8-2| 34.35 |
| NVIDIA Jetson Nano Developer Kit |https://www.sparkfun.com/products/16271| $149.00|
| Anker PowerCore 5000 | https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B072QD7F6N?th=1  | $34.95 |
| Edimax   |https://www.amazon.com/Edimax-EW-7611ULB-Wi-Fi-Bluetooth-Adapter/dp/B01KVZB3A4 | $12.11  |
| Total           |                                  | $230.41 |
