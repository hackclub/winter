---
name: "@Gspidey123"
project: "Mechatronic Hand"
---
 
# Mechatronic Hand
 
## Summary
 
I recently learnt of the existence of smart materials such as nitinol, and when I did a quick search, was shocked to find that it was accessible to me. This made me wonder why I haven’t seen it in use more. Many people have attempted making moveable electronic hands, however, I wanted to try something new in this field by using nitinol to electronically control the movement.  I want to experiment to see if this could be the future of bionics. 

## Plan
Firstly, I can use a simple string-based hand that can be 3D printed. My brother bought a 3d printer for the house, so I can use an existing file to do this. I have attached a picture of an example hand file from thingiverse, which is what I will probably use. However, I will use fishing wire as a stronger alternative to string for the tendons. 

![Example picture of 3D printed hand from Thingiverse](https://user-images.githubusercontent.com/122729898/212999254-8a3df9b5-cd98-42a0-994e-6cc87d7454af.png)


Since this requires very precise 3D printing, I would like to first upgrade the 3D printer to have automatic bed levelling to make this possible (as my 3D printer currently faces some acuraccy issues such as layer distortion and will not be capable of it ). I have already bought some cheap nitinol wire and made a quick model using simply a switch and a battery (picture shown below).

![Simple model of moving hand with cardboard and nitinol](https://user-images.githubusercontent.com/122729898/213000244-588885e6-2c4d-42c0-8eb8-2a77f40758a7.jpeg)


It showed potential, but the contraction was not enough for the full range of motion. So, I instead plan to use nitinol springs to act as the muscles of the hand (which allows for a much greater contraction) and an Arduino microcontroller to make it fully automatic (by using it as multiple electronic switches).  I can also add things like a joystick to control it, or a camera with a program that allows it to mirror my hand. Some extra functions for the hand I plan are to make it solar powered if possible (by using some solar cells as the power source), to promote sustainable energy usage. And I want it to have a child friendly aesthetic by using rainbow colours. Also, I can use an Arduino Wi-fi module to connect this to a controller or camera or simply to the computer (all of which I already own). 
 
 
## Budget
 

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 6 x 2 way nitinol springs | https://nexmetal.com/products/nitinol-2-way-memory-spring-w075-d65?variant=31857719672874 | $146.77|
| Arduino Uno| https://www.amazon.co.uk/ELEGOO-Arduino-Arduino-Compatible-Transfer-Operation/dp/B09JWFTZ2V/ref=sr_1_4?crid=8WR048OJR0MU&keywords=arduino+uno&qid=1673816874&sprefix=arduino+uno%2Caps%2C81&sr=8-4 | $18.33|
| Rainbow filament| https://www.amazon.co.uk/Flashforge-Rainbow-1-75mm-Printer-Filaments/dp/B08ZNBGQ2S/ref=sr_1_1_sspa?crid=1V5RR8JALRWLI&keywords=3d%2Bprinter%2Bglow%2Bin%2Bthe%2Bdark%2Bfilament&qid=1673816981&sprefix=3d%2Bprinter%2Bglow%2Bin%2Bthe%2Bdark%2Bfilament%2Caps%2C64&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1 | $24.45 |
| 8 pieces solar panels| https://www.amazon.co.uk/RUNCCI-YUN-60X80mm-Polycrystalline-Projects-Connector/dp/B08RMJLHC5/ref=sr_1_3_sspa?crid=2ANN39T3GMXC8&keywords=solar+panel+arduino&qid=1673817148&sprefix=solar+panel+arduino%2Caps%2C87&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1 | $1.95 dollars |
| Arduino wifi module | https://www.amazon.co.uk/AZDelivery-ESP8266-Wireless-Transceiver-including/dp/B078J7LDLY/ref=sr_1_2_sspa?crid=3EWSPEKQN6W54&keywords=wifi%2Bmodule%2Barduino&qid=1673817251&sprefix=wifi%2Bmodule%2Barduin%2Caps%2C109&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1 | $4.87 dollars |
|Touch sensor bed levelling| https://www.amazon.co.uk/Geeetech-accessory-automatic-levelling-printer/dp/B08P51G69Z/ref=sr_1_1_sspa?crid=1V5ZLKBYKW65U&keywords=3d+printer+blt+touch&qid=1673817450&sprefix=3d+printer+blt+touch+%2Caps%2C102&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1 | $21.03 |
| Fishing wire (for tendons) | https://www.amazon.co.uk/s?k=fishing+wire&crid=282XH584ZR73&sprefix=fishing+wire%2Caps%2C181&ref=nb_sb_noss_1| $9.40|
| 3D Printer- | N/A| Already owned |
| Soldering kit | N/A| Already owned |
| Arduino power module| N/A| Already owned |
| Chocolate blocks (to secure nitinol)| N/A| Already owned |
| Total           | | $246.80|
