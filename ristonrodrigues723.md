---
name: "@ristonrodrigues723"
project: "Iot enabled home automation system"
---

# Home automation

## Summary

What are you going to build? What does it do? Why are you excited to build it?
Home automation is an increasingly important part of connected house. It makes daily life easier by automatically performing small and simple tasks. Unfortunately, the various brands on the market generally only offer expensive and not very flexible product range. i want to work on a solution which makes home automation accessible to all by using a raspberry pi, ESP32 and some sensors and actuators.

## Plan

1) centralautomation hub using rasberry pi and apache server -first inplan to develope a central  hub using rasberry pi and apache server  which will connect to the other modules over the web using wifi and esp 32 boards
- will make use of -
1 x |RPI4-MODBP-8GB|-the main rasberry pi board.
1 x | Orange Raspberry Pi 4 Advance Kit   |- will be used to set up rasaberry pi, provide it with necessary power and connect it with the software and wifi, 
1 x | 40 Pin Red GPIO Extension Board for Raspberry Pi|- will enable me to easily connect the parts from rasbrerry pi kit on the board without harming the rasberry pi board

they all wil make use of esp 32 boards
 boards vwill be reused for newer modles as the modules are more compared to the esp boards the modules are more.
 
 modules can be increased or decresed as per need,time  and avaibility of hardware components and further modules can be easily added in the future.
 they will be connected o the central hub built using rasberry pi and can be accessed through web for now and can be manipulated theough mobile phones in the future.
 
 As all the codes are open-source, to enable me to appropriate the modules in future.
 
 i will be refrancing the following builds-
 1)  https://www.instructables.com/Free-Smart-Home/
 2)  https://www.instructables.com/Raspberry-Pi-Home-Automation-Control-lights-comput/
 3)  https://www.instructables.com/Home-Automation-4-5-6/
 4)  https://www.instructables.com/Smart-Home-by-Raspberry-Pi/
 5)  https://www.instructables.com/DIY-Cheap-Safety-Alarm-System-W-Raspberry-a-Smarte/
 
the following parts will be used again and again: throughout the building procdess:
a)|Plusivo Soldering Kit with Multimeter (EU Plug) | - soldering the wires into boards , the sensors to esp 32 modules and sensors together also will be used to do the process of removing soldring
b)| Orange Raspberry Pi 4 Advance Kit   |  mainly used in the central automation hub but can also be used for other modules.
c)| 20 CM 40 Pin Dupont Cable Male/Male, Male/Female, Female/Female Cable Combo |- the wires to be used theoughout the module
d)| Tactile Push Button Switch set | buttons to be used in the esp 32 module enabled circuts
e)| GLUN 11 mm Transparent HOT MELT glue sticks - to be used in the hot glue gun.
f) cardboard and plywood sheets/pieces- already owned:- creating containers for the modules and the wooden bin in petbfood module.
g)| ApTechDeals 60W /100 Watt Dual Watt Glue Gun |- glueing together the wooden and cardboatrd pieces and cases.
i want to  develop different modules such as:

1)Control camera and security module- will be used to develope a camara module which can be put on the house gate for security gate 

will make use of one of: 
- 1 x| D10 3.7V Rechargeable Lithium ion Battery Power Bank Cell , these cells will also be used on the modules that will be placed outside,
- 1 x| ESP32-CAM-MB MICRO USB Download Module for ESP32 CAM Development Board|-the main camara to be connected to it,
- 1 x| I2C ADS1115 16 Bit ADC 4 channel Module with Programmable Gain Amplifier | will be used to check status of camera and the gate ,
- 1 x | MC-38 Wired Door Window Sensor Magnetic Switch Home Alarm System |, will be connected to the esp 32 board will be placed next to the gate bto check opening closing status.



2)Module Outside Station- ie. unit for water tank,  weather level and to check its lid status

The purpose of the outside station is designed to measure the humidity of the air, the temperature and the level of your water tank. Each variable is sent to the website.

will use the following:
- 1 x | ESP32-CAM-MB MICRO USB Download Module for ESP32 CAM Development Board|
- 1 x Battery  | D10 3.7V Rechargeable Lithium ion Battery Power Bank Cell
- 1 DHT22 : Sensor for humidity and temperature 
- 1 x | HC-SR04-Ultrasonic Range Finder |: Ultrasonic sensor for the level of the watertank (
- Some “Dupont” wires x | 	Female to Female DuPont Line 40 Pin 30cm |- to connect the components together
- 1 x |37-1K - Resistance:1kohm |- will be conne cted in the module for resistenc.
 

3) Module Light:Lighting management-This module allows you to control as many lights as you want. There are two types of control : ON/OFF with a relay or a PWM to dim the brightness between 0 and 100%.

