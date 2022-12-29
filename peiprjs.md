---
name: "@peiprjs"
project: "Your Project Name Here"
---

# Car thing but like for not a car

## Summary

Spotify has this device they call Car Thing. It's a screen that's supposed to go on your car (unsafe much?) and allow you to choose music and see what is currently playing at a glance. I would like that, but available for my desk, as I don't have a car (nor do I need one).\
So my plan is to, using a ~~Raspberry~~ Orange Pi, a web server and a touchscreen, make something that allows me to see which song is playing (and album artwork, author and year), which song is next in the queue (and author), from which playlist/album, duration of the song and rough progress bar (can't be too exact because it will mostly comunicate through the API), basic controls (pause, skip, go back) and a sleep timer function (pause the music after a certain time).\
The whole device would be built inside of a 3D printed structure, which would include a support for a Homepod mini (as I've heard that it is fairly flat and just a little bit of EQ makes it sing). The only problem is that streaming the music directly from the Pi would be very hard due to its basic computer status, which could reduce the quality of the music).

## Plan

1. Measure all of the parts, design and print (and sand) a single piece that allows me to keep them all together.
2. Assemble the device and connect all of the parts together.
3. Design a web interface that connects to the Spotify API and displays the data.
4. Run the web interface on the local device, connect the speaker and voilà! A ~~car~~ desk thing.

## Budget

| Product          | Supplier/Link                       | Cost*   |
| ---------------  | ----------------------------------  | ------  |
| Orange Pi Zero 2 | https://www.amazon.es/dp/B09M8N614J | $49.12  |
| Touchscreen      | https://www.amazon.es/dp/B07PHFQF7W | $56.43  |
| PLA filament     | https://www.amazon.es/dp/B07R6PL63K | $23.42  |
| Electric plug    | https://www.amazon.es/dp/B06XXNPLJ9 | $ 9.56  |
| Homepod Mini     | (Apple Store)                       | $99.00  |
| Shipping         | Amazon + In-store pickup            | $00.00  |
| Total            |                                     | $237.53 |


*Price is after EUR->USD conversion. Actual price may vary by ±5% due to currency fluctuations. I can cover any conversion hijinks. Prices include VAT/IVA.
