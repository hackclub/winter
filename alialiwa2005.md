---
name: "@alialiwa2005"
project: "Raspberry Web Services (RWS) | DIY Homemade AWS Cloud"
---

# Project Name
Raspberry Web Services (RWS) | DIY Homemade AWS Cloud
## Summary

I am going to build a hackable, Kubernetes-based, (mini)-super-computer Arm-powered private cloud. 

Instead of hosting a site, Minecraft server, or web app on a cloud service like AWS, 
I'm excited to build a hackable, Kubernetes-based, (mini)-super-computer Arm-powered private cloud, while exploring redundancy, load-balancing, containers, orchestration, and physical networking, from a hands-on hardware perspective!

I can't wait to build a DIY cluster of mini-servers at home! It's so wonderful to think of all the possibilities of this build!

What's more fascinating is how little electricity is used by the build. Also, this project doesn't require much physical space, 
and is versatile in many ways!

I am certain that this is will turn out to be an awesome and unique project, and I can't wait to start making it this winter.

While this project is about making, it is also an awesome learning opportunity for me, in terms of the hardware side of computing and cloud, such as physical networking, as well as the software side of dev-ops, 
such as using Kubernetes to manage separate pieces of hardware that make up a cluster in accomplishing tasks in unison... that is just mind-blowing to me!

What's even better is that unlike just deploying instances on the AWS dashboard, I get to build my own cloud, comparable to the actual Amazon Web Services, from scratch... starting with the hardware, inspecting the physical computer boards and chips, physically networking the nodes, even designing a stylish case for the cloud! :)

I always wanted to build a super-computer. I guess Winter of Making will finally make this dream a part of my New Year's Hacking bucket list! Hooray!

## Plan

For this project, you'll need 4 Raspberry Pis (preferably with at least 4 gigabytes of RAM). 
These will be the heart of the build, and should have a solid amount of memory to handle tasks comfortably (ideally at least 4 gigabytes. 
The 8 gigabytes model will be more stable and able to handle more tasks, but is about 20 dollars more expensive).

Why Pis? They're UK-made, are great in terms of build quality, and are relatively affordable overall. 
They also don't use much electricity and are surprisingly powerful for their credit-card-size.

Also, Pis have ARM64 CPUs, just like AWS Graviton instances. This is awesome because it means that almost anything that can run on AWS EC2-A1 
or other Graviton-powered deployments can be deployed at home, on your own DIY AWS (RWS) cloud! :)

Aside from these, you also need accessories, like power supplies, storage (these can be MicroSD Cards, at least 16GB, ideally Class-10 32GB), ethernet cables, and a cluster stand/stackable cases for organization.

You'll also need a laptop or PC for the initial setup of the Pis.

Some other optional but recommended items are:

- A network switch, so that the pis all connect to the ethernet switch, which ultimately links to your router via a 
single network cable.

- Cooling: This is optional but recommended if you're planning on overclocking and/or running many resource-intensive services. 
  Cooling can be passive cooling via heatsinks, active cooling with fans, or even liquid cooling!

---

Step 1: Order materials (full list at the bottom), then await items' arrival.

Step 2a: Create a custom case/stand, or buy one.

Step 2b: Attach Raspberry Pis to the cluster stand/case(s), and attach heatsinks/fans (cooling) if applicable.

Step 3: On your PC, install Raspberry Pi imager.

(Repeat Steps 4 - 16 for each Pi)

Step 4: Insert your SD card into your computer.

Step 5: On Raspberry Pi Imager, select Raspberry Pi OS lite (32-bit or 64-bit), and select your SD card (make sure to select the correct storage device).

Step 6: Write the image to your SD card.

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

Step 15: Eject the SD card from the PC/laptop and plug the SD card into Pi, connect ethernet, and power.

Step 16: ssh into the Pi & install Kubernetes.

Step 17: Set up the first pi as the Kubernetes "master."

Step 18: Set up the other pis as Kubernetes "nodes."

Step 19: Experiment & hack with Kubernetes! Congrats on building your private cloud!

Step 20: Overclock! (or underclock, if you want to achieve even more energy efficiency)... 
Install monitoring software, deploy websites, block ads on your network with your own PiHole-powered DNS,
link to RGB lights (or even full-on RGB desktop fans, or go crazy with liquid cooling!), pair with other projects, create a custom case... 
Perhaps you'd want to program and attach some status LEDs via the pis' GPIO pins... Maybe you'd like to upgrade from SDcards to faster USB3 drives...
Like machine learning? Why not try to create a mini neural network with your cluster?

Whichever path you choose to travel with this build, you can always HACK! :)

## Budget

| Product                         | Supplier/Link                         | Cost    |
| ------------------------------- | ------------------------------------- | ------- |
| 4 Raspberry Pi 4 4GB Ram        | https://bit.ly/2ZVDImM                | $220    |
| 4 Power Supplies                | https://bit.ly/3WwznmU                | $32     |
| 6 Ethernet Cables               | https://bit.ly/3WtkAte                | $3.23   |
| 4 MicroSD Cards                 | (Already Own)                         | $0      |
| Customized Case                 | (Already Own Supplies)                | $0      |
| Gigabit Ethernet Network Switch | (Already Own)                         | $0      |
| Router for Project-Only Network | (Already Own a Spare Router)          | $0      |
| Total Including NYC Tax (8.875%)|                                       | $277.89 |
