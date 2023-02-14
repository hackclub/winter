---
name: "@Captain-AJ"
project: "Autonomous Butler Robot"
---

# Project Name
A.L.F.R.E.D. Butlerbot

## Summary

I plan to build an Arduino controlled autonomous robot butler named A.L.F.R.E.D. (Advanced, Little, Fit, Robot, Education, Device) that can be summoned at the press of a 
button and deliver items. I am excited because this practical project has been on my list for sometime now. 
After a long part search, my efforts to build this contraption summed in the listed Devastator robot kit. The set includes treads, metal motors, an aluminum tank chassis, 
and a battery compartment.
All coincides with my desire to apply computer and mechanical engineering concepts to develop a computing module in physical excellence.

## Plan

1. Order kit and required parts.
2. Read a sizable amount of Arduino Cookbook to become well endowed with appropriate knowledge.
3. Build the kit according to the instructions: 
a. Assemble the tracks with gear components. 
b. Assemble the robot's chassis and attach the Romeo BLE.
c. Attach all sensors to the body, e.g., Ultrasonic sensor, speaker, etc.
d. Pan/tilt systems for camera.
e. Wire all components 
f. Attach the food storage unit.

4. Programing (Python, C language):
a. PixyCamera for color and facial recognition.
b. Ultrasonic sensor for object detection and avoidance.
c. Speaker for communication.
d. Display for facial expressions and personality.
e. Gyroscope for absolute direction capabilities, e.g. field-oriented drive.
f. Unify sensor control by programming manual and autonomous control functions.

5. Operation
 a. I plan to make an application with manual and autonomous control options using PyQT5. One would make the robot move to points of reference using the tracking system (Pixy2 and OpenCV).
 b. I intend for the application to be quite simple. The control pad will be on the left and buttons on the right, with icons or numbers for the corresponding actions. For communication, I aim to use Bluetooth. Also, there will be an option to alter background color. 
 c. One will load food into the storage unit upon the robot’s arrival at various intake points. A fully automatic procedure is intended for the future. When enabled, the robot will be summoned via Bluetooth.

#### Function List: 

Button one: Instructs the robot to travel to a loading point. 

Button two: Activates autonomous reference tracking for station one.

Button three: Activates autonomous reference point tracking for station two.

Button four: Activates autonomous reference tracking for station three.

Button five: Instructs the robot to return to resting point.

Hand gestures: These can be used as an alternative to the buttons.

Control pad/arrow keys: For manual control.

When the robot recognizes one’s face, it will say hello and the user's name.

After a certain amount of time, the robot will ask if the user is satisfied. Upon asking thrice, the bot will autonomously return to it's resting space, but, if the “satisfied” button is pressed, it will return earlier.

When waiting to be loaded the bot will say, “waiting for load”, then, upon pressing buttons two-five, it will go to a specified drop-off point.

### Programming:

Libraries:

Pixy2: https://github.com/charmedlabs/pixy2/tree/master/releases/arduino

For vision processing: OpenCV

#### Sensor connections (planned):

Gyro: I2C
Ultrasonic: PWM
Pixy2 Camera: SPI
Speaker: Digital
Display: SPI

### Extra Details:
Resources: Arduino Cookbook, engineering advisers, online research.

Furthermore, I will also use the listed tutorials from dfrobot.com to assist me:

