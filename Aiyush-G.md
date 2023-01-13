---
name: "@Aiyush-G"
project: "LED Matrix to Connect the Elderly to the Young"
---

# LED Matrix to Connect the Elderly to the Young

## Summary
I am planning to build three LED matricies each powered by an Adafruit Matrix Portal which features both an ATSAMD51J19 Cortex M4 processor and an ESP-32 Wifi co-processor allowing me both the computational power needed and wifi connectivitiy for the three devices to communicate between each other. 

The aim of the project is to have three separate 64 x 64 matrices that display messages between each other so the end-user (both my grandparents) who don't have access to mobile phones (which have low-accessibility due to their small screen size) can still communicate with their loved ones easily.
Furthermore, when not being used for sending messages (powered by a flask-server hosting a REST-API ) the device can display artwork, album art (my grandparents love music) & reminders ie. when to take medicine / meal times / carer times etc...

I am really excited to complete this build because despite being a fun project it will have real-world impact and hopefully make my grandparents daily lives more interesting and fun. From a technical perspective, interfacing the microcontroller with the web-server will provide a delightful challenge and allow me to employ best-practices that I've learnt through my other projects.

## Plan
### Specification

| Specification Point                                                            | Justification                                                                                                                                                                                            | How Will It Be Achieved                                                                                                       |
|--------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| There should be three LED-Matrixes                                               | This is required so there can be three devices that can communicate with each other. They should be 64 x 64 pixels to ensure enough screen-estate to make messages and images sent clearly visible.        | Three Adafruit 64 x 64 led matrices will be sourced.                                                                            |
| The device should have a range of options for what is displayed on the screen. | To make this project exciting for its' users, there should be a range of options for what can be displayed on screen ie. messaging, art work, football-scores etc...Exciting!                            | Software will be implemented in micro-python since it is both readable and more easy to implement that alternative languages. |
| The device should be powered 24/7 via mains.                                   | This is important since if the project was running of a LiPo battery it would quickly run out due to large power requirements. Consequently, a RPI USB-C adapter will be used that draws 3A, 5V and 15W. | Any USB-C wall adapter should work but the RPI one has been selected for most ease.                                           |

### Steps

1. **Prepare the Adafruit Portal**
Since a 64 x 64 LED matrix is being used this means that an E-Line jumper will have to be employed to ensure that the matrix works correctly. This means that the center-pad provided will need to be shorted to pin 8.
*See image below*
![Pads shown here](https://user-images.githubusercontent.com/55917505/211188243-13ae9154-3ded-4718-9e95-3e6048141a10.png)

2. **Power the board & Panel**
Screw the provided spade connectors into the board: red 5V, black GND. Connect the JST connectors to the LED matrix - plug the board into the left side shrouded 8x2 connector.

3. **Install CircuitPython**
Download provided UF2 file from CP website. Plug board into computer and hold reset button then drag file to MATRIX-BOOT directory.
More information about circuit python here: https://learn.adafruit.com/adafruit-matrixportal-m4/what-is-circuitpython

4. **Install Required Libaries**
The following libraries ensure that communicating with the portal can be done easily. Note, some of these libraries don't need to be used but that means relying on a lower-level library where documentation may be lacking.
```
adafruit_matrixportal - this library is the main library used with the MatrixPortal.
adafruit_portalbase - This is the base library that adafruit_matrixportal is built on top of.
adafruit_esp32spi - this is the library that gives you internet access via the ESP32 using (you guessed it!) SPI transport. You need this for anything Internet
neopixel.mpy - for controlling the onboard neopixel
adafruit_bus_device - low level support for I2C/SPI
adafruit_requests.mpy - this library allows us to perform HTTP requests and get responses back from servers. GET/POST/PUT/PATCH - they're all in here!
adafruit_fakerequests.mpy  - This library allows you to create fake HTTP requests by using local files.
adafruit_io - this library helps connect the PyPortal to our free data logging and viewing service
adafruit_bitmap_font - we have fancy font support, and it's easy to make new fonts. This library reads and parses font files.
adafruit_display_text - not surprisingly, it displays text on the screen
adafruit_lis3dh.mpy - this library is used for the onboard accelerometer to detect the orientation of the MatrixPortal
adafruit_minimqtt - this is used for communicating with MQTT servers.
```

5. **Connect to internet**
Store credentials in a secrets file first then access in python and attempt to join as AP. 
In the future, I will implement a WiFi manager so the ESP-32 acts as a web server so then the credentials don't need to be hard-coded into the secrets file. This means when credentials are altered of the WiFi network then this can be easily altered for the project without needing to plug the matrix into a computer.
Follow this guide here: https://learn.adafruit.com/adafruit-matrixportal-m4/internet-connect
What steps areyou going to take to build it? What tools are you going to use? What will you do first, second, third, etc.?

6. **Implement the software** 
This will be written before the 10-days of hacking and then troubleshooted within this time. Refer to the flowchart below on what I hope to implement.
I've yet to decide whether any external software GUI will be as a webpage or I might create it in the open-source engine Godot.
![Flowchart showing how software will be implemented](https://i.ibb.co/d08bN02/LED-Matrix-drawio.png)

## Budget


| Product                                                                     | Supplier / Link                                                                                    | GBP - Unit Cost Ex Vat | USD - Unit Cost Ex Vat | Number | GBP - Unit Cost x Number (incl Vat) | USD - Unit Cost x Number (incl Vat) |
|-----------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|------------------------|------------------------|--------|-------------------------------------|-------------------------------------|
| Adafruit Industries LLC 64X64 RGB LED MATRIX PANEL - 2MM                    | https://www.digikey.co.uk/en/products/detail/adafruit-industries-llc/5362/16020580                 | 41.63                  | 49.95                  | 3      | 124.89                              | 149.85                              |
| Adafruit Industries LLC ADAFRUIT MATRIX PORTAL - CIRCUIT                    | https://www.digikey.co.uk/en/products/detail/adafruit-industries-llc/4745/13250945                 | 20.79                  | 24.95                  | 3      | 62.37                               | 74.85                               |
| RPI USB-C POWER SUPPLY BLACK UK Raspberry PiAC/DC WALL MNT ADAPTER 5.1V 15W | https://www.digikey.co.uk/en/products/detail/raspberry-pi/RPI-USB-C-POWER-SUPPLY-BLACK-UK/10258766 | 6.67                   | 8.00                   | 2      | 13.34                               | 16.00                               |

Total USD: $240.70
