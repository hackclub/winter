---
name: "@alialiwa2005"
project: "Libre Web Services (LWS) | DIY Homemade AWS Cloud" 
---

# Project Name
(also known as "Raspberry Web Services (RWS)")

## Summary

I am going to build a hackable, Kubernetes-based, Arm-powered (mini-)cluster-computer private cloud. 

Instead of hosting a site, Minecraft server, or web app on a cloud service like AWS, 
I'm excited to build a hackable, Kubernetes-based, (mini)-super-computer Arm-powered private cloud, while exploring redundancy, load-balancing, containers, orchestration, and physical networking, from a hands-on hardware perspective!

I can't wait to build a DIY cluster of mini-servers at home! It's so wonderful to think of all the possibilities of this build!

What's more fascinating is how little electricity is used by the build. Also, this project doesn't require much physical space, 
and is versatile in many ways!

I am certain that this is will turn out to be an awesome and unique project, and I can't wait to start making it this winter.

While this project is about making, it is also an awesome learning opportunity for me, in terms of the hardware side of computing and cloud, such as physical networking, as well as the software side of dev-ops, 
such as using Kubernetes to manage separate pieces of hardware that make up a cluster in accomplishing tasks in unison... that is just mind-blowing to me!

What's even better is that unlike simply deploying instances on the AWS dashboard and I'm pretty much mostly finished... I get to build my own cloud, comparable to the actual Amazon Web Services, from scratch... starting with the hardware, inspecting the physical computer boards and chips, physically networking the nodes, even designing a stylish case for the cloud! :)

I always wanted to build my own macro-computer out of multiple mini-computers. I guess Winter of Making will finally make this dream a part of my New Year's Hacking bucket list! Hooray!

## Plan

For this project, you'll need a few computers to act as nodes, perhaps some Raspberry Pis, or in my case, a Raspberry Pi alternative (since there's a major Raspberry Pi shortage at the time of this event).

A good amount of memory is reccomended for stability, at least 4 gigabytes of RAM, but ideally 8 gigabytes or more per node, if possible.

If you decide to build this when Pi's are available, I reccomend you use Raspberry Pis... here's why:

Why Pis? They're UK-made, are great in terms of build quality, and are relatively affordable overall. 
They also don't use much electricity and are surprisingly powerful for their credit-card-size.

Also, Pis have ARM64 CPUs, just like AWS Graviton instances. This is awesome because it means that almost anything that can run on AWS EC2-A1 
or other Graviton-powered deployments can be deployed at home, on your own DIY AWS (RWS) cloud! :)

Aside from these, you also need accessories, like power supplies, storage (these can be MicroSD Cards, at least 16GB, ideally Class-10 32GB), ethernet cables, and a cluster stand/stackable cases for organization... I'll be designing my own cases for each node using a 3D printer.

You'll also need a laptop or PC for the initial setup of the Pis.

Some other optional but recommended items are:

- A network switch, so that the boards all connect to the ethernet switch, which ultimately links to your router via an organized 
single network cable.

- Cooling, such as heatsinks or fans... reccomended especially if you plan on overclocking, or for greater stability. If you're using Raspberry Pis, there are many great options for cooling out there!

---

Step 1: Order materials, then await items' arrival.

Step 2a: Design and build a custom case(s)/stand using a 3D printer, or other materials like wood, or buy a pre-made one.

Step 2b: Mount boards to the case(s), and attach heatsinks/fans (cooling) if applicable.

Step 3: On your PC, install Raspberry Pi imager.

(Repeat Steps 4 - 16 for each board)

Step 4: Insert your SD card into your computer.

Step 5: On Raspberry Pi Imager, select Raspberry Pi OS lite (32-bit or 64-bit), and select your SD card (make sure to select the correct storage device).

Step 5b: If you're using an Raspberry Pi alternative board, download the applicable OS image from your board's manufacturer. You can also use Ubuntu Server 64-bit, if you prefer.

Step 6: Write the image to your SD card.

(If you're using an alternate board, skip steps 7 through 14)

Step 7: Insert your SD card into a Pi & power on the Pi.

Step 8: After a few minutes (3-5 minutes), unplug the power from the Pi.

Step 9: Take out the SD card from the Pi & insert it into PC/laptop

Step 10: Your SD card should be named "boot." Open it, there should be a file called cmdline.txt

Step 11: At the end of the first line of cmdline.txt, paste this (this enables cgroup, needed for Kubernetes and containers to work 
completely and properly on the Pis): cgroup_enable=memory cgroup_memory=1

** For step 12, please note that your IP setup may be different, the format is (pi static IP):(router/gatwayip):(subnet mask):(pi hostname):eth0:off

** Also, for step 12 be sure to change the static IP and the hostname for each pi.

Step 12: After pasting, assign your pi a static IP and hostname by typing this: ip=192.168.1.121:192.168.1.1:255.255.255.0:cloudone:eth0:off

Step 13: Enable the 64bit tasks processing of your Pis' ARM64 CPU by opening the file named config.txt, scrolling to the bottom of the file to the "all" section, and adding a new line with the following: arm_64bit=1

Step 14: Enable headless SSH setup by creating a new file without an extension, name it: ssh

Step 15: Eject the SD card from the PC/laptop and plug the SD card into board, connect ethernet, and power.

Step 15b: If using an Raspberry Pi alternative board, use a keyboard & mouse, complete initial setup, and install ssh if not already installed. 
Refer to your board-specific documentation as needed.

Step 16: ssh into the boards & install Kubernetes.

Step 17: Set up the first board as the Kubernetes "master."

Step 18: Set up the other boards as Kubernetes "nodes."

Step 19: Experiment & hack with Kubernetes! Congrats on building your private cloud!

Step 20: Overclock! (or underclock, if you want to achieve even more energy efficiency)... 
Install monitoring software, deploy websites, block ads on your network with your own PiHole-powered DNS,
link to RGB lights (or even full-on RGB desktop fans, or go crazy with liquid cooling!), pair with other projects, create a custom case... 
Perhaps you'd want to program and attach some status LEDs via the pis' GPIO pins... Maybe you'd like to upgrade from SDcards to faster USB3 drives...
Like machine learning? Why not try to create a mini neural network with your cluster?

Whichever path you choose to travel with this build, you can always HACK! :)

## Budget

| Product                                   | Supplier/Link                         | Cost    |
| ----------------------------------------- | ------------------------------------- | ------- |
| 4 Libre Computer Boards (4GB)             | https://amzn.to/3vwx5ZI               | $220    |
| Network Switch                            | https://amzn.to/3jEL5ha               | $19.79  |
| Power Supply                              | https://amzn.to/3InxF3C               | $30.99  |
| Power Cables                              | https://amzn.to/3icRGPI               | $7.59   |
| Ethernet Cables                           | (Already Own)                         | $0      |
| Keyboard, Monitor, HDMI (for first setup) | (Already Own)                         | $0      |
| microSD Cards                             | (Already Own)                         | $0      |
| Total Including 8.875% NYC Tax            |                                       | $303.08 |
