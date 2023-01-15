---
name: "@CoolCoderSJ"
projects: "Assisting Colorblind Drivers, Motion Lights - Total At End"
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
| Google Coral USB Accelerator | https://www.amazon.com/Google-Coral-Accelerator-coprocessor-Raspberry/dp/B07R53D12W | $159.99 |
| USB Camera | Already own | $0 |
| aux-to-aux cable | Already own | $0 |
| Amazon Shipping | | Free |
| Total           |                                       | $159.99 |


# Motion Based Lights

## Summary

In the mornings, the house is super dark and it's very easy to stumble and fall. Instead of buying expensive smart lights and a motion switch, hacking into existing switches with sensors and an ESP8266 board would be way easier and cheaper. This is exciting because we would be able to simply walk down the stairs/into rooms in the mornings and the lights would turn on automatically. For nights, it might be overkill to turn on the entire room lights. When I get up at night, instead of turning on the bedroom lights, I'll have an LED strip light up on the side of my bed. This could also be used for fun or decoration!

## Plan
- Wall switches are a simple switch, and a relay would help turn the switches on and off
- I'll connect an ESP8266 (Wio Link) to a relay and gesture sensor
- The relay will be connected to the wires leading to the switch
- The gesture sensor can detect what direction motion moves in
    - The Wio Link will record whether motion is moving into the room or out, and toggle the relay accordingly

For the LED strip:
- I'll use the same board from last project, but this time, use IR transmitters to talk to existing LED strips instead. 
- I'll use an IR receiver to record the button's signals and save them
- Then I'll use the IR transmitter to send those signals to the strip

## Budget

The following has amounts for 2 rooms, 1 staircase (2 receivers), and 2 beds, and the total cost is listed for each part, not the individual amount.

| Product | Supplier/Link | Cost |
| --------------- | ------------------------------------- | ------ |
| Wio Link (x6) | https://www.arrow.com/en/products/102110037/seeed-technology-limited | $41.76 |
| Gesture Senosr (x4) | https://www.newark.com/seeed-studio/101020083/gesture-sensor-arduino-board-rohs/dp/42AK5665 | $29.74 ($0.82 per unit discount with code US10CR23) |
| Relay (x4) | https://www.seeedstudio.com/Grove-Relay.html | $11.16 |
| Newark Shipping | - | $9.99 |
| Arrow Other Costs (taxes, shipping) | | Free |
| Wires | Already own | $0 |
| IR Receiver | https://www.seeedstudio.com/Grove-Infrared-Receiver.html | $3.98 |
| IR Transmitter (x2) | https://www.mouser.com/ProductDetail/Seeed-Studio/101020026?qs=1%252B9yuXKSi8CXRMd7gDJKyw%3D%3D | $8.60 |
| LED Strip (x2) | Already own | $0 |
| Mouser Shipping | | $7.99 |
| Total | | $113.22 |


# Total - $273.21
I'm aware this goes over-budget and will be able to cover the rest of the funds.
