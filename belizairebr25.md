---
name: "@belizairebr25"
project: "Newsight"
---

# Newsight

## Summary

I will attempt to build a headsup display/wearable computer with a keyboard innovation.

**The concept:**

I have always had the dream of a glasses-type computer display, but the display wouldn't be able to do much without a keyboard and mouse. No one would want to try to walk around and type on a conventional keyboard, and using a smartphone as a keyboard defeats the purpose. I will be using a raspberry pi as a computer element and an OLED or LCD display as the monitor mounted to a 3d printed glasses frame. Most of the electronics and a powerbank will be stored in the users pocket.

**The display:**

The plan was to use a transparent OLED as a monitor for a raspberry pi, but the technology for transparent oled's has not progressed far enough to function as a complete display for this project. I will use an LCD screen as a monitor for the raspberry pi, and swap it out for the transparent monitor when using it as a teleprompter, python console, text veiwer, etc...

**The keyboard:**

The keyboard is where the project gets more interesting. Ever since I dreamed of the future as a little child, I have envisioned wearable computers prolific as the iphone is today, but the keyboard and mouse have always eluded me. I finally solved the issue theoretically and can't wait to bring it to life. Essentially, where the joints are on the fingers there exists a line on the inside of the hand. This divides each finger into four areas, the tip, first knuckle, second knuckle, and the base on the palm. If a glove is worn with conductive peices on each space throughought both hands, there will be enough isolated areas for use as a keyboard(provided shift, number mode, and special charachter mode options are utilized). Then the thumb could have a contact wired to the positive of a low-voltage dc power supply. When the thumb contacts a part of the finger the circut is closed. Each section of the finger on each hand will have different resistance value attached to it and an arduino will read the resistance value of the circut knowing which value to assign to each charachter. Then three transistors per hand will be able to change which input is being used on the arduino and associates the same resistance with a number or capital for instance. The gate pin of these transistors will be wired to the modifying space of each hand allowing a different keyboard set for the opposite hand. These values will then be sent to the raspberry pi. As for the mouse, a regular wireless mouse can be used proided there is a flat surface present.

**Why:** I give a lot of pre-written talks/speeches and it would be nice to have a teleprompter there to guide me if I forget where I am. It has also always been a dream of mine to make something like this and it would be awesome if that could become a reality.

## Plan

1. Design wiring schematics and paper drafts to guide when wiring and to find any potential issues with the idea, as well as to aid in knowing quantities of what is needed.
2. Gather materials to construct the display and keyboard
3. begin making keyboard prototypes with transistors, resistors, and arduino.
4. Assemble the display and print the glasses frame.
5. Integrate the two systems.
6. Test the system and revise it to make it better. 
7. Find more potential use cases and modifications for the future.

Tools: I will utilize a soldering iron, a 3d printer, and glue

## Budget

| Product                                                                                                                                        | Supplier/Link                                                                                                                 | Cost    |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------- | ------------------------------- | ----------------------------------------------------------------------------------------- | ----- |
| Arduino nano board                                                                                                                             | https://www.amazon.com/gp/aw/d/B07R9VWD39/ref=ox_sc_act_image_10?smid=A2QTZX14X1D97I&psc=1                                    | $12.99  | BJT transistor and resistor set | https://www.amazon.com/gp/aw/d/B07G46LNCG/ref=ox_sc_act_image_8?smid=A2WIZBA4LZM5RA&psc=1 | $7.99 |
| Raspberry Pi Zero W                                                                                                                            | https://www.amazon.com/gp/aw/d/B06XFZC3BX/ref=ox_sc_act_image_7?smid=AN9XFB4R34UOI&psc=1                                      | $62.90  |
| Portable USB charger                                                                                                                           | https://www.amazon.com/gp/aw/d/B09H4GLZXT/ref=ox_sc_act_image_6?smid=A3CUYIPLALR9UA&psc=1                                     | $34.90  |
| LCD display module                                                                                                                             | https://www.amazon.com/gp/aw/d/B082GFTZQD/ref=ox_sc_act_image_5?smid=A3B0XDFTVR980O&psc=1                                     | $14.75  |
| Copper sheet roll for making keyboard contacts                                                                                                 | https://www.amazon.com/gp/aw/d/B0B21S6J5R/ref=ox_sc_act_image_4?smid=A3E294TQDZJYZC&psc=1                                     | $13.59  |
| Breadboard                                                                                                                                     | https://www.amazon.com/dp/B07DL13RZH/ref=redir_mobile_desktop?_encoding=UTF8&psc=1&ref_=ox_sc_act_image_3&smid=AX8SR0V05IQ2E  | $13.99  |
| Wireless USB mouse                                                                                                                             | https://www.amazon.com/gp/aw/d/B08NM2GF2V/ref=ox_sc_act_image_2?smid=A1PUHO6D4MM5FC&psc=1                                     | $10.93  |
| Transparent OLED with expansion board                                                                                                          | https://www.amazon.com/dp/B0B984V4YG/ref=redir_mobile_desktop?_encoding=UTF8&psc=1&ref_=ox_sc_act_image_9&smid=A3B0XDFTVR980O | $26.89  |
| Total                                                                                                                                          |                                                                                                                               | $215.06 |
| Materials I already own: Breadboard wire, acess to 3d printed parts, nessicary cables and connectors, general purpose wire, adhesives, Gloves. |                                                                                                                               | $0      |
