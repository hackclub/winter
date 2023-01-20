---
name: "@ZeroQLi"
project: "IOT kanban board"
---

# IOT kanban board

## summary

TLDR: An IOT kanban board

I LOVE trello and its Kanban board methodology. So i am now making mini physical kanban board for myself.
using a spare white board i have i will create physical kanban board that syncs with an online trello board so i can easily access and update my progress on the fly, or maybe just create a app from scratch myself.

The kanban board is basically a imaginary 3x3 grid on a whiteboard with magnetic hall effect sensors attached behind the it. Adding a new card in trello triggers a receipt
using the thermal printer inidcating the same, which i would then attach to the magnet using double sided tape (at least that's what the idea is)
Changing the position of a magnet would update a live server running on the pi and updating the position via the site would display the instruction using an led display attached on top of the board
for me to follow upon returning

The current configuration is expected to support a max of 6 tasks (although i will inittaly configure it to 3 cause i don't want to increase my productive workload).

In addition, i would like the board to be able to handle multiple people so i'm implementing a NFC tag based profile to be able to do so

## plan

i plan to follow a tutori- SIKE **THIS IS AN ORIGINAL IDEA** meaning no tutorials for me

Trying to simplyfying things, A step by step process of building the board would involve:

- Porting [this arduino](https://github.com/bitbank2/Thermal_Printer) library to raspberry pi in order support the thermal printer.  *I've already begun this step*
- Testing magnetic components and soldering them to some jumper wires
- connect the jumpers wires to the appropriate ports of raspberry pi
- figuring out how RFID works and managing profiles.
- coding all the needed software (the easy part)
- finishing touches and debugging
- tweeting the finished product on twitter to gather some internet points (/s)

This is just a stub, I plan on fully documenting my journey via a blog and process and will update this file too

## budget

| Product | Supplier | Cost |
|----|----|----|
|Raspberry pi 4B 4gb ram kit|https://besomi.net/product/raspberry-pi-4b-starter-kit-4gb-blk/|$122.51|
|hall effect sensor (7pcs)|https://besomi.net/product/49e-hall-sensor-lm393-linear-hall-effect-detection-module-ab030/|$28.59|
|Electronic Component kit (2 pcs)|https://besomi.net/product/electronic-component-starter-kit-wires-breadboard/|$19.06|
|PN532 NFC reader|https://besomi.net/product/pn532-nfc-rfid-reader/|$9.53|
|RFID card (3pcs)|https://besomi.net/product/df-robot-accessories-mifare-one-rfid-card-13-56-mhz/|$4.90|
|ADS1115 ADC|https://besomi.net/product/ads1115-16-bit-adc-4-channel-with-programmable-gain-amplifier/|$10.89|
|Cat thermal printer|https://www.noon.com/product/Z4C6688401CB54FB3069AZ/p/|$18.51|
|Soldering Iron Kit|https://www.noon.com/uae-en/product/N18835963A/p/|$11.43|
|Neodyium magnets|https://www.noon.com/product/N47404217A/p/|$9.53|
|double-sided tape, sd card and reader | self expense |$0|
|Grand total (inclusive shipping and VAT)|-|$245.25|
