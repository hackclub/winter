---
name: "@Gaurav-Ban22"
project: "Multijointed Movable Robotic Arm"
---

# Project Name

Movable Robotic Arm

## Summary

So the basis of this project is a medium-sized, motor-jointed robotic arm. I aim to use machine learning to look at a person's arm through a camera, and then map the arm's movement to that robotic arm.  I am planning on hooking it up to a esp32 and a raspberry pi (for moving the arm and for getting camera input, respectively).
As extra touches I will add electromagnets to a 3d printed claw at the end of the arm that can be enabled and disabled, as well as an e-paper display (for aesthetic purposes.)

I actually came up with this idea a few weeks ago when I had heard of inverse kinematics. Inverse kinematics is a way of moving a multi-jointed structure into a certain formation. I wanted to use FABRIK, or forward and backward reaching inverse kinematics, to make some sort of arm in real life, rather than a video game or simulation.

I would use this to learn more about FABRIK and how I could use it; I think its a really cool concept and I want to delve deeper into it. Also, I would get more practice with esp32s, computer vision, and more. Also, it would be pretty cool to be able to control a robotic arm. :)



## Plan

I am first going to design the arm and the stand for the arm; I aim for the arm to be like a simple multijointed robotic arm or industrial arm, and for most of the material of the arm and hub to be made of 3d printed filament. When I am done designing the project's overall prototype, I will print the required pieces.

I will then set up the esp32 microcontroller. I will connect it to the stepper motors, aesthetic e-paper display, and electromagnets controlling the joints through dupont wires and breadboards.
The raspberry pi will also be used, and I will hook it up to the camera and set up computer vision with tflite; I can easily interop between the esp32 and the rasbpi due to the esp32's ability to handle bluetooth and wifi.

Overall, I aim to make a working prototype with a working, moveable arm (through inverse kinematics).

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

Everything is in USD

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| esp32s          | https://www.amazon.com/Teyleten-Robot-ESP-WROOM-32-Development-Microcontroller/dp/B08246MCL5/ref=sr_1_3?crid=3N6W6ZGMUDTIL&keywords=esp32&qid=1673331848&sprefix=esp32%2Caps%2C159&sr=8-3&th=1 | $17.88  |
| 2.9" e-paper display | https://www.amazon.com/2-9inch-Module-Resolution-Display-Electronic/dp/B07P6MJPTD/ref=sr_1_2_sspa?crid=3075U8PPF2RUA&keywords=epaper+module&qid=1673331940&sprefix=epaper+modul%2Caps%2C139&sr=8-2-spons&psc=1&smid=A2SA28G0M1VPHD&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFOUVVBSk1ZNjY1QVQmZW5jcnlwdGVkSWQ9QTA4NTk4NTIzMVIzN0QxSk1VNURMJmVuY3J5cHRlZEFkSWQ9QTAxMTMyMDNVSUY3TU9BN1FGMTEmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl | $22.65 |
| Steppers+drivers   |https://www.amazon.com/ELEGOO-28BYJ-48-ULN2003-Stepper-Arduino/dp/B01CP18J4A/ref=sr_1_3?crid=NXEWAG8D1VOD&keywords=stepper+motor&qid=1673332024&sprefix=stepper+moto%2Caps%2C140&sr=8-3                                | $13.99 |
|Dupont Wires | https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78/ref=sr_1_3?crid=21OQ3Z22NQ4T7&keywords=long%2Bconnection%2Bwires%2Besp32&qid=1673332285&sprefix=long%2Bconnection%2Bwires%2Besp3%2Caps%2C163&sr=8-3&th=1 |6.98|
|Breadboards| https://www.amazon.com/Breadborad-Solderless-Breadboards-Distribution-Connecting/dp/B082VYXDF1/ref=sr_1_1_sspa?crid=37DDAE31FBSO8&keywords=breadboards&qid=1673332425&sprefix=breadboard%2Caps%2C140&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExUVpTVThJN1I2N1JGJmVuY3J5cHRlZElkPUEwMDkzNDI1SEhYVFZUUzJIV0ZUJmVuY3J5cHRlZEFkSWQ9QTA5Mzc2MzUxTFJZVkUzNTRBR0paJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ== |$12.99|
|Electromagnets| https://www.amazon.com/KEYESTUDIO-Electromagnet-Module-Arduino-Environmental-Friendly/dp/B07H3V8N2Q |$10.00|
|Raspberry Pi 4 Model B| https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TD42S27/ref=sr_1_3?crid=1ETXZIZ3CYHOU&keywords=raspberry%2Bpi%2B4&qid=1673416760&sprefix=raspberry%2Bpi%2B4%2B%2Caps%2C151&sr=8-3&ufe=app_do%3Aamzn1.fos.f5122f16-c3e8-4386-bf32-63e904010ad0&th=1 | $119.00 |
|Webcam Module| https://www.amazon.com/Microphone-Calling-Conferencing-Streaming-Computer/dp/B09TKCBWZ2/ref=sr_1_2_sspa?crid=3J732YPQOKCW0&keywords=1080p+webcam&qid=1673416998&sprefix=1080p+webc%2Caps%2C150&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExSFZGV0dXUUxISTNOJmVuY3J5cHRlZElkPUEwOTcyNjk4MVVZQ040OUxDR1Q5NCZlbmNyeXB0ZWRBZElkPUEwMzIxMzE0M0tLVDE1VTQ2SzBCNSZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU= |$19.99|
|3d Printer| Already own | |$0.00|
|Computer-Microcontroller connection wires| Already own |$0.00|

Subtotal: $223.48 USD
Tax: $20.01 USD
Coupon for Webcam: -$4 USD

Total: $239.28 USD
