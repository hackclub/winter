---
name: "@pranavnt", "quackduck" (me and Ishan are building this together)
project: "FSC (full self cycling) Bike"
---

# FSC (full self cycling Bike 

## Summary

Ishan and I are building an ebike that has full self cycling – you can press a button (on touchscreen) and it will cruise at ~8mph on a trail, detecting lanes and the side of the trail, and automatically steer.

## Plan

1) Put battery on top rack; surround with pre-owned foam and duct tape 
2) Mount the Motor & ESC such that the motor moving will move the chain
3) Mount training wheels
4) Mount the touchscreen, servo that controls the steering, and OAK-D Camera. Tie string to handlebars.
5) Connect the Raspberry Pi to the ESC, Touchscreen, servo, and OAK-D Camera
6) Run self driving software

Self-driving software will work by detecting the lane and edge of a trail using a pre-trained lane detection model. Based on this, we'll model how much the bike has to turn. Max speed in this mode will be ~8mph probably. String will be connected to a servo and each of the handles; turning will be adjusting the string.

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product                      | Supplier/Link                           | Cost   |
| ---------------------------- | --------------------------------------- | ------ |
| OAK-D Camera                 | https://store.opencv.ai/products/oak-d  | OWNED  |
| 7" Raspberry Pi Touchscreen  | https://www.adafruit.com/product/2718   | OWNED  |
| Bike (lol)                   | OWNED                                   | OWNED  |
| Raspberry Pi                 | OWNED                                   | OWNED  |
| Duct Tape/Filiament          | OWNED                                   | OWNED  |
| Electronic Speed Controller  | https://amzn.to/3Xd0AM5                 | $117   |
| Brushless Motor              | https://amzn.to/3iB2l73                 | $90    |
| Battery                      | https://amzn.to/3iFHcZc                 | $170   |
| Servo                        | https://www.adafruit.com/product/1142   | $20    |
| Training wheels              | https://amzn.to/3iFHy1Y                 | $33    |
| Taxes                        |                                         | $43    |
| Shipping                     |                                         | $15    |
| Total                        |                                         | $488   |
