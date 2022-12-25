---
name: "@KaiDevrim"
project: "NFC Unlock & Stream Deck & Monitor Backlight"
---

# Project Name
NFC Unlock & Stream Deck & Monitor Backlight

## Summary
I want to make a system where depending on who wants to use the computer, the pi will detect them via their keycard and log them into all the websites under their account and everything. This will be very useful if I want to use this as a guest computer or was teaching someone and they needed to use my computer.

For the Stream Deck, I just want basically a hotkey keyboard to do advanced actions, like custom scripts and whatnot.

I finally want to make a simple monitor backlight that basically just detects what is on screen and changes the light of an led strip to match that colour. It will be very useful for immersive games as well as immersive movies.

## Plan

### NFC
I plan on using a raspberry pi that I already own, along with a pikvm so it acts as a troubleshooting device for my pi. My raspberry pi will use the PiKVM to act as a keyboard and mouse, and will also allow me to remotely monitor the user in case they need help. I will be using a an nfc card with the nfc pi hat to do all the authentication and stuff and everything. 

### Stream Deck
For the Stream Deck, I will use a mechanical keypad, attach that to my raspberry pi, and use the OSS https://stream-pi.com/ to control my computer, phone, server, lights, all from a click of a button. I will need the SD card switcher so that I can use one pi for multiple projects.

### Monitor Backlight
For the monitor backlight I will just follow this very simple video, [Cheap DIY Arduino Ambilight 2.0](https://www.youtube.com/watch?v=nzDnr76fZCc).

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| PiKVM           | https://www.amazon.com/dp/B0B5R37TT3  | $79.99  |
| Mechanical Numpad | https://www.amazon.com/Tidbit-Programmable-Mechanical-Numpad-White/dp/B08CBQHGJ7 | $39.99 |
| SD Card Switcher | https://www.amazon.com/Icstation-Micro-Card-Dual-Switcher/dp/B01MY139K4 | $13.99 |
| NFC Hat         | https://thepihut.com/products/nfc-hat-for-raspberry-pi-pn532 | $30
| Arduino Nano    | https://www.amazon.com/gp/product/B00NLAMS9C?psc=1 | $12
| LED Connector   | https://www.amazon.com/gp/product/B08VRGRYM9?psc=1 | $8
| Breadboard      | https://www.amazon.com/gp/product/B09ZQPRFTB | $7
| DC Power Connector | https://www.aliexpress.us/item/2251832804147531.html | $2
| Power Supply    | https://www.aliexpress.us/item/2251832624591733.html | $12
| LED Light Strip | https://www.aliexpress.us/item/2251801850504415.html | $5
| Total           |                                       | $242
