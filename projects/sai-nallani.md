---
name: "@sai-nallani"
project: "Connected LED Speakers"
---

# LED Network Speakers

## Summary
Basically a ton of microcontrollers and speakers in a small lamp that can send data to each other through a phone. Useful as a gift to a friend so you can scream
in their room while they're sleeping.

What are you going to build? What does it do? Why are you excited to build it?
I am building it because I want to stay connected with my friends and it seems fun to annoy them. I will first build the lamp; the lamp has a speaker and a microcontroller
inside of it. The microcontroller can control what the speaker says and it can control the LED lights. Next, I will build a website that can control all the other speakers
given permissions and security. I will make sure that it won't be too annoying though.
## Plan

What steps are you going to take to build it? What tools are you going to use? What will you do first, second, third, etc.?

My School's engineering room has a soldering iron kit, and using that i will attach the headers to the pico. I think I will also change the headers from male to female because then I wouldn't need to use a bread board.

Next, I looked at Adafruit's Neopixels. I believe I can simply just connect the Neopixels' pins to the pico. I will also find a external power source.

Afterwards, I will attach the speakers to the pico. Since they are speakers designed to connect to the raspberry pi, I don't think there is a problem with that.

To contain all the wiring, I will design a 3d-printed container (provided with by my school's engineering class) to contain the hardware.

Next step, API

As you may have noticed, I chose a Pico W to include wireless capabilities. Building the API would be fairly simple. The challenging part would be making it work with the PICO. I think to actually do it, I would need to have a small web server running on the Pico. This is where I was thinking instead of getting a Pico, should I get a Zero W? It has more ram, so it may be able to support a web server more efficiently than the Pico. Do you believe that a Pico could support a small web server?

Or another possible solutions is to use web sockets.

The web socket would be a runner program running on the Pico, and it would be connected to a server that is always running located in my home or located in the cloud. The RPI would be sending requests to the server, and the server will establish a web socket with the RPi. The web socket establishes a constantly running communication port between the server and the pico. This is what chat applications use for real-time communications, so I think web sockets would be a more efficient solution.
## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 3x Raspberry Pi Pico W + Breadboard | https://www.pishop.us/product/raspberry-pi-pico-w/ | $40.85 |
| 4x Female Header Set | https://www.pishop.us/product/female-header-set-for-raspberry-pi-pico/ | $9.80 (shipping with raspberry pi) |
| 4 Meters Adafruit NeoPixel LED Strip | https://www.adafruit.com/product/1138?length=4  | $119.93 |
| Raspberry Pi Starter Kit: Contains wires, resistors, etc... so I don't have to worry about that | https://www.amazon.com/Freenove-Raspberry-Included-Compatible-313-Page/dp/B0BJ1QC6X8/ref=sr_1_5?crid=2XRHFVLVON0G0&keywords=raspberry%2Bpi%2Bpico%2BW%2Bstarter%2Bkit&qid=1674350712&sprefix=raspberry%2Bpi%2Bpico%2Bw%2Bstarter%2Bki%2Caps%2C106&sr=8-5&th=1 | $32.06 |
| 4x Speakers | https://www.amazon.com/MakerHawk-Full-Range-Advertising-Connector-Separating/dp/B07GJ4GH67/ref=sr_1_3?crid=2OWCEXGU0418U&keywords=raspberry+pi+speakers&qid=1673672099&sprefix=raspberry+pi+speaker%2Caps%2C134&sr=8-3 | $25.98 |
| 3d printer | in school | 0 |
| welding | in school | 0 |
| Total with tax and shipping |                                       | $218.82 |
