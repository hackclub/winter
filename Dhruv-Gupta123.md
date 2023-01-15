
name: Dhruv-Gupta123
project: The all in one robo

#summary

I am going to build a robot car that will have the following features-
1. can be controlled by mobile using bluetooth
2. can be controlled by a wireless remote
3. can avoid any obstacle in between
4. can follow your hand
5. can move away from your hand
6. can be controlled using a wearable glove by moving your fingers
7. has a weapon which can shoot
8. can follow a black line
9. can follow light
10. can be controlled by voice

The above featues in the car can be switched form one to another by the remote, bluetooth, glove, a board present in the car


I am also making a second project in which a user can control any appliance by the movement of their hand wirelessly.
## PlAN
First Project------------------------------------------
First i will 3d design the sturcture of the car and the 3d print it after that i will attach the motors on the 3d printed parts after that i will connect the 
motors to the motor driver and the motor driver to arduino after that i will connect the sensors, bluetooth module, rf module(for communicating wirelessly with 
the glove and the remote) The car will have two arduinos as one arduino can only send and recieve signal from a single rf so as we are using 2 rf module to control
the car with both remote and gesture so the first arduino will control the motors using glove and the second one will recieve signal from the remote and then send 
it to the second arduino and that arduino will recieve the signal and controll the motors acording to it then i will use a glove to connect the flex sensors rf module
(for communicating wirelessly with the car), arduino, etc. and code for making the car gesture controlled and then i will 3d print a remote and connect the joystick 
module, arduino, rf module(for communicating wirelessly with the car) switches,etc and code it.for controlling it with phone i will add a bluetooth(bt) module 
(for establihing bluetooth communication) in it. After that i will make the weapon using bo motors then i will attach the weapon on the car. The weapon 
will be able to shoot 3d printed balls,etc. The balls will be hollow so that no one will be harmed from it.
--------------------------------------------------------
Second Project------------------------------------------
In this first i will use a emg sensor to sense the signals of the brain then it will send it to the arduino and then the arduino will trainsmit the siganl wirellesssly to the other arduino and then that arduino will turn the appliance on or off the appliance can be a bulb, fan, heater,etc. 
--------------------------------------------------------
## Budget