[Raspberry Pi Devastator Robot #1](https://youtu.be/DyQxvfwQbTg)

[Raspberry Pi Devastator Robot #2](https://youtu.be/j6mglfhWZrQ)

[Raspberry Pi Devastator Robot #3: Camera](https://youtu.be/pK0XvjiP2qk)

[Arduino Tank Robot Project using the Devastator metal chassis!](https://youtu.be/RTFSzXnlx4E)


## Budget


| Product         | Supplier/Link                                         | Cost    |
| ------------- | ------------------------------------ | ------- |
| Devastator Tank Mobile Robot Platform (Metal DC Gear Motor) | https://a.co/d/dMECYbL | $94.90 
| Charmed Labs Pixy 2.1 Robot Vision Image Sensor | https://www.robotshop.com/products/charmed-labs-pixy-21-robot-vision-image-sensor-rbc | $69.95 |
| Gravity Digital Speaker Module | https://www.robotshop.com/products/gravity-digital-speaker-module | $6.00 |
| ELEGOO 5PCS HC-SR04 Ultrasonic Module Distance Sensor Kit | https://a.co/d/bACB9fh | $9.99 |
| Bolsen 10PCS/LOT Ultrasonic Sensor Mounting Bracket for HC-SR04 | https://a.co/d/6Tg1lYd | $6.49 |
| DFRobot Romeo BLE All-in-one Microcontroller (ATMega 328) | https://www.robotshop.com/products/dfrobot-romeo-ble-all-in-one-microcontroller-atmega-328 | $39.50 |
| Hobbypark 2pcs Aluminium Cross Wrenches | Amazon: https://a.co/d/11olJhw | $9.98 |
| Arduino Cookbook: Recipes to Begin, Expand, and Enhance Your Projects - 3rd Edition | Amazon: https://a.co/d/2JEbYvZ | $33.28 |
| Waveshare General 2-Inch 240×320 IPS LCD Display Module | https://www.robotshop.com/products/waveshare-general-2-inch-240320-ips-lcd-display-module | $12.35 |
| AstroAI Digital Multimeter | Amazon: https://a.co/d/gdRBUyS | $15.19 |
| Charmed Labs Pixy2 Robot Vision Pan & Tilt Add-On | https://a.co/d/1Tf8JYl | $29.90 |
| *SparkFun ICM-20948 9DoF IMU Breakout (Qwiic) | https://a.co/d/16kl0Um | $15.30 |
| *SparkFun Qwiic Cable Kit | https://a.co/d/f7vqYIK | $10.70 |
| USB BLE-Link Bluetooth Module | https://www.robotshop.com/products/usb-ble-link-bluetooth-module | $8.50 |
| ELEGOO 120pcs Multicolored Dupont Wire 40pin Jumper Wires | Amazon: https://a.co/d/hspaKwv |  $6.98 |
| HMROPE 100pcs Cable Zip Ties | Amazon: https://a.co/d/eVwSuSM | $5.49 |
| 3M Scotch Electrical Tape | Amazon: https://a.co/d/0MQiqZv | $2.29 |
| Tax + Shipping |  | $19.52 |
|Total | | $399.31 | I will pay for the difference with my own funds.
|*I purchased the SparkFun IMU and the SparkFun Qwiic Cable Kit at a discounted price for both. |



#### Items to be purchased using grant funds (planned):

| Product         | Supplier/Link                                         | Cost    |
| ------------- | ------------------------------------ | ------- |
| Devastator Tank Mobile Robot Platform (Metal DC Gear Motor) | https://a.co/d/dMECYbL | $94.90 
| Charmed Labs Pixy 2.1 Robot Vision Image Sensor | https://www.robotshop.com/products/charmed-labs-pixy-21-robot-vision-image-sensor-rbc | $69.95 | 
| Gravity Digital Speaker Module | https://www.robotshop.com/products/gravity-digital-speaker-module | $6.00 |
| DFRobot Romeo BLE All-in-one Microcontroller (ATMega 328) | https://www.robotshop.com/products/dfrobot-romeo-ble-all-in-one-microcontroller-atmega-328 | $39.50 |
| USB BLE-Link Bluetooth Module | https://www.robotshop.com/products/usb-ble-link-bluetooth-module | $8.50 |
| Waveshare General 2-Inch 240×320 IPS LCD Display Module | https://www.robotshop.com/products/waveshare-general-2-inch-240320-ips-lcd-display-module | $12.35 |
| Tax + Shipping |  | $16.19 |
| Total |  | $247.39 |