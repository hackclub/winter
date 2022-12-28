---
name: "@praveenkumar1410"
project: "Voice controlled car"
---

## Summary

I'm going to build a arduino Voice Controlled Car. This car is designed to be controlled by voice commands. This car is built using arduino uno board,Beardboard(generic), DC motor 12V, micro motors, grippy wheels, Voltage Regulator, DC/Dc gate driver, Jumper wires(Generic), HC-05 Bluetooth module, Bluetooth Low Energy (BLE) Module (Generic),Texas Instruments Dual H-Bridge motor drivers L293D, Battery 12 V. The car operates by having a voice receiver box on it where it receives your voice commands. The car has a 50 foot radius from where it is initially place on the ground. The child interacts with the car by shouting out commands like "faster", "slower", "right", "left", and "stop". The child will be able to feel like they are in full control of the car by doing this, thus giving them the sense of being important. The child programs their own voice into the receiver so that only they can operate the car. The car has an emergency shut down when it reaches the boundary of the 50 foot radius. The child must also be within that 50 foot radius when shouting commands in order for the car to initiate the desired command. 

## FUTURE SCOPE
It is a miniature model for a voice controlled wheel chair( For differently abled people). They can easily controll the wheel chair though commands. In further development it can also function using neural commands(Direct impulse from the brain).

## Plan

1. Collect all the parts I need to make this project.The principle this toy concept was based on was voice recognition technology. 
2. Make a car with the components( DC motor 12V,  micro motors, grippy wheels, battery, Texas Instruments Dual H-Bridge motor drivers L293D).
3. Connect it with the Bluetooth module. 
4. Connect wires to the arduino uno board.
5. Connect Arduino with the Motor Shield and then connect all the wires coming from motors and servo.
6. Assemble all items.
7. Program the machine with arduino IDE to verify if everything is working as expected.
8. Prepare the machine for the first testrun by using ardiuino software.
9. Test the custom made dashboard by running the machine again using the dashboard generated g-code.
10. Complete the project if everything work as expected.
11. Connect the Raspberry pi4. The script on the Raspberry Pi that handles the processing of requests is written in Python.When the python script is activated, this opens the link between the Arduino Uno and the Raspberry Pi, thus enabling the car's motors and lights.This script also opens a communication link to a servo connected to pin 18 on the Raspberry Pi. This servo controls the turning mechanism in the car. The script uses PubNub to retrieve Alexa's requests and feeds these requests into a series of if statements. Depending on the command, the script will either send the command to the Arduino Uno through serial communication, tell the servo to turn the car, or return an unknown command error.

## Raspberri Pi4 SET UP

1.) Download the Raspberry Pi K'nex Car Control image.

2.) flash the 16 gb sd card with the image.

3.) Plug the monitor (via HDMI), mouse, keyboard, Arduino Uno (via USB), and WiFi adapter (if applicable) into the Raspberry Pi.

4.) Power on the Raspberry Pi

5.) When the Raspberry Pi finishes booting, it will ask you to connect to WiFi.

## Existing Project

https://create.arduino.cc/projecthub/mathwuy/voice-controlled-k-nex-car-f1b867?ref=similar&ref_id=443067&offset=4

## Budget

| Product                               | Supplier/Link                                                                                  | Cost   |
| --------------------------------------| -----------------------------------------------------------------------------------------------| ------ |
| HC-05/HC-06 Bluetooth Module          | https://amzn.to/2zoSc6v                                                                        | $42    |
| Arduino Uno                           | https://amzn.to/2yL24aA                                                                        | $27.60 |
| 12V DC Geared Motors 300 RPM (Q-2)    | https://amzn.to/2yJmtg4                                                                        | $30.99 |
| 12V Rechargeable Battery              | https://amzn.to/3dwWCH2                                                                        | $9.68  |
| L293D H-Bridge Dual Motor Driver IC   | https://amzn.to/2WmKsek                                                                        | $10.99 |
| Robot Chasis & Wheels                 | https://amzn.to/3bq6tNo                                                                        | $19.99 |
| Jumper Wires     (Q-20)               | https://amzn.to/2L8Xc1p                                                                        | $1.20  |
| Breadboard                            | https://amzn.to/2YM6YyS                                                                        | $11.98 |
| Raspberry Pi 4                        | https://bit.ly/3GaOxZY                                                                         | $47.15 |
| Total                                 |                                                                                                | $200.98|

No shipping costs are included because the prices included in the table is very similar to the prices in my local electronic store. I can confirm every item listed here is available in the store and don't need to ship them from overseas.
