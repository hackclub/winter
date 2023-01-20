---
name: "@xi-forgetme"
project: "Mini Home NAS"
---

# Mini Home NAS - A portable server controlled by a car.

## Summary

Hello! 

Happy lunar new year!

Do you want to hack with a toy car? Or do you want to storage your data on a small moving NAS? This is a really cool & simple Home NAS, you can control it to move everywhere as you want. And also, it just based on these common hardwares and a bit code.

As the development of information technology， more and more data are generated in people's lives.

They may like to storage them on clouds like iCloud, MEGA etc. However, the high price makes the storage of data generate a lot of unnecessary expenses.

By the way, they store the data on the cloud and the sync of the data is very slow, so I just wanna build a mini home-stay cloud as a private NAS for people.

Programmers can also build a local git repo, or build a portable cloud code platform, you can also do hacking with this moving "hacker" lol.


TODO: I gotta write an app on phone to control the car easier.


## Plan
### STEP 1
Install Linux on SD Card for Raspberry Pi 4B, and Install necessary software like nginx python etc. The web admin panel I will write by myself (I have almost finished it now). 

### STEP 2
Build the mini-car, and connect to the L298N, then connect MotorA (OUT1, OUT2), MotorB(OUT3, OUT4), 12V in, 5V out, IO to Raspberry Pi.

In this project, I will use this Raspberry Pi to control a mini car with L298N to move it everywhere, The design is as follows.

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
Connect the camera, I will make the mobile car server can be controlled on your phone via network as I said. With this, you can essier see what happening in front of the car.

### STEP 5
Then you can connect or access the server everywhere and move it everywhere you want.

## Budget


| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi 4B | [JD](https://item.jd.com/100020415183.html) | $162.54  |
| SanDisk SD Card 64GB | [JD](https://item.jd.com/2141154.html)  | $8.81 |
| 7'' Screen | [JD](https://item.m.jd.com/product/44632987580.html) | $34.18 |
| Wireless Network Adapt | [JD](https://item.m.jd.com/product/10051857225000.html) | $16.57|
| RPi Camera | [JD](https://item.m.jd.com/product/10036673190479.html) | $10.30 |
| L298N | [JD](https://item.m.jd.com/product/10054711210476.html) | 1.64 |
| mini car kit | [JD](https://item.m.jd.com/product/67803770281.html) | $4.03 |
| NVMe Mobile Hard Disk Box | [JD](https://item.m.jd.com/product/100044436249.html) | $11.93 |
| Shipping | FREE | $0|
| Tax | FREE | $0 |
| Total | | $250.00 |
