---
name: "@KaiDevrim"
project: "NFC Unlock & Stream Deck & Microphone"
---

# Project Name
NFC Unlock & Stream Deck & Microphone

## Summary
I want to make a system where depending on who wants to use the computer, the pi will detect them via their keycard and log them into all the websites under their account and everything. This will be very useful if I want to use this as a guest computer or was teaching someone and they needed to use my computer.

For the Stream Deck, I just want basically a hotkey keyboard to do advanced actions, like custom scripts and whatnot.

Finally, me and @sohamb117 plan on building a microphone from scratch. This microphone will be used for recording audio and also to teach the both of us how to make an audio project from scratch. I have always wanted to learn how microphones work and how they take audio in and convert it to an electrical signal. This will be a group project as Soham has agreed that he will help build my Stream Deck keyboard and I will help build a microphone project.

## Plan

### NFC
I plan on using a raspberry pi that I already own, along with a pikvm so it acts as a troubleshooting device for my pi. My raspberry pi will use the PiKVM to act as a keyboard and mouse, and will also allow me to remotely monitor the user in case they need help. I will be using a an nfc card with the nfc pi hat to do all the authentication and stuff and everything. 

### Stream Deck
For the Stream Deck, I will use a mechanical keypad, attach that to my raspberry pi, and use the OSS https://stream-pi.com/ to control my computer, phone, server, lights, all from a click of a button. I will need the SD card switcher so that I can use one pi for multiple projects.

### Microphone
For the micrphone, me and Soham plan on following this simple video., [Building a quality USB-C microphone](https://www.youtube.com/watch?v=LoQu3XXIayc). We are planning on meeting up together during the hardware-party in February. I will help build the easier parts like connecting the power and doing some soldering. Soham wants to work with the resistors and capicitors and will also be helping teach me a lot of the hardware parts. This will be a fun project for the both of us as he will help me build my keyboard and I will help build his microphone.

## Budget
For the budget, the following should add up to $250 and the rest of the parts of the microphone will come out of me and Soham's pockets.
| Kai's Products         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| PiKVM           | https://www.amazon.com/dp/B0B5R37TT3  | $79.99  |
| Mechanical Numpad | https://www.amazon.com/Tidbit-Programmable-Mechanical-Numpad-White/dp/B08CBQHGJ7 | $39.99 |
| SD Card Switcher | https://www.amazon.com/Icstation-Micro-Card-Dual-Switcher/dp/B01MY139K4 | $13.99 |
| Arduino         | https://www.mouser.com/ProductDetail/782-ABX00028 | $12
| Switches        | https://mechanicalkeyboards.com/shop/index.php?l=product_detail&p=6458 | $8
| Keycaps         | https://www.mouser.com/ProductDetail/782-ABX00028 | $11
| NFC Hat         | https://thepihut.com/products/nfc-hat-for-raspberry-pi-pn532 | $30 |
| Microphone Products         | Supplier/Link                         | Cost   |
| Stripboard | https://www.mouser.com/ProductDetail/BusBoard-Prototype-Systems/ST2?qs=NGErKr1RxMAdSUqgGAVpyQ%3D%3D | 5.98 |
| 3 22uF Capacitors | https://www.mouser.com/ProductDetail/Panasonic/ECE-A1CKN220?qs=sGAEpiMZZMvwFf0viD3Y3ffldXPLozaym6ErFlDpeH8%3D | 1.23 |
| 4 2200uF 16v Capacitors | https://www.mouser.com/ProductDetail/Vishay/MAL217255222E3?qs=sGAEpiMZZMsh%252B1woXyUXj5FlmuaiuzipPNTnEQMb0kI%3D | 11.24 |
| 4 2.2kO Resistors | https://www.mouser.com/ProductDetail/Vishay-BC-Components/NFR25H0002201JR500?qs=sGAEpiMZZMtlubZbdhIBINtbNoSbM%252B0dFAjYP%252BXJwes%3D | 1.80
| 2 100O Resistors | https://www.mouser.com/ProductDetail/Vishay-BC-Components/NFR25H0001000JA500?qs=sGAEpiMZZMtlubZbdhIBINm6Q1qzdVi5VC4AhnQYPNU%3D | 0.9 |
| 2 3.9kO Resistors | https://www.mouser.com/ProductDetail/Vishay-Beyschlag/MBA02040C3901FCT00?qs=sGAEpiMZZMtlubZbdhIBIBVk1FrbPqRGFWgByuDgWoA%3D | 0.48 |
| Power Isolator | https://www.mouser.com/ProductDetail/Murata-Power-Solutions/NMA0515SC?qs=PpY8XP9UEJGt%2FToOcuC6IQ%3D%3D | 5.08 |
| IC Socket | https://www.mouser.com/ProductDetail/Mill-Max/110-41-308-41-001000?qs=dvxwXVM4mZVj1CY1TePuww%3D%3D | 0.90 |
| J112 | https://www.mouser.com/ProductDetail/onsemi-Fairchild/J112?qs=ljbEvF4DwONoDl3CPnuhug%3D%3D | 0.47 |
| Total           |                                       | $250
