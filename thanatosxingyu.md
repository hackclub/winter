---
name: "@ThanatosXingYu  "
project: "Smart toolbox"
---

# Smart toolbox -- a box that can change our life a bit

## Summary
Hi there!
As I said in the title, this box can keep people away from danger and make our life more convenient. 

When I enter my home, my phone automatically connects to the raspberry pi in the box. 

Then when the Raspberry Pi recognizes the Bluetooth Address(BD_ADDR, a unique 48-bit identifier assigned to each Bluetooth device by the manufacturer) of the device, it will display the customized content on the 40" TV screen. *For each person, the displayed content is different.* For example, if it identifies that the BD_ADDR is my father's device, the TV will display today's stock, and for my mother, it will display today's WalMart promotion :)

In addition, it can also recognize and answer our questions through Chat-GPT's api and voice recognition module. I will set a keyword "Hello, box" for it to prevent wake-up by mistake.    
For example, when I say "Hello box, how's the weather today ", it will use GPS to determine my location and then show today's weather on TV screen.
Of course, when Bluetooth is disconnected, it will also send messages to the mobile phone via WiFi.

At the same time, its own 3.5" screen will also display the current status, such as how many device links, wifi signal strength, system load, etc


## Plan
### STEP 1
Apply for some apis, such as Chat-GPT, weather, or stocks

### STEP 2
Find the right place, connect the raspberry pie to the TV, and connect it to a stable power supply

### STEP 3
Use a laptop to connect raspberry pi，download and then install Raspberry Pi imager  .

### STEP 4
Write a demo program for test. Then write true programs in Python or C (I like Python)

### STEP 5
Connect the wifi signal at home and set the BD_ADDR of each device. Then go out and enter the door for test again.

### STEP 6
Assemble All!   

## Budget


| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi 4B + 32 GB TF + micro-HDMI wires + Type-C Power + Acrylic shell   | [TMALL](https://detail.tmall.com/item_o.htm?abbucket=5&id=624594173139&skuId=4928005546003) | $226.76  |
| 3.5" display | [TMALL](https://detail.tmall.com/item_o.htm?id=615266190445&skuId=4502665842552)  | $6.92 |
| Voice Recognition Module for R-Pi| [TMALL](https://detail.tmall.com/item_o.htm?id=628429845784)| $14.60 | 
| 40" TV display | Already Own | $0 |
|Laptop | Already Own | $0 |
| Dupont Line | Already Own | $0 |
| Shipping | FREE | $0|
| Tax | FREE | $0 |
| Total | | $248.28 |

That's all, thxxxx :)