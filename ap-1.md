---
name: "@ap-1, @EmperorParzival"
project: "3D RGB Visualizer"
---

# Project Name
3D RGB Visualizer

## Summary

The visualizer will be constructed using a matrix of 8x8x8 individually-addressable RGB LEDs. It will be controlled by an Arduino Nano and powered by a 5V 20A power supply. The purpose of the visualizer is to take a variety of inputs and generate a colorful 3D visualization for those inputs. The majority of this will be programmed in Arduino C by us, using the FastLED library. Here are some of the features we will try to implement:
- A music visualizer: Given an audio file, the LED matrix will create waves that sync with the music.
- A 3D visualizer: Given a 3D object file, the LED matrix will try to display that object to the best of its ability with 8px resolution.
- A weather visualizer: The visualizer will generate a sky that represents the current weather. For example, a rain animation on rainy days, a lighting animation during thunderstorms, etc.
- A number of animations and presets, including a disco ball, infinite terrain generation (Minecraft chunk loading style) using perlin/simplex noise, and others we haven't come up with yet!

## Plan

While both of us (mostly me) have general programming experience and experience using Arduino C, constructing a circuit of this complexity is new to both of us. There are a number of tutorials we found on YouTube, and we plan on using information from all of them in order to build our design.
- https://www.youtube.com/watch?v=ciaFar8nfHc
- https://www.youtube.com/watch?v=R-arZ31-zJo
- https://www.youtube.com/watch?v=T5Aq7cRc-mU

Our visualizer is based around individually-addressable RGB LEDs. This means that multiple LEDs can be chained together and controlled individually using a single signal, which reduces the complexity of the design significantly. Still, the individual RGBs have to be soldered together, which is why we included a soldering kit. Neither of us had experience with soldering before, even though this project relies on it heavily. We're both very eager to be introduced to soldering through this project, and we both hope we can figure it out relatively quick! Apart from soldering the leads of the RGB LEDs together to make the 8x8x8 matrix, the Arduino Nano, power supply jack, potentiometer, and power supply jack will also be soldered to the breadboard in some way or another. The chosen Arduino comes with headers to aid in this purpose. The final stage is adding a case for the design! I have an Autodesk Fusion 360 subscription through my school, but we have no way to actually 3D print the case.

We know that designing the case will likely take multiple iterations and a lot of time, so we considered sending our 3D models to a company to have them printed out and shipped to us. The problem with this, however, is that this model of developing a case, testing it out, designing a new one, sending it to a company, getting it shipped back to us, and testing the new one out is a very slow process and not very conducive to rapid prototyping. First of all, we won't be able to predict the costs upfront, which was a requirement to recieve the grant. Secondly, we'd have to pay shipping and wait for the new case to arrive every time we made a design. We decided that if we went with that, we probably wouldn't be able to finish within 10 days. Instead, because it was in our combined budget, we opted for buying a 3D printer and filament instead. It may take some time to assemble, but it will save a lot of time in developing cases.

## Budget

| Product | Supplier/Link | Cost |
| - | - | - |
| Soldering Kit with Multimeter | https://www.amazon.com/Soldering-Digital-Multimeter-Bundled-Plusivo/dp/B08SWHGTQH | $34.18 |
| Ender 3 3D Printer with PLA Filament | https://www.amazon.com/Creality-Ender-Printer-Filament-1-75mm/dp/B08FSP19XD | $210.99 |
| Male and Female Pin Headers | https://www.amazon.com/DIYhz-Straight-Connector-Computer-Breadboard/dp/B07BS126FK/ | $9.99 |
| Silver Plated Copper Wire | https://www.amazon.com/Darice-3959-08-Silver-Plated-Copper/dp/B0051WT7NS/ | $7.00 |
| Solderable Breadboards | https://www.amazon.com/EPLZON-Solder-able-Breadboard-Electronics-Compatible/dp/B09WZY8H3X/ | $12.59 |
| Breadboard Jumper Wires | https://www.amazon.com/EDGELEC-Breadboard-Optional-Assorted-Multicolored/dp/B07GD2BWPY/ | $6.99 |
| Arduino Nano with Cable | https://www.amazon.com/ATmega328P-Microcontroller-Board-Cable-Arduino/dp/B00NLAMS9C/ | $11.99 |
| 11x 50pcs Individually Addressable 8mm RGB LEDs (PL9823 F8) | https://www.ebay.com/itm/182094821868 | $131.78 |
| 3 Terminal Toggle Switch | https://www.amazon.com/HiLetgo-AC125V-Terminals-Position-Toggle/dp/B079JBF815/ | $6.49 |
| 3 Terminal 10k Potentiometer | https://www.amazon.com/BOJACK-Terminals-Potentiometer-Connector-Cable（Pack/dp/B0868TRS94/ | $6.99 |
| DC Power Connector Plug Jack | https://www.amazon.com/AiTrip-20pcs-Connector-Female-5-5x2-1mm/dp/B081DYQSC9/ | $5.99 |
| 2 Pole PCB Mount Screw | https://www.amazon.com/uxcell-20Pcs-Pitch-Mount-Terminal/dp/B00I00OHHY/ | $7.99 |
| 5V 20A Power Supply | https://www.amazon.com/ALITOVE-Transformer-Adapter-Converter-Charger/dp/B06XK2DDW4/ | $19.99 |
| Power Cord for Power Supply | https://www.amazon.com/ALITOVE-Universal-Adapter-Transformer-Replacement/dp/B07CWS4BGC/ | $8.99 |
| Shipping | | $13.96 |
| Total | | $495.91 |
