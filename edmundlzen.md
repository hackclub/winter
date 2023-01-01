---
name: "@edmundlzen"
project: "Media Deck"
---

# Media Deck

## Summary

Basically like a stream deck but with a screen and a rotary knob. Can be used for controlling audio, running macros, launching applications once connected to a computer. I'll probably also need to write a client side app to achieve the macros, info displaying part. I also decided to use a banana pi m2 zero. Also because it has a built in display, it can be programmed to show other useful data, such as bitcoin price data, currently playing media, etc. I also intend to make the built in display show notifications, this way, if the user is engaged in a fullscreen activity, such as playing a game and etc, they can check on the notifications just by glancing at the deck.

| ![Concept](https://user-images.githubusercontent.com/12859874/210131267-afd04426-078c-4969-9422-611caf134e07.png) |
|:--:| 
| *Concept image of the deck, note that this is just an initial concept and I intend to change & iterate on the design further* |

## Plan

After I buy all the required items, I'm going to figure out how to connect the display to the raspberry pi, after that, I'm going to let the raspberry pi be able to detect the key inputs, rotary knob inputs and etc. After getting the inputs, I have to figure out how to relay this information to the connected computer. Maybe through an app on both the raspberry pi and the computer? Honestly I have only tried arduino before, so it would be a learning curve to try raspberry pi. Once that's done I guess all that's left is to design the ui for the display. Once the electronics part is done, I will design a case (probably going to have to learn to use cad software) to house all the electronics in and print it out. After soldering all the components together, glueing it into the case, it should be complete.

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
| Shipping Costs |  | $8.29 |
| Total |  | $245.46 |