will make use of -
- 1x ESP32 : one board for each place (up to 4 lights command by ESP32) 
- 5V 2 Channel Relay Module |- will be used here to enable us to provisde the necessary amphere of current to the dimmer. : a double relay by light.
- Dimmer - https://www.amazon.fr/variateur-lumière-RobotDyn-...
- 4 x | Generic E-DIMMER AC 50-220V 2000W SCR Triac Electric Voltage Regulator Temperature/Motor Speed
- Controller Light Dimmer X4|  each dimmer support a single bulb and about 4 such bulbs will be connected to to the esp 32 board to be used.
- light bulbs led x4 owned

4)Module Central Heating- The purpose of the "Heating" module is to replace the conventional thermostat of a heating system with a remotely controllable thermostat. The web interface makes it possible to modify the different setpoints, the operating hours and to trigger the system remotely.

An additional option also makes it possible to control a ventilation system in the case of a hot air heater. This ventilation can be used to better circulate the air in the house

- 1 x ESP32- main dev board.
- 1 x | 5V 2 Channel Relay Module |- wi
- 1 x | Tactile Push Button Switch set | will be connected to the circut so if the  circut fails we have a way to stop it ie stop individual components that will chang e humudity , heat , temperature using different buttons.
- 1 x |37-1K - Resistance:1kohm |
- 1 x DHT22 sensor for humidity and temperature -sense thwe humidity and temperature of the room provide input to the board
- 1 x 5V Power Supply-power supply for our circut

- 1 x | 20 CM 40 Pin Dupont Cable Male/Male, Male/Female, Female/Female Cable Combo |- connect the circut together - later will be soldered together using
- 1 x |Plusivo Soldering Kit with Multimeter (EU Plug) | - this kit will be used throughout the project.

5)Pet food management- 

- 1 x ESP32 board- main part of the module to connect to wifi 
- HX711 module with a strain gauge -owned.
- 1 x A wooden bin - will be created using the wood i have at home and will be joined using -
- 1 x | GLUN 11 mm Transparent HOT MELT glue sticks       |-will be used in the glue gun to stick the food dispense box together and  cases with wood.
- 1 x| ApTechDeals 60W /100 Watt Dual Watt Glue Gun | glue gun to stick wood and cardboard parts together
- 1 x | 	Standard 5V 3A Power Supply with 5.5mm DC Plug|- power supply adapter
- 1 x | D10 3.7V Rechargeable Lithium ion Battery Power Bank Cell | -An external battery to connect to the ESP32 

6)Remotely controlled electric shutters module-The purpose of the "Electric Shutters” module is to allow the user to maintain control over the installation of electrical shutters. In addition to traditional use, everyone will now be able to decide to control their shutters remotely. 

will make use of the following parts:
- 1 x Electrical shutters- already owned
- 1 x ESP32 board- main part of the module to connect to mifi and carry out processing
- 1 x | D10 3.7V Rechargeable Lithium ion Battery Power Bank Cell | -An external battery to connect to the ESP32 
- 1 LDR5516 photoresistance for brightness
- 1 x| 2 Channel Relay Module, 30A with Optocoupler, Isolation 5V Supports, High and Low Triger |- to control shutter functions will be connected to the esp 32.
- 1 x 1k/resistance-1kohm/dp/2784369):resistance 1000 Ohms
- 1 x | GL-12 840 Points Solderless Breadboard  |- where we will mount the circut and components of the module
- 1 x | 	Female to Female DuPont Line 40 Pin 30cm | -Some “Dupont” wires -used to cponnect breadboards to other parts and esp 32 modules.
- 1 x | D10 3.7V Rechargeable Lithium ion Battery Power Bank Cell | -An external battery to connect to the ESP32 

7)Gas detection module- in the kitchen 
 
will make use of:
- 1 x ESP32 board- main part of the module to connect to mifi and carry out processing
- 1 x | GL-12 840 Points Solderless Breadboard  | - the breadbords will be used here and one other module,
- 1 x | 20 CM 40 Pin Dupont Cable Male/Male, Male/Female, Female/Female Cable Combo | will connect the breadboards to other parts such as sensors and electronic components and will be uised in different modules.
- 1 x | MQ-2 Smoke LPG Butane Hydrogen Gas Sensor Detector Module |- gas sensor to sense 
- 1 x | Tactile Push Button Switch set | buttons will be  connected in the module to stop the module  in case of server failure.
- 1 x | D10 3.7V Rechargeable Lithium ion Battery Power Bank Cell | -An external battery to connect to the ESP32 
- 1 x |Flame Sensor Module |- connected to the esp 32 board.


