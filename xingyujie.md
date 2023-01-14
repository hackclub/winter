---
name: "@xingyujie"
project: "IOT remote control system(IRCS)"
---

# IOT remote control system(IRCS)

## Summary
I have had a strong interest in computers since the beginning of my elementary school. I go from software to hardware. I have built many projects through MCU, development board. These experiences have given me more love for computers, and let me learn more programming languages and get in touch with more hardware.  

Do you want to remotely turn on your home devices, computers, etc. when you are out? IRCS did just that. When you are on the go, you only need to click on the intuitive visualization panel, and your corresponding equipment will be turned on.  Through IRCS, you can monitor your home conditions anywhere in the world, and remotely/wirelessly turn on any device in your home, which is very cool!



## Plan

Through this project, I will build a Linux distribution on the Raspberry Pi. At present, my computer is basically Linux, and I have also studied it specially, so I am very familiar with it. The name of this Linux distribution is: FlyOS Cloud. This release integrates an intuitive, I will write a WEB control panel based on Python Flask, including the required dependent environment and software. Through this set of panels, you can access and control the equipment in your home anywhere in the world (provided that the equipment is connected to IRCS), and it also comes with a camera, you can keep track of the situation in your home anytime, anywhere, and you can control the voltage of the equipment (preliminary design 12V 1.5 A). And support the use of ESP-32 devices to control devices in different places through 2.4g wireless (such as living room and bedroom, can be remotely controlled through wireless bridges), ESP32 is a small wireless microcontroller with 2.4g, And make these "non-smart" devices smart. Moreover, since ESP32 is wireless, these non-smart devices become wireless remote control devices after they are integrated with ESP32, and IRCS can remotely control these non-smart devices integrated with ESP32. Therefore, IRCS can directly control IRCS-connected devices via cable (DuPont line), or remotely control ESP32-modified smart devices via wireless. all IoT devices in the whole house can be directly controlled through IRCS.

For the hardware, we need a Raspberry Pi 4B to control the IoT devices, a 64G TF card inserted in the Raspberry Pi to store the operating system and software, a Raspberry Pi camera to monitor the home conditions, a voltage converter , 3 ESP32 (for 2.4g to control the device wirelessly in three rooms), a soldering iron for soldering the device, I already have enough Dupont wire, voltage converters and LED lights, so don't have to buy again.

Through this project, I will learn more about hardware and software. It's a very interesting experience. After this, I will be testing our IRCS project and I will be very excited to control our home devices from anywhere in the world

For this project, I didn't follow any guides, but I saw some similar guides, I found it very interesting, I originally implemented a similar project using esp8266, but esp8266 is a microcontroller, so it is not based on Linux, there is no intuitive visualization panel, and it is also impossible for one terminal device to control devices in multiple rooms, etc. But this new project has achieved these
## Budget


| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry PI 4B | https://item.m.jd.com/product/57497424806.html?gx=RnFkkTZcamffmtRP--txCDpbRe2Q8d80DZje&ad_od=share&utm_source=androidapp&utm_medium=appshare&utm_campaign=t_335139774&utm_term=CopyURL | $198.41  |
| electric soldering iron | https://item.m.jd.com/product/10028240754328.html?gx=RnFkkTZcamffmtRP--txCDpbRe2Q8d80DZje&ad_od=share&utm_source=androidapp&utm_medium=appshare&utm_campaign=t_335139774&utm_term=CopyURL  | $35.53 |
| ESP-WROOM-32 x3 | https://m.tb.cn/h.UlITbib?tk=1RpUdUOdm2F | $10.28 |
| SanDisk 64GB TF | https://item.m.jd.com/product/1887526.html?gx=RnFkkTZcamffmtRP--txCDpbRe2Q8d80DZje&ad_od=share&utm_source=androidapp&utm_medium=appshare&utm_campaign=t_335139774&utm_term=CopyURL | $5.12 |
| Dupont wire     | already own 
| LED lights      | already own
| voltage converter | already own
| shipping and taxes|                                     | $0.00 |
| Total           |                                       | $249.34 |
