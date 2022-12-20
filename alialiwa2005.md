---
name: "@alialiwa2005"
project: "RWS | DIY AWS Cloud"
---

# Project Name
RWS | DIY AWS Cloud
## Summary

I am going to build a hackable, Kubernetes-based, (mini)-super-computer Arm-powered private cloud. 

Instead of hosting a site, minecraft server, or webapp on a cloud service like AWS, 
I'm excited to build a hackable, Kubernetes-based, (mini)-super-computer Arm-powered private cloud, while exploring redundancy, load-balancing, containers, orchestration, and physical networking, from a hands-on hardware perspective!

I can't wait to build a DIY cluster of mini-servers at home! It's so wonderful to think of all the possibilities of this build!

What's more fascinating is how little electricity is used by the build. Also, this project doesn't require much physical space, 
and is versatile in many ways!

I am certain that this is will turn out to be an awesome and unique project, and I can't wait to start making it this winter.

While this project is about making, it is also an awesome learning opportunity for me, in terms of the hardware side of computing and cloud, such as physical networking, as well as the software side, 
such as using Kubernetes to manage separate pieces of hardware that make up a cluster in accomplishing tasks in unison... that is just mind-blowing to me!

I always wanted to build a super-computer. I guess Winter of Making will finally make this dream a part of my New Year's Hacking bucket-list! Hooray!

## Plan

For this project, you'll need 4 Raspberry Pis. They will be the heart of the build. 

They're also realitively affordable overall, don't use much electricity, and are surprisingly powerful for their credit-card-size.

Aside from these, you also need accessories, like power supplies, storage, ethernet cables, and a cluster stand/stackable cases for organization.

You'll also need a laptop or PC for initial setup of the Pis.

Some other optional but reccomended items are:

- A network switch, so that the pis all connect to the ethernet switch, which ultimately links to your router via a 
single network cable.

- Cooling: This is optional but reccomended if you're planning on overclocking and/or running many resource-intensive services. 
  Cooling can be passive cooling via heatsinks, active cooling with fans, or even liquid cooling!

---

Step 1: Order materials (full list at the bottom), then await items' arrival.

Step 2: Attach Raspberry Pis to the Cluster Stand/Case(s), and set up heatsinks/fans (cooling) if applicable.

Step 3: On your PC, install Raspberry Pi imager.

(Repeat Steps 4 - 16 for each Pi)

Step 4: Insert your SD card to your computer.

Step 5: On Raspberry Pi Imager, select Raspberry Pi OS lite (32 bit or 64 bit), select your SD card (make sure to select the correct storage device).

Step 6: Write the image to your SD card.

Step 7: Insert your SD card to a Pi & power on Pi.

Step 8: After a few minutes (3-5 minutes), unplug power from Pi.

Step 9: Take out SD card from Pi & insert into PC/laptop

Step 10: Your SD card should be named "boot." Open it, there should be a file called cmdline.txt

Step 11: At the end of the first line of cmdline.txt, paste this: cgroup_enable=memory cgroup_memory=1

** For step 12, please note that your ip setup may be different, the format is (pi static ip):(router/gatwayip):(subnet mask):(pi hostname):eth0:off

** Also, for step 12 be sure to change the static ip and the hostname for each pi.

Step 12: After pasting, assign your pi a static ip by typing this: ip=192.168.1.121:192.168.1.1:255.255.255.0:cloudone:eth0:off

Step 13: Open config.txt, scroll to the bottom of the file to the "all" section, type arm_64bit=1

Step 14: Create a new file without an extenstion, named ssh

Step 15: Eject SD card from PC/laptop and plug SD card into Pi, connect ethernet and power.

Step 16: ssh into the Pi & install Kubernetes.

Step 17: Set up the first pi as the Kubernetes "master."

Step 18: Set up the other pis as Kubernetes "nodes."

Step 19: Experiment with Kubernetes! Congrats on building your private cloud!

Step 20: Install monitoring software, deploy your own websites, block ads on your network with PiHole,
link to rgb lights, pair with other projects, create a custom case... perhaps you'd want to program and attach some status leds via the pis' GPIO pins... Whichever path you choose to travel with this build, you can HACK! :)

## Budget

| Product                         | Supplier/Link                         | Cost   |
| ------------------------------- | ------------------------------------- | ------ |
| 4 Raspberry Pi 4 4GB Ram        | https://bit.ly/2ZVDImM                | $220   |
| 4 Power Supplies                | https://bit.ly/3WwznmU                | $32    |
| 4 Ethernet Cables               | (Already Own)                         | $0     |
| 4 MicroSD Cards                 | (Already Own)                         | $0     |
| Customized Case                 | (Already Own Supplies)                | $0     |
| Gigabit Ethernet Network Switch | (Already Own)                         | $0     |
| Total (Before Taxes)            |                                       | $252   |
