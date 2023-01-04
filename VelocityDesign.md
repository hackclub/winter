---
name: "@VelocityDesign"
project: "Nature's Eye - A Weather System and Bird Watcher + Other Home Improvements"
---

# Nature's Eye

## Summary

I'm planning to build an all-in-one Weather System, Bird Cam, and Home Dashboard with Home Assistant, Weather Sensors, and a Google Pixel.

## Plan

Currently, I have a home assistant setup running on my home server.
We have a small forest in our backyard, and it is often visited by birds.
Additionally, Oklahoma is known for (if anything) weird weather patterns.

So, I'd like to set up a small setup out in this forest to monitor the weather, and to see/monitor the birds that visit.

### Solving some problems/How everything will work
#### Humidity
Humidity is kinda an issue for electronics, so I'm using a plastic enclosure to shield the components from humidity.

#### Power Management
These components require power, and I have to get it from somewhere. For power, I'm using a combination solar panel and battery pack I found from amazon. This should work for now, but I hope to potentially examine adding more batteries, or maybe even completely overhauling this system.

#### Connectivity
##### Wireless Connectivity
The whole project had a major problem: The forest is outside of the WiFi range. To solve this issue, I'm using a Pixel 5, so it can connect over Cellular Data to my Home Assistant instance.

##### Connectivity Between Pixel and Sensor
Since the pixel can't natively connect to the sensor, I'll be using [this library](https://github.com/3cky/usb-i2c-android) with a custom-made app and the FT232H chip to connect to the chip and "phone home."

#### Supply Shortages
Another driving factor in using a Google Pixel instead of a Raspberry Pi are the ongoing supply chain issues. Raspberry Pi's are extremely hard, if not impossible, to find. That, and the cost for a camera that's comparable to the Pixel and a Cellular modem would be even more expensive than the pixel itself.

### One More Thing...
While we're on the topic of Home Assistant, I have some RGB lighting in my room that is REALLY annoying to turn off at night. I'd like to automate this process using Home Assistant and a Pi Pico W, which I've found (for an arm and a leg) on Amazon. This is just something to add for the fun and convenience of it.

## Ideas for the Future
 - Add AI bird detection? (As seen in The MagPi)
 - Create Mastodon Bird Watcher Bot? (Powered by the AI)
 - Add a Humidity Sensor?
 - Add a Wind Speed Sensor?
 - Add a bird perch near it?

## Intangible Products of this Project
### Open Source Licensing
I will release the code (App for Android Connection, RGB Lighting Controller) I create for this project under an Open Source License.

### Documentation of Project Itself
I will, if all goes correctly, document the process of making this project as an Instructable and/or post the process to my Blog.

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| MPL3115A2 | https://www.adafruit.com/product/1893 | $9.95 |
| Google Pixel 5a 5g | https://swappa.com/listing/view/LWNS27865 | $155 |
| FT232H  | https://www.adafruit.com/product/2264 | $14.95 |
| Solar Panel + Battery Pack | https://www.amazon.com/Portable-20000mah-Waterproof-Flashlights-CellPhones/dp/B07NVM4L1C/ | ~$16.80 (Deal Applied) |
| Raspberry Pi Pico W (x2, it's only a little more, and I'll put the second to a good use case) | https://www.amazon.com/Hosyond-Raspberry-Dual-core-Microcontroller-Development/dp/B0BJD4R1LV/ | ~~$21.99 (Deal Applied)~~ $24.99 |
| USB-C Hub | Owned | ? |
| Micro-usb, USB-C Cable | Owned | ? |
| Wood (For Enclosure) | Owned | ? |
| Humidity Enclosure (Made from Plastic) | Owned | ? |
| Additional Decorations for Enclosure | Owned/Will Be Purchased from own funds if more needed | ? |
| Shipping/Tax | See Above | $6.00 (AdaFruit) + $9.07 (Swappa) = $15.07 |
| Total           |                                       | $236.76 |

## Credits
Thanks to my Grandma for the inspiration for this project <3
