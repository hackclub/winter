---
name: "esjiko"
project: "Weather Lamp"
---

# Project Name
Weather Lamp

## Summary

I am going to build a RGB weather lamp that changes color depending on the temperature range and sun/moon by using the openweathermap.org API. 
I'm excited to build this because this is my first hardware project and just the idea of making something that I can use in my day to day life is so exciting! 
Instead of having to use my phone to check the weather in the morning, I can just look at the lamp which in my opinion is much cuter and convenient.

## Plan

To make this lamp I will follow the guide mukesh-sankhla on electro-maker made. (https://www.electromaker.io/project/view/weather-lamp#items-used-in-this-project) 
To make this project a bit more personal I will design my own 3D model in solidworks. My current idea for the lamp model is Snoopy sleeping on top of his doghouse.
I'll put the circuit board on the base of the doghouse and the doghouse will change colors depending on the temperature.

Getting into the specifics, first, I will buy the hardware components needed for this project- the WizFi360, LED strip, white filament, soldering kit, and connecting wire.

Next, I will design the doghouse model in solidworks and print them on my brothers 3D printing machine using the printer filament. 

For Snoopy, since I'm new to 3D modeling I will use a 3D model of Sleeping Snoopy FRANK1927 made on cults3d. (https://cults3d.com/en/3d-model/art/sleeping-snoopy)

Afterwards I will follow the circuit connection guide mukesh-sankhla gave and connect the WizFi 360 and WS2812B LEDs using the connecting wires and soldering kit.

Fourth, I will assemble the parts together and glue the top and base of the 3D model with the circuit board inside with super glue.

Fifth, I will go to openweathermap.org and copy the API key.

Sixth, on my computer I'll download WizFi360 Arduino Library, Adafruit_NeoPixel library, and Arduino Code.

On line 20 of the Arduino Code I will edit the code to connect it to my wifi.

And then on line 153 I will edit the code to make the time zone match mine. 

Next, on line 282 I will input my location-Longitude and Latitude and imput my theopenweathermap API key.

Afterwards, I will connect the lamp to my computer using a MicroUSB cable and compile and upload the code.

This will then allow the lamp to connect with my wifi and display the output.


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
|  WizFi360-EVB-Pico | https://www.mouser.com/ProductDetail/WIZnet/WizFi360-EVB-Pico?qs=t7xnP681wgUiMgEF215xMA%3D%3D&mgh=1 | $14.87 ($6.88 + $7.99 shipping) |
| WS2812B LED Strip | https://www.amazon.com/BTF-LIGHTING-Flexible-Individually-Addressable-Non-waterproof/dp/B01CDTEJBG?crid=2HQATETF4F1NH&keywords=ws2812b+led+strip&qid=1666787396&qu=eyJxc2MiOiI0Ljc3IiwicXNhIjoiNC41NCIsInFzcCI6IjQuNTMifQ%3D%3D&sprefix=WS2812B+,aps,273&sr=8-1-spons&psc=1&linkCode=sl1&tag=0420043-20&linkId=c6479d2b3f3b1b098f9520945ebf8628&language=en_US&ref_=as_li_ss_tl  | $32.99 |
| 3D Printer | already own  | $0.00 |
| White Filament | https://www.amazon.com/OVERTURE-Filament-Consumables-Dimensional-Accuracy/dp/B07PGZNM34?crid=15ZVL8IULP9NF&keywords=white%2B3d%2Bprinter%2Bfilament&qid=1666799249&qu=eyJxc2MiOiIzLjU5IiwicXNhIjoiMy42NiIsInFzcCI6IjMuNDYifQ%3D%3D&sprefix=white%2B3d%2B%2Caps%2C364&sr=8-1-spons&linkCode=sl1&tag=0420043-20&linkId=d55fce10b65526847533fb76b12ad66e&language=en_US&ref_=as_li_ss_tl&th=1  | $19.99 |
| Solder Kit | https://www.amazon.com/Soldering-Premium-Ceramic-Adjustable-Temperature/dp/B0B3D96MN6?crid=3R6JFVA3RWNVE&keywords=Solder+kit&qid=1666799594&qu=eyJxc2MiOiI1LjI3IiwicXNhIjoiNC43OCIsInFzcCI6IjQuNDUifQ%3D%3D&sprefix=solder+kit,aps,284&sr=8-1-spons&psc=1&linkCode=sl1&tag=0420043-20&linkId=a5fb172adc76d2208bd6184caf31c15d&language=en_US&ref_=as_li_ss_tl#customerReviews  | $21.99 |
| Connecting Wire | https://www.amazon.com/Electrical-Flexible-Silicone-different-automotive/dp/B07G744V5Z?crid=1FEI2VYTSMRHY&keywords=color%2Bwire&qid=1666799583&qu=eyJxc2MiOiI0Ljk1IiwicXNhIjoiNC42NiIsInFzcCI6IjMuOTYifQ%3D%3D&sprefix=color%2Bwire%2Caps%2C294&sr=8-1-spons&linkCode=sl1&tag=0420043-20&linkId=c8da6d601de2ec6f89e27dafeab4df5a&language=en_US&ref_=as_li_ss_tl&th=1  | $15.99 |
| Super glue cyanoacrylate | already own | $0.00 |
| Total           |                                       | $105.83 |
