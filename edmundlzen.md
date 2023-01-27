---
name: "@edmundlzen"
project: "Media Deck"
---

# Media Deck

## Summary

Basically like a stream deck but I'd say it's a better version, it has a screen, a rotary knob and 9 buttons. Can be used for controlling audio, running macros, launching applications, even maybe mini programs on the deck itself since it can run independent of a computer if you wish to. Because it has a built in display, it can also be programmed to show other useful data, such as bitcoin price data, currently playing media, etc. I also intend to make the built in display show notifications, this way, if the user is engaged in a fullscreen activity, such as playing a game and etc, they can check on the notifications just by glancing at the deck. Basically the capabilities for modding seem endless to me with the combination of a banana pi, a touchscreen, a knob, and keys.

| ![Concept](https://user-images.githubusercontent.com/12859874/210131267-afd04426-078c-4969-9422-611caf134e07.png) |
|:--:| 
| *Concept image of the deck, note that this is just an initial concept and I intend to change & iterate on the design further* |

## Plan

1. After receiving the grant, purchase all the required items.
2. After setting up the banana pi, connect the display to the banana pi and finish setting it up.
3. I'd probably write a custom app for the banana pi to make it display info, read inputs from the gpio pins which I'll connect the knobs and buttons to, after prototyping on a breadboard, I'll solder the components together. I'll probably test sending the input data through maybe something like bluetooth? This probably requires writing another app on the receiving computer to configure the macros, relay information like currently playing song, maybe even set a background? Custom theming?
4. After I confirm the electronics are working, I'll take the dimensions and design a case which looks aesthetically nice and can fit everything nicely. I'll 3d print the case using the 3d printer I purchased as I don't have any access to a 3d printer in my area and probably have to use some online 3d printing which would be slow to ship and wouldn't enable me to rapidly iterate on my design.
5. If I have the time, and budget, I'm also considering adding a lipo battery to this deck to make it be able to used fully wirelessly.

Notes:
- I'm not following any guide directly to build this and will work my way through with some experimenting + following various different online guides to connect all the different pieces together.

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Soldering kit | https://shopee.com.my/60W-Adjustable-Temperature-Soldering-Iron-936-Tips-Station-Solder-Tools-Gun-Portable-15-in-1-Set-Kit-Bag-READY-STOCK--i.33091591.13932809791?sp_atk=392dbb44-c507-4904-908a-93ef32eabd80&xptdk=392dbb44-c507-4904-908a-93ef32eabd80 | $7.95 |
| PLA Filament | https://shopee.com.my/KINGROON-PLA-Filament-1KG-1.75mm-Diameter-Genuine-Dry-Stock-0.02mm-Tolerance-Smooth-Print-i.490347977.17189110439?sp_atk=d3d4ae9a-b606-4752-81d5-583773dae45e&xptdk=d3d4ae9a-b606-4752-81d5-583773dae45e | $9.40 |
| Tactile Mechanical Switches x 9 | https://shopee.com.my/-READY-STOCK-Leobog-Icesoul-Leobog-Crystal-45g-Tactile-Switches-Switch-for-Mechanical-or-Gaming-Keyboards-Tactile-i.72068395.18252700943?sp_atk=f627d3dd-2648-45ce-a3d2-f7e20a0e39f5&xptdk=f627d3dd-2648-45ce-a3d2-f7e20a0e39f5 | $2.02 |
| Keycaps x 9 | https://shopee.com.my/-JOHOR-READY-STOCK-XDA-Keycap-1U-White-Pink-Green-Blue-for-Mechanical-Keyboard-i.92077799.12056961648?xptdk=8c8657da-9afa-48ce-aadf-ec559ffd1a1a | $2.45 |
| Rotary Control Knob | https://shopee.com.my/1pcs-35x17mm-Aluminum-Alloy-Rotary-Control-Potentiometer-Knob-6mm-Shaft-Hole-i.178873154.15876362530?xptdk=bf8d90ed-0790-4784-bd8b-cc0fcd37213b | $1.08 |
| Creality Ender 3 3D Printer DIY Kit | https://shopee.com.my/READY-STOCK-IN-MALAYSIA-Creality-Ender-3-3D-Printer-DIY-Kit-(UK-PLUG)-i.744585255.16464162984?sp_atk=e2a24f41-3038-4bdb-b58a-e66601215331&xptdk=e2a24f41-3038-4bdb-b58a-e66601215331  | $165.72 |
| Banana Pi M2 Zero | [Link shortened for your viewing pleasure](https://www.lazada.com.my/products/bpi-m2-zero-bananapi-android-allwinner-h2-banana-pi-is-faster-than-raspberry-pi-zerow-i1936182967-s7792108567.html?clickTrackInfo=query%253Abanana%252Bpi%252Bm2%252Bzero%253Bnid%253A1936182967%253Bsrc%253ALazadaMainSrp%253Brn%253Aa4adf4f3da25f6d5bb3215ded2d7dc7e%253Bregion%253Amy%253Bsku%253A1936182967_MY%253Bprice%253A100018945%253Bclient%253Adesktop%253Bsupplier_id%253A100018945%253Basc_category_id%253A10000493%253Bitem_id%253A1936182967%253Bsku_id%253A7792108567%253Bshop_id%253A61360&fastshipping=0&freeshipping=0&fs_ab=1&fuse_fs=0&lang=en&location=Overseas&price=115.7&priceCompare=&ratingscore=5.0&request_id=a4adf4f3da25f6d5bb3215ded2d7dc7e&review=1&sale=28&search=1&source=search&spm=a2o4k.store_product.list.i40.79b7c8d9svZXkR&stock=1) | $26.27 |
| 3.5 Inch Touch Screen LCD for Raspberry Pi | https://shopee.com.my/Waveshare-3.5-Inch-Touch-Screen-LCD-for-Raspberry-Pi-4B-3B-3B-2B-Zero-Zero-W-Zero-WH-480X320-Pixel-SPI-Interface-i.110869235.21066606814?sp_atk=bf544f69-e284-45e2-bc56-f101ac81f709&xptdk=bf544f69-e284-45e2-bc56-f101ac81f709 | $22.28 |
| 2x20 stacking GPIO Header | https://shopee.com.my/product/168163073/6232135506?smtt=0.18725379-1672577161.9 | $2.25 |
| Mini HDMI Cable | https://shopee.com.my/Vention-Mini-HDMI-to-HDMI-2.0-Cable-Male-to-Male-1080P-HD-4K-3D-HDMI-Cable-Adapter-for-Projector-LCD-i.285713283.8435872052 | $3.17 |
| Breadboard | Already have | $0.00 |
| Jumper wires | Already have | $0.00 |
| SD Card | Already have | $0.00 |
| Shipping Costs |  | $10.51 |
| Total |  | $253.10 |
