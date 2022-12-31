---
name: "@BadPotato1007"
project: "Drumbox looper midi"
---

# RasberryPi Drumbox looper midi with advanced features

## Summary

The plan is to make a advanced MIDI device with rasberryPi, which will include a Drumbox, a looper, and a midi launchpad, featuring a 7" touch display, and a sensitive mic, topped off with a good quality mono spear for audio out. 

There will be 2 potentiometers for volume control, 2 rotary encoders for mode selection and drum sound selection, 16 capacitive switches for the drum pad, and 16 RGB leds for the drum pad.
You can select between 4 modes, which are the drumbox, the looper, the midi launchpad, and the settings mode. In the drumbox mode, you can play the drum pad and the mic will pick up the sound and play it back through the speaker. In the looper mode, you can record and play back loops. In the midi launchpad mode, you can play the drum pad and it will play midi notes. In the settings mode, you can change the volume, the mode, and the drum sound. When you change the mode, the drum sound will change to the default drum sound for that mode. All sounds and recordings will be saved on the device, and will be uploaded to my cloud server with 1TB storage to access them on any other device. Turning the rotary encoders will cycle between the different drum kits. Turning the potentiometers will change the volume and the pitches to calibrate the device. Using a simple button on the display, you can Turn on the screen saver kind of feature, during which the screen will display a equalizer that reacts to surrounding sounds and the leds will turn off, but the device will still be on and you can still play the drum pad. The device will be powered by a 12V 2A power supply. Witch will be stepped down to 5v for the rasberryPi. The dimension of the device will be 12" x 10" x 2.5" and will be made out of black acrylic sheets and some 3d printed parts. It will be a portable device that can be used anywhere. It will be a great device for musicians and producers alike, and also help me in my musical endeavours.


This project will be opensource and will have instructions on how to make it on instructables, so that other hobbiests like me can make it too.

## Plan

1. To start off, I will need a new rasberryPi device as my old one shortcircuited and the gpio pins no longer work
2. Then I will have to connect all the hardware to the rasberryPi, which includes 
    1. The 7" touch display 
    2. The 16 capacitive switches as the buttons for the drum pad with the help of a port expander [MCP23017]
    3. 6 Output Shift registers to control the 16 Rgb leds for the drum pad [74HC595]
    4. The mic              [These will be connected to the rasberryPi via a usb soundcard]
    5. The mono speaker     [These will be connected to the rasberryPi via a usb soundcard]
    6. The 2 rotary encoders [Change modes and select drum sounds]
    7. The 2 potentiometers [Volume]
3. Then I will have to write the code [Planning to use python]
4. Make a nice good professional looking case with the help black acrylic sheets and some 3d printed parts
5. Use the drumbox looper and make the project opensource with instructions on how to make it on instructables


## Budget


| Product                   | Supplier/Link                                                                                      | Cost   |
| ---------------           | -------------------------------------------------------------------------------------------------- | ------ |
| 7" LCD display            | https://www.amazon.in/REES52-Display-1024X600-Function-Raspberry/dp/B07GDLB7TM/product/1957        | $81.25 |
| Rotry Encoder             | https://robu.in/product/m274-360-degree-rotary-encoder-module-brick-sensor/                        | $0.68  |
| Rasberry pi 3b            | https://www.olx.in/item/raspberry-pi-3b-6-pieces-brand-new-condition-iid-1702194889                | $68.75 |
| MCP23017                  | https://robu.in/product/mcp23017-16-bit-input-output-expander-with-i2c-interface-ic-dip-28-package | $4.00  |
| 74HC595                   | https://robu.in/product/sn74hc595n-dip16/  (owned)                                                 | $1.75  |
| Potentiometer             | https://robu.in/product/ptv09a-4225f-b103-rotary-potentiometer/                                    | $1.30  |
| Capacitive Sensor         | https://robu.in/product/ttp223-touch-key-module-2pcs/                                              | $6.00  |
| 12V 2A Adapter            | Owned                                                                                              | $3.00  |
| RGB leds                  | https://robu.in/product/ws2812b-4-x-4-rgb-led-module/                                              | $2.70  |
| 3D printed parts          | Nearby shop                                                                                        | $10.00 |
| Acrylic sheets            | https://cutt.ly/u2ujscX, shorturl.at/cdes5                                                         | $15.00 |
| Speaker                   | Owned                                                                                              | $2.00  |
| Mic                       | shorturl.at/ahJL2                                                                                  | $1.00  |
| USB soundcard             | shorturl.at/nGZ25                                                                                  | $2.00  |
| Midi socket               | owned                                                                                              | $7.00  |
| Screws and other expenses |                                                                                                    | $10.00 |
| Total                     |                                                                                                    | $217.43|
|Funds I actually require   |                                                                                                    | $183.63|


Will try to Cut down at some places to decrease the price furthur, and make it more cost effective.
