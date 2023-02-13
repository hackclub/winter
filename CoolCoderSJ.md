---
name: "@CoolCoderSJ"
project: "Assisting Colorblind Drivers, Motion Lights - Total At End"
---

# Assisting Colorblind Drivers

## Summary

Red-green colorblindness is the most popular type of colorblindness. In this form of colorblindness, drivers may not see red or green traffic light colors clearly enough and that may cause a problem while on the road. A small device that utilizes a camera that can take photos of the road in front while driving and uses machine learning to parse the image and identify traffic light colors correctly can help with this problem and make driving for protans (people who are red-green colorblind) easier.

## Plan

- Use a live camera feed with opencv (Python) to parse frames of the road
    - The camera will be taped to the windshield
- Use tensorflow to train a model to identify traffic lights in a frame
- Announce the colors detected to the car's audio system using an aux-to-aux cable

[Benchmarks](https://www.hackster.io/news/benchmarking-tensorflow-and-tensorflow-lite-on-the-raspberry-pi-43f51b796796) ([here's another one](https://qengineering.eu/deep-learning-with-raspberry-pi-and-alternatives.html#imPageRow_9)) show the raspberry pi is very slow (even with TFLite) to run tensorflow- which is why I'll be using the Coral USB Accelerator to speed models up.

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi 4 Model B (8 GB)   | Already own | $0  |
| microSD Card, reader | Already own | $0 |
| power supply | already own | $0 |
| Google Coral USB Accelerator (including shipping and tax) | https://www.mouser.com/ProductDetail/Coral/G950-01456-01?qs=sGAEpiMZZMve4%2FbfQkoj%252BNzzHFZgWGqIphwvwTL5xvk%3D | $73.82 |
| USB Camera | Already own | $0 |
| aux-to-aux cable | Already own | $0 |
| Amazon Shipping | | Free |
| Total           |                                       | $73.82 |


# Motion Based Lights

## Summary

For nights, it might be overkill to turn on the entire room lights. When I get up at night, instead of turning on the bedroom lights, I'll have an LED strip light up on the side of my bed. This LED strip will be controlled by an ESP8266 based board that triggers when motion is sensed. This could also be used for fun or decoration!

## Plan
For the LED strip:
- I'll use the same board from last project, but this time, use IR transmitters to talk to existing LED strips instead. 
- I'll use an IR receiver to record the button's signals and save them
- Then I'll use the IR transmitter to send those signals to the strip

## Budget

The following has amounts for 2 beds, and the total cost is listed for each part, not the individual amount.

| Product | Supplier/Link | Cost |
| --------------- | ------------------------------------- | ------ |
| Wio Link (x2) | https://www.arrow.com/en/products/102110037/seeed-technology-limited | $13.92 |
| Gesture Senosr (x2) | https://www.arrow.com/en/products/101020083/seeed-technology-limited?q=101020083 | $22.02 |
| Arrow Other Costs (taxes, shipping) | | Free |
| IR Receiver | https://www.arrow.com/en/products/101020016/seeed-technology-limited?q=101020016 | $3.76 |
| IR Transmitter (x2) | https://www.arrow.com/en/products/101020026/seeed-technology-limited?q=101020026 | $7.48 |
| LED Strip (x2) | Already own | $0 |
| Total | | $47.18 |


# Total - $121
