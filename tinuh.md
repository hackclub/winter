---
name: "Tinu Vanapamula"
project: "Smart Chess Board"
---

# Smart Chess Board

## Summary

I'm going to build a variation of this [chess board](https://www.youtube.com/watch?v=Z92TdhsAWD4&t=1s). I want my chess board to sync with lichess api so that I can play chess games online and show the opponents move on the physical chess board. I want to then be able to make my move (through a simple web server) and have it sync with the api. I also want to include an oled screen to display the opponents moves as well as mine. I'm excited to build this because it would be super cool to play chess physically and have it sync with an online game.

## Plan

Instead of using an arduino and raspberry pi combo, I plan on just using a single raspberry pi pico w. I'm going to use the [lichess api](https://lichess.org/api#tag/Board) to have the game sync with an online game. In the video the guy used 8 buttons to input a players moves however I'm going to try to use a web server and simple api calls to use as inputs. I'm going to use an addressable LED strip as a backlight for the board and I'm going to use white PLA filament for a translucent board surface. I'm going to use the blue filament to print out the rest of the board. Instead of using a micro usb port I'll use a usb-c port to provide power for the pico, oled, and light strip. I'm going to reference the 3d models the guy from the video guide provided but will have to use CAD to make changes because I won't be using an buttons and I'll be using different hardware. Here is a general outline of steps,

### Hardware

- Use CAD to make changes to the provided 3D printable parts to accommodate the USB-C port, the raspberry pi pico, the OLED screen, and the lack of buttons.
- Figure out how to use the 3D printer to print out the pieces for the board, and the chess pieces themselves
- Solder headers onto the raspberry pi pico w, USB-C breakout connector, and OLED display
- Use the USB-C breakout connector to provide power to the raspberry pi (cut a micro usb cable in half to provide regulated power) and use the same 5V and ground rails to power the addressable LED strip as well as the OLED display
- Use I2C GPIO pins to connect the OLED display with raspberry pi pico

![image](https://user-images.githubusercontent.com/41168054/209708021-7586e6bb-7626-49c8-8e4e-79cf10c67964.png)

### Software

- Figure out the lichess API (how to connect to a game, make moves, recieve the next move, etc.)
- Make a simple webserver with micropython on the rpi pico to recieve moves as inputs and pass it onto the lichess API
- Design a system to best interface with the LED strip (translate coordinates into location on the strip)
- Display moves from the API response on the board
- Use the OLED screen to display opponents moves and your previous move

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi Pico W| [Micro Center](https://www.microcenter.com/product/650108/raspberry-pi-pico-w) | $5.99  |
| 0.96" OLED display | [Adafruit](https://www.adafruit.com/product/326) | $17.50 |
| USB-C Breakout Connector| [Adafruit](https://www.adafruit.com/product/4090) |$2.95
| Ender 3 Pro 3D Printer | [Micro Center](https://www.microcenter.com/site/content/specialoffer3dprintertxt.aspx?web=EMAIL+OPT+IN) | $99.99 |
| White PLA Filament | [Micro Center](https://www.microcenter.com/product/611544/inland-175mm-white-pla-3d-printer-filament-1kg-spool-(22-lbs)) | $18.99 |
| Blue PLA Filament | [Micro Center](https://www.microcenter.com/product/611538/inland-175mm-light-blue-pla-3d-printer-filament-1kg-spool-(22-lbs)) | $18.99 |
| Solder | [Amazon](https://a.co/d/izpRV80) | $7.99 |
| Soldering Iron | | Already Own |
| Hot Glue Gun | | Already Own |
| Wire | [Amazon](https://a.co/d/hfry9cp) | $14.95 |
| Addressable LED Strip | [Amazon](https://a.co/d/03nOTAV) | $22.99 |
| General Purpose Headers | [Amazon](https://a.co/d/aoTQSx8) | $5.99 |
| Sales Tax (Maryland 6%) | Amazon | $3.12 |
| Sales Tax (Maryland 6%) | Micro Center | $9.14 |
| Sales Tax (Maryland 6%) | Adafruit | $1.23 |
| Shipping (Adafruit) | USPS First Class | $6.10 |
| Total           |                                       | $235.92 |
