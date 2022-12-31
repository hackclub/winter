---
name: "@andy-phung"
project: "DIY AirPods / Desktop Killjoy Turret / Ramen Lamp"
---

# DIY AirPods / Desktop Killjoy Turret / Ramen Lamp

## Summary

I'll be using this grant for three mini-projects:
- DIY AirPods! Because I thought making a pair'd be a fun way to learn about what goes into wireless audio streaming :>
- A desktop [Killjoy turret](https://media.tenor.com/ivAUHBeshMsAAAAC/valorant-killjoy.gif) (from Valorant)! It'd just be a scaled down version that shoots Nerf bullets at whoever it can see
- A ramen bowl lamp! Because I came across [these](https://www.adafruit.com/product/5509) flexible LED filaments and thought it'd be cool if they were noodles in some kind of lamp :0
   - (it'd look something like [this](https://content.instructables.com/FBJ/2SC4/JWL0SBVJ/FBJ2SC4JWL0SBVJ.png?auto=webp&frame=1&width=320&md=5c993760fb62baf7242dff8c6dae6eb3), but with a 3D-printed arm holding the chopsticks and a sliding switch to adjust the brightness of the noodles)

## Plan
### DIY AirPods
I'll probably:
- Use Expressif's [ESP32 Bluetooth A2DP API](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/bluetooth/esp_a2dp.html) to get audio streaming from my phone to the two TinyS3s 
- Connect the TinyS3s to their respective earbuds and make sure they can play audio through them (i.e. they'd now be attached on the sides of the earbuds) -> wire a li-on battery and USB-C plug to each
- Wire together the USB-C ports and li-on chargers (one port'll be at the bottom of the charging case, sending current to the two li-on chargers -> other two ports; to charge the earbuds, I'd just plug them into these two ports)
- Design and 3D print the charging case, leaving slots for the charging assembly, hinge, and magnets (I have access to 3D printers, in case it isn't clear)
- Assemble the charging case!
### Desktop Killjoy Turret
This one should be a little easier --- I'll just:
- 3D print housings for the yaw motor, shooting motor, camera, Raspberry Pi, and power cable (the only part I don't have is the yaw motor, which is the one listed in the budget table)
    - The bullet-feeding mechanism would probably just be a ramp in the shooting motor housing
- Assemble and paint the turret!
- Write and upload a Python script that detects the nearest person using pose estimation, aligns the turret with their center of mass by signaling the yaw motor driver as appropriate, and shoots them by turning the shooting motor on!

### Ramen Lamp
Also shouldn't be too hard --- I'd just need to 3D print the arm, chopsticks, & bowl and wire the noodles to the slide potentiometer (which'd be connected to a resistor -> the USB-C port)!

## Budget
| Project        | Product                                         | Quantity  | Supplier/Link                         | Cost   |
| -------------- | ----------------------------------------------- | --------- | ------------------------------------- | ------ |
| DIY AirPods    | Micro-Lipo Charger                              | 2         |https://www.adafruit.com/product/1904  | $13.90 |
|                | USB Type C Socket - SMT Inline Breakout Board   | 3         |https://www.adafruit.com/product/4396  | $10.50 |
|                | Magnet Square - 0.125"                          | 4         |https://www.sparkfun.com/products/8644 | $4.20  |
|                | Plastic Hinge                                   | 1         |https://www.adafruit.com/product/1215  | $0.95  |
|                | Apple EarPods                                   | 1         |https://www.apple.com/shop/product/MNHF2AM/A/earpods-with-35-mm-headphone-plug  | $19.00 |
|                | USB Type C Plug (10 Pack)                       | 1         |https://www.adafruit.com/product/4932  | $9.95  |
|                | TinyS3 - ESP32-S3 Development Board             | 2         |https://www.adafruit.com/product/5398  | $40.00 |
|                | Lithium Ion Polymer Battery - 3.7v 100mAh       | 2         |https://www.adafruit.com/product/1570  | $11.90 |
| Killjoy Turret | Stepper Motor - 68 oz.in (400 steps/rev)        | 1         |https://www.sparkfun.com/products/10846| $19.50 |
|                | DRV8833 DC/Stepper Motor Driver Breakout        | 1         |https://www.adafruit.com/product/3297  | $5.95  |
| Ramen Lamp     | nOOds - Flexible LED Filament - Yellow, 3V 300mm| 8         |https://www.adafruit.com/product/5509  | $60.00 |
|                | Slide Pot - Medium (10k Linear Taper)           | 1         |https://www.sparkfun.com/products/11621| $2.75  |
|                | Slide Potentiometer Knob - Small and Medium     | 1         |https://www.sparkfun.com/products/14889| $1.25  |
|                | USB Type C Socket - SMT Inline Breakout Board   | 1         |https://www.adafruit.com/product/4396  | $3.50  |
|Taxes           |                                                 |           |                                       | $26.93 |
|Shipping        |                                                 |           |                                       | $17.20 |  
|Total           |                                                 |           |                                       | $247.48| 
