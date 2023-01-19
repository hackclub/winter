---
name: "@xi-forgetme"
project: "Mini Home NAS"
---

# Mini Home NAS - A portable server controlled by a car.

## Summary

Hello!

Thank you for reading my project, just as the title, this is a portable private cloud.

It can also move everywhere as a mini car. You can control it with the RPi. It can also use a hotpot to connect with your phone.

This project is made for a home NAS to storage data locally rather than storage them on clouds.

As the development of information technology， more and more data are generated in people's lives.

They may like to storage them on clouds like iCloud, MEGA etc. However, the high price makes the storage of data generate a lot of unnecessary expenses.

By the way, they store the data on the cloud and the sync of the data is very slow, so I just wanna build a mini home-stay cloud as a private NAS for people.

Programmers can also build a local git repo, or build a portable cloud code platform.

Also I will use this Raspberry Pi to control a mini car with L298N, so that I can move this portable NAS by the mini car lol.

TODO: I gotta write an app on phone to control the car easier.


## Plan
### STEP 1
Install Linux on SD Card for Raspberry Pi 4B, and Install necessary software like nginx python etc. The web admin panel I will write by myself (I have almost finished it now).

### STEP 2
Build the mini-car, and connect to the L298N, then connect MotorA (OUT1, OUT2), MotorB(OUT3, OUT4), 12V in, 5V out, IO to Raspberry Pi.
         L298N
+---------------------+
|                     |
|                     |
|                     |
<OUT1 *         * OUT3>
<OUT2 *         * OUT4>
|  *                  |
+-12V-GND-SV----IO----|

         Car
  +--------------+
  |    ______    |
 | |   |    |   | |
  |     L298N    |
  |              |
 | |    RPi     | |
  |              |
  +--------------+
### STEP 3
Connect the remaining wires, Boot, and connect to the Internet, **set IP address to be static**, and install RPi.GPIO, then use [this script](https://github.com/xi-forgetme/PyCar) to control the portable server.

### STEP 4
Log in and configure what you need.

### STEP 5
Then you can connect or access the server everywhere and move it everywhere you want.

### STEP 6
**TODO: Make the server can fly lol**

## Budget


| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi 4B | [JD](https://item.jd.com/100020415183.html) | $162.54  |
| SanDisk SD Card 64GB | [JD](https://item.jd.com/2141154.html)  | $8.81 |
| 7'' Screen | [JD](https://item.m.jd.com/product/44632987580.html) | $34.18 |
| metal shell | [JD](https://item.m.jd.com/product/55298728091.html) | $3.88 |
| Wireless Network Adapt | [JD](https://item.m.jd.com/product/10051857225000.html) | $16.57|
| mini wireless ketboard | [JD](https://item.m.jd.com/product/10041381894140.html) | $11.19 |
| L298N | [JD](https://item.m.jd.com/product/10054711210476.html) | 1.64 |
| mini car kit | [JD](https://item.m.jd.com/product/67803770281.html) | $4.03 |
| NVMe Mobile Hard Disk Box | [JD](https://item.m.jd.com/product/100044436249.html) | $11.93 |
| Shipping | FREE | $0|
| Tax | FREE | $0 |
| Total | | $249.10 |
