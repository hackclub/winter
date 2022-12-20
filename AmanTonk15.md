---
name: "@AmanTonk15"
project: "Security Access Using RFID Reader"
---

# Project Name - Security Access Using RFID Reader

## Summary

What are you going to build? What does it do? Why are you excited to build it?

RFID tagging is an ID system that uses small radio frequency identification devices for identification and tracking purposes. An RFID tagging system includes the tag itself, a read/write device, and a host system application for data collection, processing, and transmission.

In simple words an RFID uses electromagnetic fields to transfer data over short distances. RFID is useful to identify people, to make transactions, etc…

You can use an RFID system to open a door. For example, only the person with the right information on his card is allowed to enter. An RFID system uses:
>> tags attached to the object to be identified, in this example we have a keychain and an electromagnetic card. Each tag has his own identification (UID).
>> two-way radio transmitter-receiver, the reader, that sends a signal to the tag and read its response
Basic Specifications:

Input voltage: 3.3V
Frequency: 13.56MHz
Now, before typing out the necessary code, you need to download the necessary library for this sensor from this repository.

Extract the contents from the zip folder "rfid-master" and add this library folder under the existing libraries of Arduino.

After doing so, restart your ArduinoIDE.

Now, our Arduino is ready to take commands and execute accordingly.

The Arduino Code has been uploaded at the end of this tutorial. Compile the code and eliminate "typo" errors (if any).

Now, its time to connect our Arduino with the RFID reader. Refer to the PIN wiring below,as well as the Connection schematic diagram for easy reference.

PinWiring to Arduino Uno

SDA------------------------Digital 10

SCK------------------------Digital 13

MOSI----------------------Digital 11

MISO----------------------Digital 12

IRQ------------------------unconnected

GND-----------------------GND

RST------------------------Digital 9

3.3V------------------------3.3V (DO NOT CONNECT TO 5V) 

Reading data from an RFID tag

After having the circuit ready, go to File > Examples > MFRC522 > DumpInfo and upload the code. This code will be available in Arduino IDE (after installing the RFID library).

## Plan

https://www.arduino.cc/en/software

What steps are you going to take to build it? What tools are you going to use? What will you do first, second, third, etc.?

## Budget

| Product         |                                   Supplier/Link                         |  Cost  |
| --------------- |                                -------------------------------------    | ------ |
| Arduino Uno Rev3                   | https://store.arduino.cc/products/arduino-uno-rev3/  | $1.95  |
| SparkFun RFID Reader Breakout      | https://www.sparkfun.com/products/13030              | $19.95 |
|13.56MHz RFID/NFC Card - Classic 1K | https://www.adafruit.com/product/359                 | $2.50  |
| Total                              |                                                      | $24.4  |
