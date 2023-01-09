---
name: "@Abubakarharuna10"
project: "Artificial Rescuer"
---

# Artificial Rescue

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


For the first day I will make all the neccessary equipment I would need to use.
For the next 2 or 3 days I will write the programming code and build the AI model .
The rest of the days will be spent constructing and testing the project.

I will use  NVIDIA Jetson Nano Developer Kit to run computer vision algorithms to detect people as the vehicle flies overhead. I will use an Edimax EW-7811Un 150Mbps 11n Wi-Fi USB Adapter that will allow me to connect to the Jetson Nano and monitor processes while the vehicle is in a flight setting. The CanaKit 5V 2.5A Power Supply will provide a stable power source while setting up the Jetson Nane. The Raspberry Pi Camera Module V2 will be mounted to the underside of the vehicle to capture video of the ground below. As for the Anker PowerCore 5000, this power pack was selected for its 2A output and compact size. Then, the PX4 Pixhawk on an autonomous drone or airplane will communicate with the Jetson Nano over a wired MAVLink connection  but you can use any autonomous drone or airplane in order to Mount your work on it.



## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi Camera Module V2.1  |https://www.amazon.com/Official-Raspberry-Pi-8-megapixel-XYGStudy/dp/B01G01JJJ0/ref=sr_1_2?crid=J818MRHDX9ED&keywords=Raspberry+Pi+Camera+Module+V2.1&qid=1672020961&sprefix=raspberry+pi+camera+module+v2.1%2Caps%2C355&sr=8-2| 34.35 |
| NVIDIA Jetson Nano Developer Kit |https://www.amazon.com/NVIDIA-Jetson-Nano-Developer-945-13450-0000-100/dp/B084DSDDLT/ref=sr_1_3?crid=1M6KCN83IMQGA&keywords=NVIDIA+Jetson+Nano+Developer+Kit+%28V3%29&qid=1672021508&sprefix=nvidia+jetson+nano+developer+kit+v3+%2Caps%2C762&sr=8-3| $149.00|
| Anker PowerCore 5000 | https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B072QD7F6N?th=1  | $34.95 |
| Edimax   |https://www.amazon.com/Edimax-EW-7611ULB-Wi-Fi-Bluetooth-Adapter/dp/B01KVZB3A4 | $12.11  |
| Total           |                                  | $230.41 |
