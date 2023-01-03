---
name: "@VelocityDeisgn"
project: "Nature's Eye - A Weather System and Bird Watcher"
---

# Project Name

## Summary

I'm planning to build an all-in-one Weather System, Bird Cam, and Home Dashboard with Home Assistant, Weather Sensors, and a Google Pixel.

## Plan

Currently, I have a homeassistant setup running on my home server.
We have a small forrest in our backyard, and it is often visited by birds.
Additionally, Oklahoma is known for (if anything) weird weather patterns.

So, I'd like to set up a small setup out in this forest to monitor the weather, and to get some good footage of birds

### Solving some problems/How everything will work
#### Humidity
Humidity is kinda an issue for electronics, so I'm using a plastic enclosure to sheild the components from humidity.

#### Power Management
These components require power, and I have to get it from somewhere. For power, I'm using a combination solar panel and battery pack I found from amazon. This should work for now, but I hope to potentially examine adding more batteries, or maybe even completely overhauling this system.

#### Connectivity
##### Wireless Connectivity
The whole project had a major problem: The forrest is outside of the WiFi range. To solve this issue, I'm using a Pixel 5, so it can connect over Cellular Data to my Home Assistant instance.

##### Connectivity Between Pixel and Sensor
Since the pixel can't natively connect to the sensor, I'll be using [this library](https://github.com/3cky/usb-i2c-android) with a custom-made app and the FT232H chip to connect to the chip and "phone home."

#### Supply Shortages
Another driving factor in using a Google Pixel instead of a Raspberry Pi is the ongoing supply chain issue. Raspberry Pi's are extremely hard, if not impossible, to find. That, and the cost for a camera that's comprable to the Pixel and a Cellular modem would be even more expensive than the pixel itself.

## Ideas for the Future
 - Add AI bird detection? (As seen in The MagPi)
 - Create Mastodon Bird Watcher Bot? (Powered by the AI)
 - Add a Humidity Sensor?
 - Add a Wind Speed Sensor?
 - Add a bird perch near it?

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| MPL3115A2 | https://www.adafruit.com/product/1893 | $9.95 |
| Google Pixel 5 | https://swappa.com/listing/view/LWER94603 | $134 |
| FT232H  | https://www.adafruit.com/product/2264 | $14.95 |
| Solar Panel + Battery Pack | https://www.amazon.com/Portable-20000mah-Waterproof-Flashlights-CellPhones/dp/B07NVM4L1C/ | ~$16.80 (Deal Applied) |
| USB-C Hub | Owned | ? |
| Micro-usb, USB-C Cable | Owned | ? |
| Wood (For Enclosure) | Owned | ? |
| Humidity Enclosure (Made from Plastic) | Owned | ? |
| Additional Decorations for Enclosure | Owned/Will Be Purchased from own funds if more needed | ? |
| Shipping/Tax | See Above | $6.00 (AdaFruit) + $7.98 (Swappa) |
| Total           |                                       | $193.91 |
