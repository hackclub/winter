# name: "@Captain-AJ"
# project: "An autonomous butler robot"

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
d. Pan/tilt systems for ultrasonic sensor and camera
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
 c. One will load food into the storage unit upon the robot’s arrival at various intake points. I plan to incorporate a fully automatic procedure in the future. When enabled, the robot will be summoned via Bluetooth.

Here is a list of functions: Button one: Instructs the robot to travel to a loading point. 

Button two: Activates autonomous reference tracking for station one.

Button three: Activates autonomous reference point tracking for station two.

Button four: Activates autonomous reference tracking for station three.

Button five: Instructs the robot to return to resting point.

Hand gestures: These can be used as an alternative to the buttons.

Control pad/arrow keys: For manual control.

When the robot recognizes one’s face, it will say hello and the user's name.

After a certain amount of time, the robot will ask if the user is satisfied. Upon asking thrice, the bot will autonomously return to it's resting space, but, if the “satisfied” button is pressed, it will return earlier.

When waiting to be loaded the bot will say, “waiting for load”, then, upon pressing buttons two-five, it will go to a specified drop-off point.

Programming:

Libraries:

Pixy2: https://github.com/charmedlabs/pixy2/tree/master/releases/arduino

For vision processing: OpenCV

I plan to connect the sensors through the following means:

Gyro: I2C
Ultrasonic: PWM
Pixy2 Camera: SPI
Speaker: Digital
Display: SPI

Extra Details:
I plan to read the Arduino Cookbook, ask engineering advisers questions relating to cases that are specific for my build, and research online.

Furthermore, I will also use the listed tutorials from dfrobot.com to assist me:

Explaining Computers:

[Raspberry Pi Devastator Robot #1](https://youtu.be/DyQxvfwQbTg)

[Raspberry Pi Devastator Robot #2](https://youtu.be/j6mglfhWZrQ)

[Raspberry Pi Devastator Robot #3: Camera](https://youtu.be/pK0XvjiP2qk)

educ8s.tv:

[Arduino Tank Robot Project using the Devastator metal chassis!](https://youtu.be/RTFSzXnlx4E)



| Product         | Supplier/Link                                         | Cost    |
| ------------- | ------------------------------------ | ------- |
| Devastator Tank Mobile Robot Platform (Metal DC Gear Motor) | https://www.robotshop.com/products/devastator-tank-mobile-robot-platform-metal-dc-gear-motor | $84.90 
| Charmed Labs Pixy 2.1 Robot Vision Image Sensor | https://www.robotshop.com/products/charmed-labs-pixy-21-robot-vision-image-sensor-rbc | $59.46 |
| Gravity Digital Speaker Module | https://www.robotshop.com/products/gravity-digital-speaker-module | $6.00 |
| Ultrasonic Sensor Scanner Kit (120°) | https://www.robotshop.com/products/ultrasonic-sensor-scanner-kit-120 | $29.99 |
| DFRobot Romeo BLE All-in-one Microcontroller (ATMega 328) | https://www.robotshop.com/products/dfrobot-romeo-ble-all-in-one-microcontroller-atmega-328 | $39.50 |
| Hobbypark 2pcs Aluminium Cross Wrenches | Amazon: https://a.co/d/11olJhw | $9.98 |
| Arduino Cookbook: Recipes to Begin, Expand, and Enhance Your Projects - 3rd Edition | Amazon: https://a.co/d/2JEbYvZ | $33.28 |
| Waveshare General 2-Inch 240×320 IPS LCD Display Module | https://www.robotshop.com/products/waveshare-general-2-inch-240320-ips-lcd-display-module | $12.35 |
| AstroAI Digital Multimeter | Amazon: https://a.co/d/gdRBUyS | $15.19 |
| Charmed Labs Pixy2 Robot Vision Pan & Tilt Add-On | https://www.robotshop.com/products/charmed-labs-pixy2-robot-vision-pan-tilt-add-on-rbc | $25.46 |
| SparkFun ICM-20948 9DoF IMU Breakout (Qwiic) | https://www.robotshop.com/products/sparkfun-icm-20948-9dof-imu-breakout-qwiic | $18.50 |
| USB BLE-Link Bluetooth Module | https://www.robotshop.com/products/usb-ble-link-bluetooth-module | $8.50 |
| Assorted Wires | https://www.robotshop.com/ / www.Amazon.com | $20 |
| Tax + Shipping |  $20.99 |
|Total | $399.08 | I will pay for the difference with my own funds.