| Product         | Supplier/Link                                                                                                                                                                                                                                                                                                   | Cost    |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
|  flex sensorX5  | https://www.amazon.in/Robodo-Electronics-FSENS-Sensor-Inches/dp/B00QV9Q1SE/ref=sr_1_2?crid=ZTNQ6GY8QB2B&keywords=flex+sensor+adafruit&qid=1673439517&sprefix=flex+sensor+adafrui%2Caps%2C231&sr=8-2                                                                                                             | $30.615 |
|  Arduino UNOX4  | https://www.amazon.in/Arduino-Uno-ATmega328P-USB-Cable/dp/B01LCN8IRK/ref=sr_1_10?crid=S5XCRDJXAYUS&keywords=arduino&qid=1673440090&sprefix=arduino%2Caps%2C221&sr=8-10                                                                                                                                          | $54.372 |
|  l293d driver   | https://www.amazon.in/xcluma-Driver-Shield-Arduino-Others/dp/B071S9W3HS/ref=sr_1_14?crid=1Z98VUPW1U7IK&keywords=l293d+motor+shield&qid=1673441003&sprefix=l293d+%2Caps%2C306&sr=8-14                                                                                                                            | $3.062  |
|  rf moduleX2    | https://www.amazon.in/Robotbanao-Wireless-Transmitter-Compatible-Raspberry/dp/B07DZCJRJ6/ref=sr_1_1_sspa?crid=2LZ42M7GE0XJF&keywords=rf+module&qid=1673441372&sprefix=rf+module%2Caps%2C237&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1                                                                   | $8.866  |
|  bt module      | https://www.amazon.in/Robotbanao-Bluetooth-Transceiver-Module-Outputs/dp/B08DV4CDXX/ref=sr_1_1_sspa?crid=2UQQW7QJIJAQ5&keywords=bluetooth+module&qid=1673441569&sprefix=bluetooth+modu%2Caps%2C232&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1                                                            | $7.421  |
|  bo motorX8     | https://www.amazon.in/Robotbanao-Duel-shaft-motor-wheel/dp/B07CVYWYQ7/ref=sr_1_23_sspa?crid=21PMM6L6YV3LM&keywords=bo+motor+high+torque+and+rpm&qid=1673441708&sprefix=bo+motor+high+trque+and+rpm%2Caps%2C219&sr=8-23-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1                                               | $12.246 |
|  jumper wires   | https://www.amazon.in/Electrobot-Jumper-Wires-120-Pieces/dp/B071VQLQQQ/ref=sr_1_6_mod_primary_new?crid=1A1E5E8I4TIMJ&keywords=jumper+wires&qid=1673441860&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=jumper+wire%2Caps%2C395&sr=8-6                                                                         | $2.449  |
|  breadboard     | https://www.amazon.in/Electronic-Spices-Solderless-Breadboard-Prototype/dp/B0BN7X7FFT/ref=sr_1_15?crid=PCMIE8C9NPRP&keywords=breadboard&qid=1673441968&sprefix=bread%2Caps%2C238&sr=8-15                                                                                                                        | $1.102  |
|  joystick module| https://www.amazon.in/rees52-JoyStick-Module-Breakout-Sensor/dp/B01HTH9ITK/ref=sr_1_6?crid=NTAK74JYHUQO&keywords=joystick+module+for+arduino&qid=1673442135&sprefix=joystick+module+for+arduino%2Caps%2C225&sr=8-6                                                                                              | $4.384  |
|  ir sensorX4    | https://www.amazon.in/Robotbanao-Infrared-Obstacle-Avoidance-Sensor/dp/B09H48S43B/ref=sr_1_1_sspa?crid=1KZXJMH48RSGG&keywords=ir%2Bsensor&qid=1673442386&sprefix=ir%2Bsensor%2Caps%2C223&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1                                                                       | $13.324 |
|  servo motor    | https://www.amazon.in/Servo-motor-SG90-for-arduino/dp/B0B87961FN/ref=sr_1_37?crid=3JI3HAF1ER2G3&keywords=servo+motor&qid=1673442501&sprefix=servo+moto%2Caps%2C313&sr=8-37                                                                                                                                      | $3.417  |
|  LDR            | https://www.amazon.in/Photosensitive-digital-Arduino-Raspberry-projects/dp/B07CW9Q189/ref=sr_1_8?crid=24FCQ6341T8UL&keywords=ldr&qid=1673443285&sprefix=ld%2Caps%2C365&sr=8-8&th=1                                                                                                                              | $2.779  |
|  lithium battery| https://www.amazon.in/Rechargeable-Battery-Lithium-Single-Holder/dp/B09DPWBYYK/ref=sr_1_2?crid=1YX93WZOS9EZ8&keywords=lithium%2Bion%2Bbattery%2B3.7v%2Brechargeable%2B18650&qid=1673445123&refinements=p_90%3A20912642031&rnid=6741116031&sprefix=lithium%2B18650%2Brechargeable%2B3.7v%2Caps%2C211&sr=8-2&th=1 | $13.774 |
|  battery charger| https://www.amazon.in/M-Enterprises-Lithium-Battery-Protection/dp/B01M5IGW85/ref=sr_1_10?crid=UOWDZ1ALGIZI&keywords=lithium%2Bion%2Bbattery%2B3.7v%2Brechargeable%2B18650+charger&qid=1673447480&sprefix=lithium%2Bion%2Bbattery%2B3.7v%2Brechargeable%2B18650+charge%2Caps%2C295&sr=8-10                       | $1.494  |
|  pla            | https://www.amazon.in/Filament-Dimensional-Accuracy-Compatible-Printers/dp/B0BFVZXQ2P/ref=sr_1_2_sspa?crid=8P93YAS902GY&keywords=pla&qid=1673447706&sprefix=pla%2Caps%2C232&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1                                                                                    | $11.007 |
|  3D printer     | ALready OWN | |
Second project
| relay moduleX2  |https://www.amazon.in/Robotbanao-Channel-Module-Shield-Arduino/dp/B08T77P3T4/ref=sr_1_1_sspa?crid=6IEN37VYAKBT&keywords=relay+module&qid=1673793026&sprefix=relay+modu%2Caps%2C410&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1|$6.997|
| EMG SensorX2    |https://store.upsidedownlabs.tech/product/muscle-bioamp-patchy/|$24.615|
| Arduino UNOX2   |https://www.amazon.in/REES52-ATmega328P-Devlopment-Compatible-Arduino/dp/B08Y95CMRH/ref=sr_1_16?crid=QELTUO8GYDDK&keywords=arduino+uno&qid=1673793385&sprefix=arduino+un%2Caps%2C333&sr=8-16|$24.591|
| RF module      |https://www.amazon.in/Robotbanao-Wireless-Transmitter-Compatible-Raspberry/dp/B07DZCJRJ6/ref=sr_1_1_sspa?crid=NO9YCF29H2YK&keywords=rf+module&qid=1673793491&sprefix=rf+modu%2Caps%2C343&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1|$4.111|
| jumper wires  |ALready Own||
TOTAL=$230.626
