---
name: LimesKey
project: Outdoor Air Quality Sensor 
---

# Outdoor Air Quality sensor for my town

## Summary

It's a AirGradient Air Quality sensor for the outdoors. It can tests a variety of air quality metrics, mostly notably CO2 which is one of the most looked at metrics for air quality. I know high CO2 levels are higher in cities and urban neighbourhoods and that CO2 is very bad for the human body; it causes fatigue, anxiety and confusion for most people. I'm excited to build it because I'll get a real, hand on experience with soldering and electrical circuitry. My town isn't too small but not as big as a large city with multiple air quality sensors already existing. I'm planning on putting the sensor outdoors and creating a website (with probably Svelete) and sharing it on my towns's Reddit page as a way for people to see the real-time air quality metrics of real, realistic, neighbourhoods inside the town. 

## Plan

I have a few friends and family that are great with soldering that can teach me some things. I'll need a soldering iron and some solder which I recently recieved for Christmas. Well thinking of soldering all the parts first, configuring everything, ensuring that it can work in low temperatures (-20C), creating a docker to monitor and log the information, then maybe if I have enough time finally creating the website in Svelte to share with my town. I actually attempted this project early last year but ran into some issues with the solder I was using; the solder was way to thick and I believe did not have a rosin core causing it to melt a lot slower. In my past experiences, I know both the micro-controller and LCD screen are fairly easy to short out and break in the past so I included another one for good measure. Now that I have a new & good soldering iron and solder, a friend that is very good with soldering, I think I'll do pretty well.

For clarification all the parts I'm purchasing are apart of a [guide](https://www.airgradient.com/open-airgradient/instructions/diy-pro/) that has full instructions on assembly. Jeff Geerling did a [video](https://www.youtube.com/watch?v=Cmr5VNALRAg&t=495s) on the project and that is what inspired me. 

## Budget

 For both the PCB and the outdoor enclosure, I already own so I gave a rough estimate on how much it cost. I don't think there is any sales tax for the ones on AliExpress. All prices are in CAD. Note that AliExpress takes a few months to ship to Canada so it'll be a while before I get the parts.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 1.3" Inch OLED Module| [AliExpress](https://www.aliexpress.com/item/32787898780.html?spm=a2g0o.cart.0.0.446b38daar2D9N&mp=1)| $3.09  |
| Wemos D1 Mini Pro | [AliExpress](https://www.aliexpress.com/item/32651747570.html?spm=a2g0o.cart.0.0.446b38daar2D9N&mp=1)  | $2.25  |
|SHT31 Temperature & Humidity| [AliExpress](https://www.aliexpress.com/item/1005001626776392.html?spm=a2g0o.cart.0.0.446b38daf3U6DT&mp=1)| $2.62|
|SGP30 TVOC|[AliExpress](https://www.aliexpress.com/item/4000004614708.html?spm=a2g0o.cart.0.0.446b38daf3U6DT&mp=1)|$7.14|
|JST 1.25 8P Connector|[AliExpress](https://www.aliexpress.com/item/4001122480470.html?spm=a2g0o.cart.0.0.446b38daf3U6DT&mp=1) | $1.21|
|SenseAir S8 C02 Sensor|[AliExpress](https://www.aliexpress.com/item/1005004123170360.html?spm=a2g0o.cart.0.0.446b38daf3U6DT&mp=1)| $31.02|
|PMS 2.5 Air Particle Quantity Sensor| [AliExpress](https://www.aliexpress.com/item/32944660534.html?spm=a2g0o.cart.0.0.446b38daf3U6DT&mp=1)| $19.07|
|AirGradient PCB|PCBWay|$0|
|Outdoor Enclosure| Amazon.ca| $0
|-------------------------------------|----------|------|
|Subtotal||$67.14 CAD ($49.92 USD)
|Shipping to Canada|| $15.23 CAD
| Total           |                                       | $82.37 CAD ($61.24 USD) |
