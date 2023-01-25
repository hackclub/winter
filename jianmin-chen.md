---
name: "@jianmin-chen"
project: "DIY electric bike!"
---

# DIY electric bike

## Summary

Basically, I stumbled across [this article on IEEE Spectrum](https://spectrum.ieee.org/electric-bike) about building an electric bike on a budget. So I'm basically fitting my bike with the components needed to turn it into an electric bike - which is not only going to be super handy, but super exciting! I can't wait to brag to all the kids on the block about my super awesome bike. (No, I'm just joking. But seriously, I always had the worst bike as a kid. This is karma.)

## Plan

The article is less of a step-by-step guide than it is a general dessemination of the parts needed to build an electric bike and how much more affordable it is now. (Still, an interesting read.) However, it does come with a couple of useful diagrams.

![The diagram in IEEE Spectrum](https://spectrum.ieee.org/media-library/blueprint-of-the-simple-electric-bike-conversion.png?id=27253742&width=1200&height=1026)

Basically, I'm going to take a brushless skateboard motor (`A` in the diagram), which goes up next to the bike wheel. Then, I'm going to 3D print a bike rack (at a local makerspace), and use it to hold the battery, which powers the electric motor. To control the actual speed of the battery/motor, I'm going to use [open-sourced ESC (Electric Speed Controller) software](https://vesc-project.com/), linked to an Arduino Nano connected to a speed signal controller. The battery is `B` in the diagram. The battery going to be connected to a Drok meter (basically a multimeter for the battery), as marked by `C` in the diagram, and the Nano is going to be used to send speed signals to the speed signal controller using the appropriate switches in the front, which are linked to the brakes (`D` and `E` in the diagram).

I'm more of a software person and I haven't really worked with hardware before, so this will be interesting!

## Budget

_Note to self: Make sure to factor in shipping costs and sales tax._

The build will go over the budget (batteries are expensive!), so I've divided the supplies into two categories for convenience - one to be covered by HC and the other to be covered by me. Any other necessary supplies will be covered by me if they do happen to come up.

| Product                           | Supplier/Link                                                                                | Cost    |
| --------------------------------- | -------------------------------------------------------------------------------------------- | ------- |
| Flipsky Brushless Motor           | https://www.amazon.com/gp/product/B086YN7SSB/ref=ox_sc_act_title_5?smid=A3QK84HB8OFPD6&psc=1 | $119.99 |
| Flipsky Electric Speed Controller | https://www.amazon.com/gp/product/B08725X8CT/ref=ox_sc_act_title_4?smid=A3QK84HB8OFPD6&psc=1 | $116.99 |
| Rocker Switch                     | https://www.amazon.com/gp/product/B01FA9UNMA/ref=ox_sc_act_title_1?smid=A3HMB6GLG0WJ17&psc=1 | $5.49   |
| Hall effect sensors               | https://www.amazon.com/gp/product/B085KVV82D/ref=ox_sc_act_title_1?smid=A3PXX08VVBPF5M&psc=1 | $5.99   |
| Total                             |                                                                                              | $248.46 |

What I'm paying for:

| Product                           | Supplier/Link                                                                               | Cost    |
| --------------------------------- | ------------------------------------------------------------------------------------------- | ------- |
| Ryobi 40V 4Ah lithium-ion battery | https://www.amazon.com/gp/product/B07QYH36TC/ref=ox_sc_act_title_1?smid=AKM2QHJF28L6F&psc=1 | $113.90 |
| Adapter for Ryobi battery         | https://terrafirmatechnology.com/products/ry40?_pos=1&_sid=2c4514cfd&_ss=r                  | $25     |
| Charger for Ryobi battery         | https://www.amazon.com/Replacement-Dewalt-Battery-DC9096-DC9098/dp/B07VCF2QGH               | $29.99  |
| Drok meter                        | https://www.amazon.com/gp/product/B07QYH36TC/ref=ox_sc_act_title_1?smid=AKM2QHJF28L6F&psc=1 | $15.99  |
| Neodymium magnets                 | https://www.amazon.com/DIYMAG-Neodymium-Magnets-Double-Sided-Adhesive/dp/B07WCBDPMJ/?th=1   | $9.99   |
| Total                             |                                                                                             | $200    |
