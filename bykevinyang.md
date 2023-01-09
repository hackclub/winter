---
name: "@bykevinyang"
project: "Musivue"
---

# Musivue

## Summary
![](https://i.ytimg.com/vi/xLpvFAAI7hg/maxresdefault.jpg)
![](http://embedded-lab.com/blog/wp-content/uploads/2016/09/royg_bars_square_fixed.gif)

Musivue is a reactive LED music display with multi view displays: spectrum analyzer, [Spotify cover](https://github.com/phultquist/frame), or [circular graphic equalizer](https://youtu.be/cMCBEp5XiP0?t=29). The goal is to make a wall-hung portrait that portals users into the complex frequencies of your favorite songs.

## Thought Process 

I've always been obsessed with making music displayable. My first (real) PCB project was a [VU meter](https://www.instructables.com/LED-Volume-Bar/) that could go up and down with the booming sounds of your song. I then pimped a boombox with a frequency analyzer to allow for a reactive light show anywhere, anytime. I want to create a central music visualizer that taps into the Spotify API, combining various frequency display formats for one breathtaking decor piece.


## Plan

First, I am going to set up the Orange PI 0. From there, I will make it communicate with the 64x64 LED matrix and play around with drawing simple animations. Afterward, I will create various frequency display modes (spectrum analyzer, circular view, etc.) and find a way to feed them music data from the Spotify API. Afterward, I will create a sleek portrait-esque wood case to hang up on the wall.

For tools I will need:
- Soldering Iron
- Laptop
- Miter Saw
- Multi-meter
- Variable Power Supply

I fortunately already have all of these tools. I will just need to buy parts.

## Features
- [] Linear Spectrum Analyzer
- [] Circular Graphic Equalizer
- [] Spotify Album Cover
- [] Spotify Smart-Home Control Hub
    - Act as a Spotify recognized listening device able to stream music. Play that music through an onboard audio jack to a speaker.
    - Have buttons and knobs to skip songs on spotify, remotely!
- [] Music Dependent Ripple Wave
    - The LED matrix will ripple in a wave pattern that is dependent on the music playing. The wave will be more intense when the music is louder.

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 64x64 RGB Matrix Display   | [Amazon](https://www.amazon.com/waveshare-Full-Color-Displaying-Adjustable-Brightness/dp/B0B3F7WKJ1/ref=pd_rhf_d_dp_s_vtp_ses_clicks_nonshared_sccl_2_3/147-8787553-5198451?pd_rd_w=nPxkh&content-id=amzn1.sym.c33ad739-91a9-476e-b522-fd0cf7ffda5c&pf_rd_p=c33ad739-91a9-476e-b522-fd0cf7ffda5c&pf_rd_r=74DH1YHPDDFM2829E4NA&pd_rd_wg=bkkzI&pd_rd_r=2427d3b3-1358-46c1-bcaf-86f53d410cad&pd_rd_i=B0B3F7WKJ1&psc=1) | $39.98  |
| Orange Pi Zero 2 | [Amazon](https://www.amazon.com/Orange-Pi-Allwinner-Supported-Ethernet/dp/B0B9BXJMSG/ref=sr_1_2?crid=3L9IG5XPCSV75&keywords=Orange%2BPi%2BZero&qid=1672958271&sprefix=orange%2Bpi%2Bzero%2Caps%2C78&sr=8-2&th=1) | $32.99 |
| Acrylic Light Diffusion Sheet | [Amazon](https://www.amazon.com/Milky-Acrylic-Translucent-Plexiglass-AZM/dp/B0818HYY8G/ref=sr_1_3?crid=10VEARZDTYSCN&keywords=LED+Diffusion+Acrylic+Panel&qid=1673043140&sprefix=led+diffusion+acrylic+panel%2Caps%2C114&sr=8-3) | $9.99 |
| 5V 8A Power Supply | [Amazon](https://www.amazon.com/Aclorol-100V-240V-Switching-Converter-5-5x2-1mm/dp/B08744HB1X/ref=sr_1_1_sspa?crid=2JOGV23TBUD3U&keywords=5v%2Bpower%2Bsupply%2B6%2Bamps&qid=1673024392&sprefix=5v%2Bpower%2Bsupply%2B%2Caps%2C955&sr=8-1-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExNFpUMkFVWTE3Q1hRJmVuY3J5cHRlZElkPUEwNDk0Mzk1M01WNllMNkVITFNMUyZlbmNyeXB0ZWRBZElkPUEwOTEwNjQ5RUhLVUNLUDVISkhGJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ&th=1) | $16.99 |
| 12" x 12" Walnut Plywood | [Home Depot](https://www.homedepot.com/p/Columbia-Forest-Products-1-4-in-x-2-ft-x-2-ft-PureBond-Walnut-Plywood-Project-Panel-Free-Custom-Cut-Available-2717/204771142) | $14.99 |
| 1" x 2" Walnut Planks | [Amazon](https://www.amazon.com/Barrington-Hardwoods-Walnut-Lumber-Pcs/dp/B07GJBM52K/ref=sr_1_6_mod_primary_new?crid=UCLYWATW9RY2&keywords=walnut%2Bplank&qid=1673041275&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=walnut%2Bplank%2Caps%2C156&sr=8-6&th=1) | $14.95 |
| Polycrylic Protective Wood Finish | [Amazon](https://www.amazon.com/Minwax-233334444-Polycrylic-Protective-Finishes/dp/B017NNJYBW/ref=sr_1_4?crid=2U32VHGLC9RSM&keywords=clear%2Bfinish%2Bwood&qid=1673042408&sprefix=clear%2Bfinish%2Bwood%2Caps%2C89&sr=8-4&th=1) | $12.98 |
| Small hardware (screws, washers, etc) | Home Depot | ~$15.00 |
| Measuring Square | [Amazon](https://www.amazon.com/Tools-Combination-Square-Metal-Body-1794469/dp/B005XUHIBG/ref=sr_1_2?keywords=square%2Bmetal&qid=1673232923&sr=8-2&th=1) | $18.27 |
| Clamps | [Amazon](https://www.amazon.com/IRWINQUICK-GRIPOne-Handed-Micro-Clamp-Pack-1964747/dp/B00004SBCO/ref=sr_1_5?crid=1B71QW4B4LNPI&keywords=clamps%2Bquick%2Bgrip&qid=1673233280&sprefix=clamps%2Bquick%2Bgrip%2B%2Caps%2C159&sr=8-5&th=1) | $12.98 |
| Shipping | Amazon | Free |
| Shipping | Home Depot | None. Driving |
| Pre-tax total | | $189.12 |
| Tax (MA) | | $ 11.82 |
| Total           | | $200.94 |


---
By the way, I have a box of 50+ soldering irons given to me by [@leomcelroy](https://github.com/leomcelroy) that I will glady ship to anyone who wants one. Just pay shipping.