8) garden module -used to pay attention  to soil condition and weather in a garden

will make use of:
- 1 x| Electronics ESP32 ESP-32 ESP-32S ESP 32 Development Board CP2102 WiFi Bluetooth Ultra-Low Power Consumption Dual Core  |
- 1 x  Waveshare Moisture Sensor -to measure moisture in the environment will connect to esp 32
- 1 x | GL-12 840 Points Solderless Breadboard  |- for mounting the componemnts - wires ,sensors
- 1 x | Female to Female DuPont Line 40 Pin 30cm | - used to connect the circut
- 1 x | GL-12 840 Points Solderless Breadboard |
- 1 x | Raindrops Detection Sensor Module	 |- used to me
- 2 x |Soil Moisture Meter, Soil Humidity Sensor, Water Sensor, Soil Hygrometer for Ardunio  | will be positioned in the garden in different will be connected to esp 32 boards
 
 
## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.
| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| ApTechDeals 60W /100 Watt Dual Watt Glue Gun | [Supplier/Link                   ](https://www.amazon.in/gp/product/B076CRTD7H/ref=ox_sc_act_image_2?smid=A2K5VGK3OPN02U&th=1)      | $7.86   |
| GLUN 11 mm Transparent HOT MELT glue sticks       |    https://www.amazon.in/gp/cart/view.html?ref_=nav_cart  | $2.24   |
| Generic E-DIMMER AC 50-220V 2000W SCR Triac Electric Voltage Regulator Temperature/Motor Speed Controller Light Dimmer X4| https://www.amazon.in/50-220V-Electric-Regulator-Temperature-Controller/dp/B07GXG82HC/ref=sr_1_9?ascsubtag=dc6cf6efbd9e870c0a7c0b6b20716b95&keywords=light+dimmer&qid=1672399537&sr=8-9   | $8.22   |
| D10 3.7V Rechargeable Lithium ion Battery Power Bank Cell  X 3/[Product         ](https://www.amazon.in/Rechargeable-Lithium-Bluetooth-Emergency-3-7v/dp/B0BKLJW6WZ/ref=sr_1_3?ascsubtag=2b0d051f60e31b9869fd994ea8086665&keywords=lithium-ion+battery&qid=1672400083&sr=8-3)| Supplier/Link                         | $11.0  |
| 5V 2 Channel Relay Module | (https://robu.in/product/5v-2-channel-relay-module/) | $1.20 |
| ESP32-CAM-MB MICRO USB Download Module for ESP32 CAM Development Board| [https://robu.in/product/esp32-cam-mb-micro-usb-shield-module-for-esp32-cam-development-board/](https://robu.in/product/esp32-cam-mb-micro-usb-shield-module-for-esp32-cam-development-board/) | $2.42 |
| 2 Channel Relay Module, 30A with Optocoupler, Isolation 5V Supports, High and Low Triger | [https://robu.in/product/2-channel-relay-module-30a-5v-supports-high-and-low-trigger-optocoupler/](https://robu.in/product/2-channel-relay-module-30a-5v-supports-high-and-low-trigger-optocoupler/) | $6.04 |
| MC-38 Wired Door Window Sensor Magnetic Switch Home Alarm System | [https://robu.in/product/mc-38-wired-door-window-sensor-magnetic-switch-home-alarm-system/](https://robu.in/product/mc-38-wired-door-window-sensor-magnetic-switch-home-alarm-system/) | $0.69 |
| Waveshare Moisture Sensor | [https://robu.in/product/waveshare-moisture-sensor/](https://robu.in/product/waveshare-moisture-sensor/) | $3.20 |
| Tactile Push Button Switch set | [https://robu.in/product/tactile-push-button-switch-assorted-kit-25-pcs/](https://robu.in/product/tactile-push-button-switch-assorted-kit-25-pcs/) | $1.81|
| MQ-2 Smoke LPG Butane Hydrogen Gas Sensor Detector Module | [(https://robu.in/product/mq-2-mq2-smoke-gas-lpg-butane-hydrogen-gas-sensor-detector-module/](https://robu.in/product/mq-2-mq2-smoke-gas-lpg-butane-hydrogen-gas-sensor-detector-module/) | $0.95 |
| 4×4 Matrix Keypad Membrane Switch for Arduino, ARM and other MCU | [https://robu.in/product/4x4-matrix-keypad-membrane-switch-arduino-arm-mcu/](https://robu.in/product/4x4-matrix-keypad-membrane-switch-arduino-arm-mcu/) | $1.09|
| 	Standard 5V 3A Power Supply with 5.5mm DC Plug|[(https://robu.in/product/orange-5v-3a-power-supply-adapter-charger-with-5-5mm-dc-plug/](https://robu.in/product/orange-5v-3a-power-supply-adapter-charger-with-5-5mm-dc-plug/)| $2.78|
| GL-12 840 Points Solderless Breadboard X 2 | [https://robu.in/product/breadboard-840-tie-points-solderless-diy-project-circuit-test-breadboard/](https://robu.in/product/breadboard-840-tie-points-solderless-diy-project-circuit-test-breadboard/) | $1.45|
| 	Female to Female DuPont Line 40 Pin 30cm | [https://robu.in/product/female-female-dupont-line-40-pin-30cm/](https://robu.in/product/female-female-dupont-line-40-pin-30cm/)| $0.60|
| HC-SR04-Ultrasonic Range Finder | [https://robu.in/product/hc-sr04-ultrasonic-range-finder/](https://robu.in/product/hc-sr04-ultrasonic-range-finder/) | $0.87|
| Electronics ESP32 ESP-32 ESP-32S ESP 32 Development Board CP2102 WiFi Bluetooth Ultra-Low Power Consumption Dual Core X 5 | [https://www.amazon.in/gp/product/B07TYCFX5C/ref=ewc_pr_img_3?smid=A2KWJ4IHWZH3FB&psc=1](https://www.amazon.in/gp/product/B07TYCFX5C/ref=ewc_pr_img_3?smid=A2KWJ4IHWZH3FB&psc=1) | $34.75|
| Raindrops Detection Sensor Module	 |[https://robu.in/product/raindrops-detection-sensor-module-rain-weather-humidity/](https://robu.in/product/raindrops-detection-sensor-module-rain-weather-humidity/)| $0.91|
| 40 Pin Red GPIO Extension Board for Raspberry Pi|[https://robu.in/product/40-pin-red-gpio-extension-board-for-raspberry-pi/](https://robu.in/product/40-pin-red-gpio-extension-board-for-raspberry-pi/) | $1.50|
| 20 CM 40 Pin Dupont Cable Male/Male, Male/Female, Female/Female Cable Combo | [https://robu.in/product/20-cm-40-pin-dupont-male-male-male-female-female-female-cable-combo/](https://robu.in/product/20-cm-40-pin-dupont-male-male-male-female-female-female-cable-combo/) | $1.50|
|Soil Moisture Meter, Soil Humidity Sensor, Water Sensor, Soil Hygrometer for Ardunio X 2 | https://robu.in/product/soil-moisture-meter-soil-humidity-sensor-water-sensor-soil-hygrometer-ardunio/ | $1.45 |
|Flame Sensor Module |[https://robu.in/product/flame-sensor-module/](https://robu.in/product/flame-sensor-module/) | $0.85 |
|RPI4-MODBP-8GB| https://in.element14.com/raspberry-pi/rpi4-modbp-8gb/raspberry-pi-4-model-b-cortex/dp/3369503) | $73.79 |
| I2C ADS1115 16 Bit ADC 4 channel Module with Programmable Gain Amplifier | [https://robu.in/product/i2c-ads1115-16-bit-adc-4-channel-module-with-programmable-gain-amplifier/](https://robu.in/product/i2c-ads1115-16-bit-adc-4-channel-module-with-programmable-gain-amplifier/) | $9.07|
|37-1K - Resistance:1kohm |[https://in.element14.com/mcm/37-1k/resistance-1kohm/dp/2784369](https://in.element14.com/mcm/37-1k/resistance-1kohm/dp/2784369) | $2.14 |
| Orange Raspberry Pi 4 Advance Kit   | [https://www.adafruit.com/product/1957](https://robu.in/product/orange-raspberry-pi-advance-kit/#reviews) | $55.59  |
|Plusivo Soldering Kit with Multimeter (EU Plug) | (https://robu.in/product/plusivo-soldering-kit-with-multimeter-eu-plug/) | $21.26 |
| Total           |                                       | $249.95|
