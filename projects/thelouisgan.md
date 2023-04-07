---
name: "@thelouisgan"
project: "RC Amphibious Rover"
---

# RC Amphibious Rover

## Summary

As an engineer and electronics enthusiast, I am excited to propose an ambitious project: an Arduino-powered RC amphibious rover. This unique device will feature a modular design that allows it to traverse both land and water, making it highly versatile and adaptable to a wide range of environments.

The rover will be built using an Arduino microcontroller, a variety of sensors, and waterproof motors and hardware to enable it to move through water. I plan to use readily available components, however the entire project will be new and original, leaving myself to experiment with new concepts rather than following a strict tutorial.

## Plan

1. Research and gather all necessary components: This will include an Arduino microcontroller and RC controller, motors, sensors, and waterproofing materials such as sealant and plastic enclosures. Links to suppliers and estimated costs are be listed below.

2. Design the rover's chassis: Create detailed drawings of the rover's physical design, including dimensions and mounting points for all components.

3. Acquire materials and build the chassis: Purchase materials, such as plastic sheet or aluminum, needed to construct the rover's chassis and build it according to the design.

4. Waterproof the electronic components: Ensure through testing that only the waterproof components are submerged into water.

5. Install the electronic components: Mount the Arduino microcontroller, motors, and sensors onto the chassis and wire them together according to the circuit diagrams.

6. Write and upload the control software: Use the Arduino programming language to write the control software for the rover and upload it to the microcontroller.

7. Test the rover: Perform initial tests on the rover to ensure that all components are functioning correctly and that the rover can move on both land and water as intended.

8. Make adjustments and improvements: Based on the results of the initial tests, make any necessary adjustments or improvements to the rover's design or software.

9. Repeat testing and finalize the design: Perform final tests to ensure that the rover is fully functional and reliable, and make any final adjustments as needed.

**In addition to the previous plans if it is feasible and the initial structure of the boat is completed I will move on to the land side of things, with already owned wheels. The RC has a switch to toggle from water mode and land mode easily and will be developed further during the initial testing phase when all the components have been assembled to ensure optimum compatibility.**

## Component List
### Arduino Mega
Used for onboard peripheral management to control the motors and PWM from the RC input. Mega is used instead of other boards such as Uno or Nano because of the additional pinouts and flash memory size.
### RPi SD Card
I already have a Raspberry Pi, I just need an SD card in order to flash the OS. The Raspberry Pi will be used as an RTMP client such as OBS. It will get a live feed from the onboard GoPro that I will attach (I already own).
### Motor
The motor will be the source of velocity power and will need to be waterproof hence the underwater motor. It will be controlled with the RC input via the Arduino Mega.
### Brushless Driver
Used for controlling the above motor from the low current of Arduino PWM to the higher current level of less than 30 amps of the motor.
### Power Distribution Board
As the name suggests, this component will take the battery pack's incoming voltage and distribute it accordingly to the various components onbard the craft, namely the Arduino, servo rudder, and the motor.
### RC Transmitter
The remote control will serve as a input source for the user and will communicate with the Arduino via radio with the included radio reciever.
### Waterproof Servo
This servo will be attached with the rudder (included in manufacturing cost) and provide the yaw movement from the bow and stern of the ship. A key piece of information is that the motor will be stationary to minimise capsizing.
### LiPo Charger
This will be used to charge the LiPo battery that powers the enitre marine vessel.
### WiFi extender
A GoPro (already owned) will transmit a live RTMP feed to the user through Raspberry Pi, and since it is transmitted via WiFi, a WiFi extender will be needed to boost the range of the signal as the GoPro wifi signal after prior testing is weak.
### LiPo Indicator
This cheap (albeit very useful) LED display will be connected to the Arduino to be able to constantly monitor remaining battery to prevent the watercraft from being stranded. The user will also be able to see this information when operating remotely via RC through the GoPro feed, the display will be strategically placed in the viewing angle of the camera.

## Arduino Programming
Programming the Arduino will be done on an already owned PC with the stock Arduino IDE. The Arduino sketch will need to provide the following tasks:
- Servo Rudder
- Take PWM info in via RC RX
- ESC Motor Driver
- Variable Thrust
- Lighting (NeoPixel Effects)

## User Experience
> What would it look like to use the rover as a user?

The rover will be able to operate wirelessly through a radio RC that is similar to a FPV drone controller. Both the velocity and direction of the rover can be altered, as well as toggling the onboard LED lights for better visibility and visual appeal at nighttime. More details for the RC can be viewed in the linked website, but otherwise it has around 500m of range. Additionally, the user will also be able to view the rover as a first-person perspective with the onboard GoPro streaming RTMP to the Raspberry Pi on a monitor (already owned).

