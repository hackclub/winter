---
name: "@imdigitalashish"
project: "Zenith"
---


# Zenith

## Summary

It is a home automation tool that resembles IRON man Jarvis Assistant. I will create this from groud up including all codes and hook
it up with hardware to automate my common tasks and open source it so everyone can use it and fullfill their IRON man dream !

## Plan

I will use Raspberry Pi 4 as main controller of the board running RUST (for key performance areas) and Python (for AI / ML). With that
I proceed by connecting to hardware by wifi or wires or bluetooth to control and get data and make variety of features such as intruder detection (servo motor), turn on lights, integrate it with ChatGPT and my own chat model to communicate, make a beautifull GUI'S, create a server to communicate over call through Azure and control my room from anywhere in the world and to store stuff by just saying "JARVIS SAVE THIS FILE" to a harddrive using raspberry PI ( just like airdrop ) and incrementally add features time to time.

Features that I will be making:

1) Apple Airdrop feature with Harddrive and Raspberry PI
     ![image](https://user-images.githubusercontent.com/61198989/212450962-ae5cc8a8-1598-4218-b200-0ab6b40f259d.png)

3) Face Recognition Door lock using Servo Motor ( Here Raspberry PI send commands to Arduino with SSE Events ) and Potentiometer
    - For Doorlocking a raspberry PI Pico would be mounted on the door and connected through wifi
    - After the recognition has been done by the Main Raspberry PI, commands would be sent over wifi to raspberry PI pico
    - After receiving the commands, raspberry Pi pico will turn the servo motor to open the door !
5) Ultra sonic sensor for intruder detection and taking picture if it is not me
6) Advance chat assistant using Open AI API's and my own custom trained model
7) Controlling my LED Lights using Wifi 
8) Based on the pitch of the Chatbot LED Strips would be calliibrated
9) Temperature sensor ( INCLUDED IN UNO KIT ) for detecting accurate temperature that will be displayed on my webapp
10) Will create a web app that would be connected by Azure services, with Server sent events all the components can be controlled from anywhere in the world !



### Block diagram for AirDrop Feature

![image](https://user-images.githubusercontent.com/61198989/212450835-bbfc861a-3ce9-4767-b261-395c385db1c9.png)







## Budget
| Product             | Supplier/Link                         | Cost   |
| ------------------- | ------------------------------------- | ------ |
| Raspberry Pi 4      | https://amzn.eu/d/0p12Hmk             | $168.95|
| Ultra sonic sensors | https://amzn.eu/d/3Vz6ldi             | $3.62  |
| WIfi LED bulb       | https://amzn.eu/d/hj7LCNl             | $9.72  |
| Robotics kit PI     | https://amzn.eu/d/5qkD6j4             | $35.72 |
| LED Strips          | https://amzn.eu/d/4psSm6O             | $29.17 |
| Raspberry PI Pico   | https://amzn.eu/d/f5pxZ7Y             | $10.17 |
| LCD Display         | https://amzn.eu/d/fCHksqU             | $30.37 |
| Total               |                                       | $287.55|

## All prices are converted from INR TO USD




