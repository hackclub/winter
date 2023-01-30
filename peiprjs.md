---
name: "@peiprjs"
project: "Desk Thing"
---

# Car thing but for a desk instead (Desk thing)

## Summary

Spotify has this device they call Car Thing. It's a screen that's supposed to go on your car (unsafe much?) and allow you to choose music and see what is currently playing at a glance. I would like that, but available for my desk, as I don't have a car (nor do I need one).\
So my plan is to, using a ~~Raspberry~~ Orange Pi, a web server, a 3D-printed enclosure, a speaker, and a touchscreen, make something that allows me to see which song is playing (and album artwork, author and year), which song is next in the queue (and author), from which playlist/album, duration of the song and rough progress bar (can't be too exact because it will mostly comunicate through the API), basic controls (pause, skip, go back), and a sleep timer function (pause the music after a certain time).\
The whole device would be built inside of a 3D printed structure, which would include a support for a Homepod mini (as I've heard that its sound is fairly flat and just a little bit of EQ makes it sing). The only problem is that streaming the music directly from the Pi would be very hard due to it being a very basic computer, which could reduce the quality of the music).

## Plan

1. Measure all of the parts, design, print, and sand a piece (or a few) that allow me to keep all of the tech parts together.
2. Assemble the device and plug all of the tech in.
3. Design a web interface that connects to the Spotify API and displays the data.
4. Run the web interface on the local device, connect the speaker and voilà! A ~~car~~ desk thing.

## Bill of materials
| Product          | Supplier/Link                       | Cost*   |
| ---------------  | ----------------------------------  | ------  |
| Touchscreen      | https://www.amazon.es/dp/B07PHFQF7W | $56.43  |
| PLA filament     | https://www.amazon.es/dp/B07R6PL63K | $23.42  |
| Electric plug    | https://www.amazon.es/dp/B06XXNPLJ9 | $09.56  |
| MiniHDMI->HDMI   | https://www.amazon.es/dp/B07PHFQF7W | $06.10  |
| Homepod Mini     | (Apple Store)                       | $99.00  |
| TP-Link TL-WN823N    | https://www.amazon.es/dp/B0088TKTY2 | $09.25  |
| Flat USB->USB        | https://www.amazon.es/dp/B0953LJ84W | $10.80  |
| Red paint (detailing)| (Supermarket)                       | $05.00  |
| Current total        |                                     | $217.06 | (-$26.57)

*Price is after EUR->USD conversion. Actual price may vary by ±5% due to currency fluctuations. Prices include VAT/IVA.
