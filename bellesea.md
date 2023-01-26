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
| Screen           |            https://www.pishop.us/product/tufty-2040-accessory-kit/                        | $33.95 |
| RPI Model 3A+ | Currently out of stock but keeping my eye on https://rpilocator.com/ | ~$50 |
| Power supply           |      https://www.amazon.com/gp/product/B00MRGKPH8/ref=oh_aui_detailpage_o06_s00?ie=UTF8                                 | $12.99 |
| Extension chord**           |         https://www.amazon.com/AmazonBasics-Grounded-Extension-3-Outlets-15-Foot/dp/B07N4PMQS3/ref=zg_bs_495312_sccl_2/134-4992931-3999416?th=1                              | $10.00 |
| Power plug adapter           |           https://www.amazon.com/gp/product/B01M4RBARQ/ref=oh_aui_detailpage_o06_s01?ie=UTF8                            | $7.99 |
| Addressable LEDs           |         https://www.digikey.com/en/products/detail/adafruit-industries-llc/4560/12396891?s=N4IgjCBcoLQBxVAYygMwIYBsDOBTANCAPZQDa4ArAEwIC6AvvYVWSACwUBsADCA0A                              | $19.95 |
| Sportys Tax + Shipping           |                                       | $7.93 |
| Pishop Tax + Shipping           |                                       | $9.50 |
| Amazon Tax + FREE Shipping           |                                       | $3.70 |
| Sportys Tax + Shipping           |                                       | $7.93 |
| Total           |                                       | $230.67 |

*purchasing two because I assume that I will likely mess up on my first try

**to allow the map to be placed almost anywhere in the room
