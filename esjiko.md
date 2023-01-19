---
name: "esjiko"
project: "Weather Lamp"
---

# Project Name
Weather Lamp

## Summary

I am going to build a RGB weather lamp that changes color depending on the temperature range and sun/moon by using the openweathermap.org API. 
I'm excited to build this because this is my first hardware project and just the idea of making something that I can use in my day to day life is so exciting! 
Instead of having to use my phone to check the weather in the morning, I can just look at the lamp which in my opinion is much cuter and convenient. I will also add a switch to the lamp to turn it off and on when needed.

## Plan

To make this lamp I will follow the guide mukesh-sankhla on electro-maker made. (https://www.electromaker.io/project/view/weather-lamp#items-used-in-this-project) 
To make this project a bit more personal I will design my own 3D model in solidworks and add a switch to control the lamp. My current 3D model idea for the lamp model is Snoopy sleeping on top of his doghouse. I'll put the breadboard and circuit board on the base of the doghouse and the doghouse will change colors depending on the temperature.

Getting into the specifics, first, I will buy the hardware components needed for this project- the WizFi360, LED strip, white filament, soldering kit, connecting wire, a micro USB cable, jumper wires, a breadboard, and an on and off switch.

Afterwards, I will design the doghouse model in solidworks and print them on my brothers 3D printing machine using the printer filament. 

For Snoopy, since I'm new to 3D modeling I will use a 3D model of Sleeping Snoopy FRANK1927 made on cults3d. (https://cults3d.com/en/3d-model/art/sleeping-snoopy)

Next, I will connect the WizFi 360 to the breadboard using a male-to-male jumper wire.

Following that, I will connect the data pin of the LED strip to a digital pin on the WizFi 360 using the soldering kit and connecting wires. I will use the circuit connection guide mukesh-sankhla created. (https://www.electromaker.io/uploads/images/projects/2829/story/medium/Mukesh_Sankhla_story_image_1666866936904869.png)

I will then connect the power and ground pins of the LED strip to the power and ground rails of the breadboard by locating the VCC and GND pins on the LED strip and then inserting the VCC pin into the power rail of the breadboard and the GND pin into the ground rail of the breadboard. I will use female-to-female jumper wires.

To control the circuit I will use the on/off switch and use this video (https://www.youtube.com/watch?v=xDDYHzrV1QM&ab_channel=ENGRTUTOR) as a guide. I will connect the switch to the digital pin on the WizFi 360 and the ground rail on the breadboard. I will use a male-to-female jumper wire for this part.

Once I finish I will assemble and glue (using super glue) the parts together with the circuit board and breadboard being inside of the lamp on the base.

Afterwards, I will go to openweathermap.org and copy the API key.

Next, on my computer I'll download WizFi360 Arduino Library, Adafruit_NeoPixel library, and Arduino Code.

On line 20 of the Arduino Code I will edit the code to connect it to my wifi.

And then on line 153 I will edit the code to make the time zone match mine. 

Following that, on line 282 I will input my location-Longitude and Latitude and imput my theopenweathermap API key.

Finally, I will connect the lamp to my computer using a MicroUSB cable and compile and upload the code.

This will then allow the lamp to connect with my wifi and display the output. 


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 3D Printer | already own  | $0.00 |
| Micro USB cable | https://www.adafruit.com/product/592 | $2.95 |
| On/Off Switch | https://www.adafruit.com/product/1443 | $1.50 |
| Micro USB cable + On/Off Switch total | | $19.84 ($4.45 subtotal + $14.36 shipping + $1.03 tax) |
|  WizFi360-EVB-Pico | https://www.mouser.com/ProductDetail/WIZnet/WizFi360-EVB-Pico?qs=t7xnP681wgUiMgEF215xMA%3D%3D&mgh=1 | $15.69 ($6.88 + $7.99 shipping + $0.82 sales tax) |
| WS2812B LED Strip | https://www.amazon.com/BTF-LIGHTING-Flexible-Individually-Addressable-Non-waterproof/dp/B01CDTEJBG?crid=2HQATETF4F1NH&keywords=ws2812b+led+strip&qid=1666787396&qu=eyJxc2MiOiI0Ljc3IiwicXNhIjoiNC41NCIsInFzcCI6IjQuNTMifQ%3D%3D&sprefix=WS2812B+,aps,273&sr=8-1-spons&psc=1&linkCode=sl1&tag=0420043-20&linkId=c6479d2b3f3b1b098f9520945ebf8628&language=en_US&ref_=as_li_ss_tl  | $32.99 |
| White Filament | https://www.amazon.com/OVERTURE-Filament-Consumables-Dimensional-Accuracy/dp/B07PGZNM34?crid=15ZVL8IULP9NF&keywords=white%2B3d%2Bprinter%2Bfilament&qid=1666799249&qu=eyJxc2MiOiIzLjU5IiwicXNhIjoiMy42NiIsInFzcCI6IjMuNDYifQ%3D%3D&sprefix=white%2B3d%2B%2Caps%2C364&sr=8-1-spons&linkCode=sl1&tag=0420043-20&linkId=d55fce10b65526847533fb76b12ad66e&language=en_US&ref_=as_li_ss_tl&th=1  | $20.99 |
| Solder Kit | https://www.amazon.com/Soldering-Premium-Ceramic-Adjustable-Temperature/dp/B0B3D96MN6/ref=sr_1_9?crid=3HI6FZ8RJ1WY&keywords=Soldering+Iron&qid=1674117578&sprefix=soldering+iron+%2Caps%2C218&sr=8-9 | $21.99 |
| Connecting Wire | https://www.amazon.com/Electrical-Flexible-Silicone-different-automotive/dp/B07G744V5Z?crid=1FEI2VYTSMRHY&keywords=color%2Bwire&qid=1666799583&qu=eyJxc2MiOiI0Ljk1IiwicXNhIjoiNC42NiIsInFzcCI6IjMuOTYifQ%3D%3D&sprefix=color%2Bwire%2Caps%2C294&sr=8-1-spons&linkCode=sl1&tag=0420043-20&linkId=c8da6d601de2ec6f89e27dafeab4df5a&language=en_US&ref_=as_li_ss_tl&th=1  | $16.99 |
| Superglue | https://www.amazon.com/Loctite-Liquid-10-Gram-Longneck-234796/dp/B0002YXG78/ref=sr_1_10?crid=3FDOL9YTRNGQN&keywords=super%2Bglue&qid=1674116452&sprefix=super%2Bglue%2Caps%2C152&sr=8-10&th=1 | $3.88 |
| Jumper Wires | https://www.amazon.com/EDGELEC-Breadboard-Optional-Assorted-Multicolored/dp/B07GD2BWPY/ref=sr_1_3?crid=33QA4S8PJ7R5W&keywords=jumper%2Bwires&qid=1674079835&sprefix=jumper%2Bwires%2Caps%2C244&sr=8-3&th=1 | $6.99 |
| Breadboard | https://www.amazon.com/dp/B0040Z4QN8 | $8.75 |
| Amazon products subtotal: | | $118.75 ( $122.58 + $6.17 tax ) |
-
| Total           |                                        $154.28 |
