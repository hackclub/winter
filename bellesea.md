---
name: "@bellesea"
project: "Map it :)"
---

# Map it :)

## Summary

I'm building a sectional aeronautical chart with live weather display, inspired by the [LightMap AIR](https://www.lightmaps.io/lightmap-air). I recently gained an interest in planes and flying, so I thought this would be the perfect opportunity to merge both interests :)) I've never built an electronics project before so i'm looking forward to learning! 

_Note: building this in Malaysia_

<img width="400" alt="Screenshot 2023-01-15 at 8 57 50 PM" src="https://user-images.githubusercontent.com/65808924/212582738-24f1043e-26f3-4256-931f-34bb3689adee.png">

(source: [LightMap AIR](https://www.lightmaps.io/lightmap-air))

_Why spend 300 dollars buying it when you can spend a similar amount building it yourself and potentially make it look considerably worse? :)_

## Plan
1. Stick the map onto a foam sheet (approx 20" x  20")
2. Figure out airport locations & where to place LEDs
3. Connect RPI to addressable LEDs and check that it works
4. Connect RPI to IR sensors & write some code*
5. Drill hole in map and add the LEDs
6. Add a small display to display text from a web app :)
7. Make it look good by adding a final wood sheet backing


*I will be working off my own fork of [this code](https://github.com/JohnMarzulli/categorical-sectional) that pulls data from the METAR website. right now all settings can be configured in a json file and the project would be good to go but i'll be adding sensors to switch between displaying different sorts of data (flight rules, temperature, precipitation, and visibility) and hence will rewrite a significant chunk of the code. Potentially also adding on/off lights functionality.

Referencing these guides:
https://slingtsi.rueker.com/making-a-led-powered-metar-map-for-your-wall/
https://github.com/JohnMarzulli/categorical-sectional

I have access to a maker space and hence the other tools necessary to make this happen (like a soldering station, power tools to create the frame, etc.)


## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Sectional Chart (x2*)   | https://www.sportys.com/vfr-sectional-chart.html | $18 |
| Foam sheets| Bought locally  | $10 |
| Wood sheets (to create frame)  |     Bought locally                                  | $20 |
| IR sensors  (5)      |   https://shopee.com.my/search?keyword=ir%20sensor&is_from_login=true                                  | $1.8 |
| Screen           |          https://shopee.com.my/5-inch-Touch-Screen-HDMI-LCD-Display-For-Raspberry-Pi-3-2-1-i.8822702.1012471424?sp_atk=87c7a68a-60f3-4cff-ac7c-87578a202922&xptdk=87c7a68a-60f3-4cff-ac7c-87578a202922                     | $32 |
| RPI Model 3B | https://shopee.com.my/Raspberry-Pi-3-Model-B-i.276752935.23810547921?sp_atk=b0909e4f-71fd-4472-9d69-599ac71a4e45&xptdk=b0909e4f-71fd-4472-9d69-599ac71a4e45 | $50 |
| MicroUSB power supply       |    https://www.digikey.my/en/products/detail/raspberry-pi/RPI-USB-C-POWER-SUPPLY-BLACK-US/10258759                    | $8 |
| Barrel Jack      |     https://www.amazon.com/gp/product/B01M4RBARQ?th=1                         | $8 |
| Extension chord**           |         bought locally                             | $10.00 |
| Addressable LEDs           |         https://www.digikey.com/en/products/detail/adafruit-industries-llc/738/9770506 | $40 |
| Sportys Tax + Shipping           |                                       | $7.93 |
| Digikey Tax + Shipping           |                                       | $28 |
| Total           |                                       | $233.73 |

*purchasing two because I assume that I will likely mess up on my first try

**to allow the map to be placed almost anywhere in the room
