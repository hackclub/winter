---
name: ["@abhisinghh501", "@mahajanasim2"]
project: "Smart Mirror and Temperature and humidity logger"
---

## Summary

### Smart mirror
Raspberry Pi can be used to create a smart mirror that can display information such as the time, weather, news, calendar, and more. Some of the smart mirror also could include facial recognition, voice control, and other advanced features.
The Raspberry Pi is responsible for running the software that powers the smart mirror, including a graphical user interface (GUI) that allows users to interact with the various features of the mirror. The GUI is typically displayed on a touch screen that is mounted behind the mirror, which allows users to interact with the mirror as if it were a computer screen.
Additionally, the smart mirror could be integrated with other smart devices in the home, such as lights and thermostats, to allow for control of those devices through the mirror.

### Temperature and humidity logger
A temperature and humidity logger made using a Raspberry Pi is a device that uses the single-board computer to measure and record the temperature and humidity in a given environment. The device is typically built using a temperature and humidity sensor, such as a DHT11 or DHT22 sensor, which is connected to the Raspberry Pi via a GPIO pin. The Raspberry Pi then reads the sensor data and records it to a file or database. The device can be configured to take measurements at regular intervals and can also be set up to alert the user if the temperature or humidity falls outside of a certain range. This device can be used for monitoring the temperature and humidity in a variety of settings such as greenhouses, museums, and storage facilities.

## Plan 

### Smart mirror
Gather Materials: You will need a Raspberry Pi computer, a mirror, a touch screen display, a frame or enclosure to hold the mirror and display, and various other components such as a power supply, cables, and a camera (optional).
Assemble the Hardware: Mount the touch screen display behind the mirror in the frame or enclosure. Connect the Raspberry Pi to the display, power supply, and any other components. Make sure everything is securely fastened and properly connected.
Install the Operating System: You will need to install an operating system on the Raspberry Pi. The most common choice for smart mirrors is Raspbian, a version of Linux that is optimized for the Raspberry Pi.
Install the Smart Mirror Software: There are several open-source software packages available for creating smart mirrors, such as MagicMirror and SmartMirror.js. These software packages provide the graphical user interface (GUI) and various features for the smart mirror.
Configure the Software: Once the software is installed, you will need to configure it to display the information and features you want on your smart mirror. This may include things like the time, weather, news, calendar, etc.
Customize the GUI: You can customize the GUI by adding widgets, modules, and other features. You can also adjust the layout, color scheme and text size to fit your preferences.
Finalize: Once everything is set up and configured, you can test it to make sure everything is working correctly. After that, you can install the mirror in the final location and use it.

### Temperature and humidity logger
Gather materials: To make a temperature and humidity logger using a Raspberry Pi, you will need a Raspberry Pi board, a temperature and humidity sensor (such as a DHT11 or DHT22), a breadboard, jumper wires, and a micro-USB power supply.

Connect the sensor to the Raspberry Pi: Using the breadboard and jumper wires, connect the data pin of the sensor to a GPIO pin on the Raspberry Pi, and connect the power and ground pins of the sensor to the corresponding pins on the Raspberry Pi.

Install software dependencies: Before you can read data from the sensor, you'll need to install the necessary software dependencies on your Raspberry Pi. This includes the Python library for the sensor, as well as any other libraries required for reading data from the sensor.

Write the code: Using Python, write a script that reads data from the sensor and stores it in a file or database. You can also include logic in the code to take measurements at regular intervals and to alert the user if the temperature or humidity falls outside of a certain range.

Test the device: Once your code is written, test the device by running the script and checking that it is correctly reading data from the sensor and storing it in the file or database.

Configure the logging intervals: Configure the device to take measurements at regular intervals. you can use cron jobs, systemd timer or other scheduling tools to schedule the script to run at specific intervals.

Deploy the device: Once you have tested the device and confirmed that it is working correctly, you can deploy it in the environment you want to monitor.

Monitor the data: Regularly check the data being logged to ensure that the device is working as intended. If you notice any issues, you can troubleshoot and make adjustments as needed.

## Budget
 -All prices include shipping and taxes
 -We're willing to cover the extra money ourself

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Acrylic sheets | Owned | 0 |
| 21.5" mirror | Owned | 0 | 
| 21.5" inch monitor | Owned | 0 |
| External speakers with mic | Owned | 0 |
| External camera(old phone being reused | Owned | 0 |
| 21 inch frame | https://amzn.asia/d/goulJRe | $52 |
| Rasberry pi 4 starter kit for the mirror| https://raspberry.piaustralia.com.au/products/raspberry-pi-starter-kit?variant=32057111969841 | $207 |
| Rfid cards | Owned | $ 0 |
| Rfid Reader for a pi | Owned(will be compatible with all pis) | $ 0|
| 7 inch touchscreen for the pi | https://raspberry.piaustralia.com.au/products/7-inch-1024x600-raspberry-pi-monitor-touchscreen-capacitive-ips-display-with-built-in-speaker-stand | $ 90 |
| External sensor kit for a pi | Owned | $0 |
| Rasberry pi 4 starter kit for temperature and humidity logger| https://raspberry.piaustralia.com.au/products/raspberry-pi-starter-kit?variant=32057111969841 | $207 |
| Total           |                                       | $556 |