## Real Life Applications
In terms of applications, this rover has a wide range of potential uses. It could be used in search and rescue operations, where it could access areas that are difficult or impossible for human rescuers to reach, such as flooded areas or swamps. For example, follwing the semi-recent event of the Thailand cave rescue mission where few cave divers were stranded in an enlosed cave, this rover could be used to converse with the stranded divers and giving them support given further development of the rover such as full-body waterproofing. Additionally, the rover could be used in scientific research, such as for collecting water samples or monitoring aquatic habitats. The rover could also be used in the field of exploration, such as inspecting and traversing hard to reach areas like underground caves, rocky terrains, or else remote island.

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Ardunino Mega   | [Mega has more pinouts for ease of use](https://my.cytron.io/p-arduino-mega-2560-r3-main-board?r=1&gclid=Cj0KCQiAtvSdBhD0ARIsAPf8oNnrMcOHuTHVE5k1_UPj6m38fndDn4SqnQ5hypFAO70cqzx0LU0fe7IaAiLbEALw_wcB) | $45.76  |
| RPi SD Card     | [For RC controller and WIFI RC comms](https://shopee.com.my/SanDisk-Extreme-Micro-SD-A2-U3-Class-10-MicroSD-Memory-Card-(256GB-128GB-64GB-32GB-16GB)（Free-adapter）-i.734634834.19707067389?sp_atk=6083fde7-937b-4a49-8737-218e93cb9036&xptdk=6083fde7-937b-4a49-8737-218e93cb9036)   | $17.94 |
| Motor          | [1000KV Underwater Brushless Motor](https://shopee.com.my/1000KV-Underwater-Brushless-Motor-Clockwise-with-with-4-Blade-Propellers-12-24V-Waterproof-Electric-Motor-Drive-Engine-f-i.143578305.17025288177?sp_atk=2e923433-2610-4622-bc3e-8e5c7a6737f4&xptdk=2e923433-2610-4622-bc3e-8e5c7a6737f4)     | $13.35 |
| Brushless Driver| [1pcs FVT LITTLEBEE BLlheli SPRING 30A](https://shopee.com.my/1pcs-FVT-LITTLEBEE-BLlheli-s-SPRING-30A-ESC-2-6S-Supports-Mulitshot-DSHOT-Oneshot42-OneShot125-Multicopter-i.53025383.11824286967?xptdk=8e1f01dd-b53c-4221-a7ec-f2d40d09743e) | $5.72  |
| Power Distribute| [Power Distribution Board with BEC 12V](https://shopee.com.my/-RuiSurplus-Quadcopter-Power-Hub-Power-Distribution-Board-PDB-with-BEC-5V-12V-for-FPV-i.161780471.12129693257) | $2.38  |
| Battery Pack    |  [1500mah 120C RC Battery (Li-Po)](https://shopee.com.my/Local-Stock-2PCS-RC-Toys-Lipo-Battery-4S-14.8V-1100mAh-1500mah-120C-RC-Battery-with-XT60-Plug-for-FPV-Drone-Helicopter-Airplane-Quadcopter-Model-Batery-i.483416116.13061198428?sp_atk=db8af79e-6865-4551-a84d-bd23192a49e2&xptdk=db8af79e-6865-4551-a84d-bd23192a49e2)      | $31.34 |
| RC Transmitter  | [FlySky 6CH Radio Transmitter+ Reciever](https://my.cytron.io/p-flysky-6-channels-rc-radio-transmitter-with-fs-ia6b-receiver-mode-2?r=1&gclid=CjwKCAiA2fmdBhBpEiwA4CcHzVg0RsPkoSCj2VBQt4ItYtJzifDq2A5conm-IU39qsiY6AtjoNBUgBoCjX8QAvD_BwE)| $66.35 |
| Waterproof Servo| [25KG Digital Servo Full Metal Gear](https://shopee.com.my/25KG-Digital-Servo-Full-Metal-Gear-High-Torque-Waterproof-for-RC-Car-Crawler-Rob-i.160359531.6320208157?sp_atk=ce3dd8b4-7732-43e4-ba6d-6fc723333ffe&xptdk=ce3dd8b4-7732-43e4-ba6d-6fc723333ffe)    | $11.75 |
| LiPo Charger    | [Multi-Function LIPO Balance Charger](https://my.cytron.io/p-multi-function-lipo-balance-charger-13853?r=1&gclid=CjwKCAiA2fmdBhBpEiwA4CcHzVSQyTVOkSbv0fAxmYCAQzXVhtO9v96U-Oc5-X5TA4vxamAtvJb6jhoCG2gQAvD_BwE)   | $20.36 |
| WiFi Extender   | [For extending GoPro video feed to RC](https://shopee.com.my/XiaomiMi-Wi-Fi-Range-Extender-Pro-Global-Version-i.139641550.2909970792?sp_atk=a251e728-8db8-4e65-9099-442717b2ec20&xptdk=a251e728-8db8-4e65-9099-442717b2ec20)  | $13.50  |
| LiPo Indicator  | [LiPo Voltage Indicator LED Display](https://my.cytron.io/p-lithium-battery-voltage-indicator-led-display)    | $1.67   |
| LED Decorations | [WS2812b Serial Adressable LED Strips](https://shopee.com.my/Xnbada-1m-2m-3m-4m-5m-WS2812B-30Led-m-RGB-Led-Strip-WS2812-5050SMD-Black-White-Board-i.116626746.2196406413?xptdk=b20ca097-7e87-4294-8843-972f3b72615b)  | $7.18   |
| Casing +Filament| Estimated cost for 3D Printing[^1]    | $11.44  |
| Total before tax| BEFORE Tax + Delivery Fees            | $237.30 |
| Delivery Fees   | Shopee: $1.26 Per Item x12 items =    | $15.12  |
| TOTAL COST      |                                       | $263.86 |

[^1]:*(I don't have a 3D Printer so I will have to rent)*
Prices are converted from MYR to USD from Google.. Please allow +- few dollars differ

Thank you so much to everyone at the HackClub and the community for this amazing opportunity!
