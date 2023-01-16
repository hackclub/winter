---
Name: "@wehaveagod"
Project: "DroneCar"
---

# Project Name

AI-RC-Drone-Car

## Summary

I am going to build a multi-purpose vehicle. Essentially, after driving the car to a specific location, I can detach the drone off it with a command. The car and drone will be sending constant video footage to a display. I am excited for this project because I will learn so much about CAD, circuit design, electronics, and AI.

## Plan

### First: Electrical

I will develop the circuitry required to operate the drone and car. This will include motors, ESCs, batteries, breadboards, Raspberry Pi, Arduino, and LCD display. I also hope to createa a custom remote controller using a PCB but I will probably be using a pre-made radio controller.

### Second: Mechanical and Assembly

I will use Fusion 360 to CAD the car and drone. I will base it around the electrical components. After creating a workable design, I will 3D print the parts using the Sovol SV01 printer. I can then asssemble the electrical components on the 3d printed parts.

### Third: Integration

After I have a working drone and car, I can then think about making them work together. The Arduino on the car will send information to the Raspberry Pi on the drone through a radio transceiver.

### Fourth: AI

After I get the drone and car completely integrated, I can use Computer Vision to develop a way for the drone to autonomously come back to the car.

## Budget

| Product                | Unit |  Cost ($) |
| ---------------        | ---- | ------ |
| [Car Motors (4-pack)](https://www.amazon.com/Alinan-Miniature-EK1450-Arduino-Projects/dp/B09MMZ78JW/ref=sr_1_10?crid=2AAEZU3OUUS7K&keywords=car%2Bmotors%2Bwith%2Bdupont&qid=1673844025&s=industrial&sprefix=car%2Bmotors%2Bwith%2Bdupont%2Cindustrial%2C97&sr=1-10&th=1) | 1 | 5.59 |
| [Brushless Motor](https://www.amazon.com/Brushless-1300KV-Electric-Airplane-Quadcopter/dp/B0BGPBTNCG/ref=sr_1_5?crid=3NWGRKK1HI799&keywords=brushless%2Bmotor&qid=1673844102&s=industrial&sprefix=brushless%2Bmotor%2Cindustrial%2C98&sr=1-5&th=1) | 4 | 0 | 
| [Servo (2-pack)](https://www.amazon.com/JIANNIU-SG90%EF%BC%8CMicro-Steering-Helicopter-Universal/dp/B09J89QJX5/ref=sr_1_11?crid=5EQ04FQH0F9R&keywords=servo&qid=1673844182&s=industrial&sprefix=servo%2Cindustrial%2C91&sr=1-11) | 1 | 0 |
| [LCD Display](https://www.amazon.com/Display-240x320-ILI9341-Arduino-3-2%EF%BC%8CRaspberry/dp/B086MBZD3Z/ref=sr_1_7_sspa?crid=L9YKQ84TZYCU&keywords=raspberry+pi+lcd+display&qid=1673845366&sprefix=raspberry+pi+lcd+displa%2Caps%2C111&sr=8-7-spons&psc=1&smid=ABMWZP7NSODS0&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzVkUwVEcyQjBRR01HJmVuY3J5cHRlZElkPUEwNDMyMTE0Q0cyNVpHUlpON0JEJmVuY3J5cHRlZEFkSWQ9QTAwNDU2NDExRFgwNDRHT0NHVlBRJndpZGdldE5hbWU9c3BfbXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==) |  1  | 17.12 |        |
| [Raspberry Pi](https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X/ref=sr_1_3?crid=30T5GXVQC90Q4&keywords=raspberry+pi&qid=1673844342&s=electronics&sprefix=raspberry+pi%2Celectronics%2C102&sr=1-3&ufe=app_do%3Aamzn1.fos.f5122f16-c3e8-4386-bf32-63e904010ad0) | 1 | 165 |
| [Arduino](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=sr_1_3?crid=BBAVODOBSFJZ&keywords=arduino&qid=1673844396&s=electronics&sprefix=arduino%2Celectronics%2C123&sr=1-3) | 1 | 0|    
| [ESC](https://www.atlantahobby.com/products/talon-25-amp-25v-esc-with-8-amp-bec)| 4 | 0 |   
| [Camera Module](https://www.amazon.com/Arducam-Autofocus-Raspberry-Megapixel-Resolution/dp/B09STL7S88/ref=sr_1_2?crid=1JTG7H1D3RKJ8&keywords=raspberry+pi+camera+module+with+cover&qid=1673844531&sprefix=raspberry+pi+camera+module+with+cov%2Caps%2C84&sr=8-2) | 2 | 59.98 |
| [Breadboard](https://www.amazon.com/dp/B071R3BFNL?ref=nb_sb_ss_w_as-reorder-t1_ypp_rep_k0_1_5&amp=&crid=3DH98NL7KED2Z&amp=&sprefix=gikfu) | 2 | 0 |
| [Lipo Battery (2-pack)](https://www.amazon.com/dp/B08KD1YN9F?ref=nb_sb_ss_w_as-reorder-t1_ypp_rep_k0_1_12&amp=&crid=1QQNBMKTPPTE7&amp=&sprefix=lipo+battery) | 1 | 0 |
| [Lipo Battery Charger](https://www.amazon.com/SUPULSE-Battery-Charger-7-4-11-1V-Charger%EF%BC%88B3V2%EF%BC%89/dp/B099K8XFG6/ref=sr_1_6?keywords=lipo+battery+charger&qid=1673844668&sr=8-6) | 1 | 11.99 | 
| [PiPower Module](https://www.sunfounder.com/products/power-pack) | 1 | 0 |
| [Flysky Remote Controller](https://www.amazon.com/FLYSKY-Transmitter-Controller-Receiver-Upgrade/dp/B07Z8VCB45/ref=sr_1_5?crid=1MGFQTKHZY31T&keywords=flysky+remote+controller&qid=1673844801&sprefix=flysky+remote+controlle%2Caps%2C104&sr=8-5&ufe=app_do%3Aamzn1.fos.006c50ae-5d4c-4777-9bc0-4513d670b6bc)| 1 | 0 | 
| PCB parts | ? | ? |
Total | - | 259.68 |  

$0 means I already have it
I do not know if I will be using a PCB for the remote control, which is why I am unsure about the parts. 
This is going a little over the budget, but I can handle the extra cost.
