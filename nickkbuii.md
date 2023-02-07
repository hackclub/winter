---
name: "@nickkbuii"
project: "ASL Translator"
---

#  ASL Translator

##  Summary

I'm making a necklace-based ASL translator with a few friends, since we thought it'd be a good way to give a deaf friend more independence. It'll look like [this](https://cdn.discordapp.com/attachments/1041850456466530375/1062637933426921492/camera_hero-lanyard.png), but with the camera on the top edge (they'd look down and sign into it to have their signs converted to speech), a power button, a potentiometer for volume adjustment, and a speaker inside.

##  Plan

1. We'll connect our camera to our Raspberry Pi using its attached ribbon cable and use the [picamera](https://picamera.readthedocs.io/en/release-1.13/) module to verify that it works.
2. Then, we'll train a hand/face keypoint to ASL gloss LSTM using [this](https://www.youtube.com/watch?v=doDUihpj6ro) video as a reference and export it to our Pi. We'll add keypoint detection to our Pi too, of course. These ASL glosses can then be converted to (very rough) speech on the Pi using the [pyttsx3](https://pypi.org/project/pyttsx3/) text-to-speech module.
3. We'll then wire the rest of our components to our Pi; the speaker and its amp with [this](https://learn.adafruit.com/adafruit-ts2012-2-8w-stereo-audio-amplifier/) tutorial, the battery and its charging board with [this](https://www.circuitbasics.com/how-to-power-your-raspberry-pi-with-a-lithium-battery/#:~:text=Connect%20a%20TP4056%20charge%20controller,3.3V%20and%205.25V) tutorial, and the rest on our own (we know how to wire a button). The main Python script running doing the keypoint detection and running inference with the LSTM model will, of course, be modified to interface with these components.
5. Finally, we'll design and 3D print a case for our necklace-based device (with a loop for the paracord+buckle).

##  Budget
| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 3D Printer + Filament  |  | (Already have)  |
| Raspberry Pi 3 B  |  | (Already have)  |
| Button |  | (Already have)  |
| Raspberry Pi Camera |  | (Already have)  |
| 10K Trimpot Potentiometer |  | (Already have)  |
| Speaker - 40mm Diameter - 4 Ohm 3 Watt | https://www.adafruit.com/product/3968 | $4.95  |
| Stereo 2.1W Class D Audio Amplifier - TPA2012 | https://www.adafruit.com/product/1552 | $9.95  |
| Lithium Ion Polymer Battery - 3.7v 2500mAh  | https://www.adafruit.com/product/328 | $14.95  |
| TP4056 Lithium Ion Battery Charging Module | https://www.amazon.com/Makerfocus-Charging-Lithium-Battery-Protection/dp/B071RG4YWM/ref=as_li_ss_tl?dchild=1&keywords=TP4056&qid=1593227138&sr=8-3&linkCode=ll1&tag=circbasi-20&linkId=957634db00eebaef6169a13464f34088&language=en_US&th=1  | $8.69 |
| MT3608 DC-DC Step Up Boost Converter | https://www.amazon.com/Teyleten-MT3608-Converter-Adjustable-Regulator/dp/B07T7ZCTNK?keywords=MT3608&qid=1638742380&sr=8-3&linkCode=ll1&tag=circbasi-20&linkId=daa4cf9ed17f3416bc1fc95e3b6a970f&language=en_US&ref_=as_li_ss_tl  | $8.69 |
| Pepperell Parachute Cord Buckles 12mm 30/Pkg | https://www.amazon.com/Pepperell-PCBUCK3012-Parachute-Buckles-Black/dp/B015P7YSFU/ref=sr_1_13_sspa?crid=2CSD25J24BTFM&keywords=plastic+buckle&qid=1673662106&sprefix=plastic+buckle%2Caps%2C163&sr=8-13-spons&psc=1&smid=A1LJQB0JA6R2YV&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE5VVg3Q1ExUjJQWlMmZW5jcnlwdGVkSWQ9QTA4Nzg0MTkxVjQ0S1ZEUElaSTJTJmVuY3J5cHRlZEFkSWQ9QTAwODMzMDEzQ0w4SVRPWFJUSU9BJndpZGdldE5hbWU9c3BfbXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ== | $9.14  |
| TECEUM Black Paracord 550 lb (50 ft) | https://www.amazon.com/Teceum-Paracord-Type-III-Black/dp/B0BJGZ8VQC/ref=sr_1_5?crid=2NHXTL4NTMI0M&keywords=black%2Bparacord&qid=1673662277&sprefix=black%2Bparacor%2Caps%2C139&sr=8-5&th=1&psc=1 | $6.99  |
| | Shipping | $14.39 |
| | Tax  | $3.58 |
| | Total| $81.33 |
