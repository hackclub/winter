---
name: ["@TechTurtel", "@addu2468"]
project: "3D Printed Kinetic & Digital Clock"
---

# 3D Printed Kinetic & Digital Clock

## Summary

<img src="https://cdn.shopify.com/s/files/1/0035/7443/1790/products/30401_left_1800x1800.jpg?v=1602201307" alt="digitalclock" width="150"/>

I'm going to be working on this with my brother who is @addu2468, this is our first time doing anything with 3D printing or servos, we have done some raspberry pi projects before. This project is something I saw a while ago but reappeared in my mind recently, its a clock similar to the digital one in the photo above but it tells the time by pushing out the digit segments using servos which looks really cool. Hopefully this will be successful and maybe we can make something that tells the date as well.

## Plan

We are going to be making one to put in a main room. Starting off we will be using an arduino mega as the controller for moving the servos and the arduino mega sensor shield to hook each server up to the arduino. We will also attach a precision rtc in order to keep the time on the clock accurate and synced. We will be using a 3d printer and pla filament because it is quick to prototype with and pla is non toxic and good for beginners. First we will design a outer housing with holes for the digit segments, and the digit segments themselves. Then 3d print them, then we will design a gear and screw like thing to attach to the digit segments to allow the servo to move them in and out. Then we will attach the servos to the arduino and combine the housing and digit segments. Then finally align all the servos and create a program to convert the time to which servo to activate. If this is successful we will also be adding a button to toggle between displaying different sensors like, carbon monoxide, light, temperature, sound. The extra modules will be soldered to a prototype board that we will buy later.

## Budget

For the 3d printer it is currently on sale for 3 days, if possible can I buy it now and get reinbursed for the purchase later, so we can catch the sale?
We will cover shipping, taxes, and anything extra

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Arduino Mega + Sensors  | [https://www.amazon.com/dp/B016PZO2LQ](https://www.amazon.com/dp/B016PZO2LQ) | $71.99  |
| Arduino Mega Sensor Shield | [https://a.co/d/8rcUPc8](https://a.co/d/8rcUPc8) | $7.49 |
| DS3231 Precision RTC | [https://www.adafruit.com/product/3013](https://www.adafruit.com/product/3013) | $17.50 |
| SG90 9G Micro Servo (3x10pcs) | [https://www.aliexpress.us/item/3256804845912768.html](https://www.aliexpress.us/item/3256804845912768.html) | $59.13 |
| SV06 3D Printer | [https://sovol3d.com/products/sovol-sv06-direct-drive-3d-printer?variant=40106603774040](https://sovol3d.com/products/sovol-sv06-direct-drive-3d-printer?variant=40106603774040) | $239.00 |
| PLA Filament | [https://www.matterhackers.com/store/l/175mm-pla-filament-silver-1-kg/sk/M2JWHYCY](https://www.matterhackers.com/store/l/175mm-pla-filament-silver-1-kg/sk/M2JWHYCY) | $20.87 |
| Soldering Station | [https://www.amazon.com/YIHUA-Soldering-Station-Multiple-Functions/dp/B07RY5XWVG?ref_=ast_sto_dp](https://www.amazon.com/YIHUA-Soldering-Station-Multiple-Functions/dp/B07RY5XWVG?ref_=ast_sto_dp) | 119.95 |
| Total           |                                       | $535.94 |
