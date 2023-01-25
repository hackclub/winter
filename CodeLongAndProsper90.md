---
name: "@CodeLongAndProsper90"
project: "Out of Time"
---

# Out Of Time - The Hacker's CLock

## Summary
This is going to be a smart clock, with the following features:
- time and date
- analog and digital display modes
- plays music from sd card as an alarm
- can store multiple alarms, and schedule them.

Possible features
- reads metadata from WAV file
- displays messages on birthdays and holidays (needs a big database though)
- gets weather report from outside unit (needs chips, license, $$$)
- plays video games (input problem)

I currently have a sony alarm clock but the local radio stations are :poop:, so I want to make a better alarm clock

## Plan
I plan to first breadboard this, without any sort of external input sans serial.
First I'm going to figure out the ui in p5.js / turtle to get an idea of what I need to do. Next, I'll make the audio amp and player.
Next would be the display / ui, should be pretty fast.
Once I get audio output working, I'm going to design a faceplate for the display and controls. After that I think I'll make the rest of the case then solder.
I might use plexiglass, or 3d print, depending on cost. (I'll probably pay for that)
Then I'll test one more time then solder, case up and go from there.

## Budget

| Product / name | Link | Cost | Used for |
| -------------- | ---- | ---- | -------- |
| Slide Potentiometer with Knob - 75mm Long - 10KΩ | https://www.adafruit.com/product/4219 | 2.95 | Volume control |
| 5.0" 40-pin TFT Display - 800x480 with Touchscreen | https://www.adafruit.com/product/1596 | 29.95 | Display and interface (wanted 7", out of stock) |
| RA8875 Driver Board for 40-pin TFT Touch Displays - 800x480 Max | https://www.adafruit.com/product/1590 | 39.95 | Used to control the TFT, handle input |
| MicroSD card breakout board+ | https://www.adafruit.com/product/254 | 7.50 | Read music and maybe config |
| Adafruit DS3231 Precision RTC Breakout | https://www.adafruit.com/product/3013 | 17.50 | time |
| CQRobot Speaker 3 Watt 4 Ohm Compatible with Arduino Motherboard, 2.54mm Dupont Interface. | https://www.amazon.com/CQRobot-JST-PH2-0-Interface-Electronic-Projects/dp/B0822XCPT8/ref=sr_1_4?keywords=8%2Bohm%2Bspeaker%2Barduino&qid=1671486487&sr=8-4&th=1 | 8.99 | Play audio |
| Arduino zero | https://store-usa.arduino.cc/products/arduino-zero?selectedStore=us | 47.40 | Control it all |
| Audio IC Development Tools Adafruit Mono 2.5W Class D Audio Amplifier - PAM8302 (1 piece) | https://www.amazon.com/Audio-Development-Tools-Adafruit-Amplifier/dp/B00PY2YSI4/ref=psdc_667846011_t2_B07P38H4P8 | 7.92 | drive les speakers |
| Adafruit Sensirion SHT31-D - Temperature & Humidity Sensor | https://www.adafruit.com/product/2857 | 13.95 | Add some stats to display |
| Shipping and Tax from Adafruit | | 22.28 | |
| Shipping and Tax from Arduino | | 3.79 | |
| Tax from Amazon | | 1.39 | | 
| | | 202.18 | |
(Computed by `awk -F\| '{ sum += $4 } END { print sum }` on the table without the header)


