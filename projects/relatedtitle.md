---
name: "@relatedtitle"
project: "Home Security Drone"
---

# Home Security Drone

I want to build a home security system using a drone. The goal is to replace normal CCTV-based security with drones. This has a few advantages, such as being able to cover basically the whole perimeter of the house and perform surveilance, follow suspicious people and send alerts to homeowners. Using a drone for this instead of a normal CCTV camera has a lot of benefits, such as being cheaper than a lot of commercial CCTV solutions out there, making it harder for potential attackers to disable the cameras, and I think just having a drone hovering above the property will dissuade any potential intruders. It will use AI to detect people in the property and potentially verify who they are. It will report back to a base station to process the data and issue commands. Besides home security, this project could also be used to gather insight into traffic flow for businesses. Homeowners who are away could get a better look at what's going on by controlling the drone manually from a remote location if necessary. I think it is a really ambitious but exciting project. I am excited about it because it would be my first opportunity to tinker with drones and useful hardware applications. I've never written software to control hardware before, so I am excited about that. It would also be my first time applying computer vision to things that could actually be useful.

## Plan

I will use an Orange Pi (Raspberry Pi alternative) as the base station. The purpose of this is to process all the data from the drone, run the AI needed to detect people from the video feed, store and upload video footage to the cloud, and issue commands to the drone. The Orange Pi will also be in charge of hosting the interface for homeowners and allowing them to control the drone remotely. It will host a webserver to serve the interface (something like a router configuratiom interface, but modern). This will allow the homeowners to manage the system. The drone is a DJI Tello, this is the cheapest offering from DJI (a reputable drone brand), while it doesn't have the best quality or battery life, it has all the features needed for this project, and it's from a reputable brand, so it is more reliable. The plan is to write software that will record a designated flight path with possible guidance from the owner. After this, I will develop the software needed for the user interface (Node, Typescript, React) and the software needed for the person detection (Using the YOLO model and either Python, TS, or rust as the language). In order to get more battery life, I am considering creating a system to have the drone recharge wirelessly by returning to the base station and making a custom adapter to charge the battery wirelessly. I am not 100% sure if I will be able to do this part, since I don't have a lot of knowledge of electronics, but I want to use this as an opportunity to learn more. Otherwise, the drone would have to take short sessions many times a day. I have done a lot of research for this project, and I've determined that having to charge security systems is not really a problem for most people, although it would seem like it. There are a lot of commercial battery-operated security systems such as the Wyze Cam v3.

## Budget

(Note: The prices have been converted from MXN to USD, shipping and taxes already included)

| Product             | Supplier/Link                                                                         | Cost    |
| ------------------- | -------------------------------------                                                 | ------- |
| DJI Tello           | https://www.amazon.com.mx/DJI-TLW004-Distancia-Altura-Blanco/dp/B07CSH82SV            | $182.04 |
| Orange Pi 3 LTS 2GB | https://www.amazon.com.mx/Orange-Pi-AllWinner-computadoras-ejecutar/dp/B09WVDS579     | $58.71  |
| Total               |                                                                                       | $240.75 |
