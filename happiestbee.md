---
name: "@happiestbee"
project: "Speed Tracking Luxury Keyboard"
---

# Speed Tracking Luxury Keyboard

## Summary

I am going to build a keyboard that tracks your typing speed and displays it on a small LCD screen. It will measure the speed of the user in words per minute and display additional stats such as the max words per minute of a session, the total number of keys/words pressed, and more. The keyboard will be able to detect the user and start a session using an ultrasonic sensor. This way, the keyboard will be able to automatically detect when a user is in front of it or not. 

The keyboard will have additional features such as interactive LCD lighting, programmable messages, and speakers for music and sound effects which will all be controlled using web application that the user can access.

In my experience, many people are interested in how fast they type and use typing speed tests to measure their progress. This project will allow users to track their typing speed in a more convenient way and will allow them to see their progress over time. 

The keyboard comes with many other features as well, making it much more than a regular keyboard. This project will also be a fun way to learn about electronics and programming in a tool that is used everyday.

## Plan

First, I will connect the keyboard to the arduino to intercept the keystrokes and use the Keyboard library in arduino to write a program to detect which keyes and how fast the user is typing. 

Then, the arduino will then take these values and display them the LCD screen. 

Secondly, I will have a web application set up where the user is able to set how they want the lights and speaker to function such as what color schemes and patterns they want.

Third, I will write an arduino program to use the ultrasonic sensor to detect when someone is using the keyboard and start a session.

Finally, I will assemble all of these parts in a portable and compact keyboard.

Useful links:
https://github.com/garyhtou/Desk-Lights
https://projecthub.arduino.cc/Isaac100/7cabe1ec-70a7-4bf8-a239-325b49b53cd4
https://forum.arduino.cc/t/serial-input-basics-updated/382007/3
https://docs.arduino.cc/built-in-examples/usb/KeyboardSerial

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Keyboard Barebone   | https://www.amazon.com/dp/B01MSVHZTT | $49.22  |
| Keyboard Switches  | https://www.amazon.com/Switches-Prelubricated-Compatible-Mechanical-Keyboard/dp/B0B28Y7X88/ref=sr_1_1  | $33.00 |
| Keycaps | https://www.amazon.com/Profile-Japanese-Keycaps-Tenkeyless-Keyboard/dp/B09FSQP8TN/ref=sr_1_6 | $25.99 | 
| Arduino Leonardo | https://store-usa.arduino.cc/products/arduino-leonardo-with-headers | $24.90 | 
| Arduino Shipping |  | $2.33 | 
| LCD Display | https://www.amazon.com/GeeekPi-Character-Backlight-Raspberry-Electrical/dp/B07S7PJYM6/ref=sr_1_3 | $10.99 | 
| LED Strip Light | https://www.amazon.com/ALITOVE-Individual-Addressable-Programmable-Non-Waterproof/dp/B01MG49QKD/ref=asc_df_B01MG49QKD | $8.99 | 
| Speakers | https://www.amazon.com/MakerHawk-Full-Range-Advertising-Separating-JST-PH2-0mm-2/dp/B07FTB281F/ref=sr_1_3 | $10.99 | 
| Jumper Wires | https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78/ref=pd_bxgy_sccl_2/137-8916954-5557248 | $6.98 | 
| Breadboards | https://www.amazon.com/Breadboards-Solderless-Breadboard-Distribution-Connecting/dp/B07DL13RZH/ref=sr_1_4 | $13.99 | 
| Ultrasonic Sensor | https://www.amazon.com/Dorhea-Ultrasonic-Distance-Duemilanove-Rapsberry/dp/B07L68X65N/ref=asc_df_B07L68X65N | $8.99 | 
| Sales Tax |  | $11.65 | 
| Total           |                                       | $208.02 |