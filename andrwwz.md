---
name: "@andrwwz"
project: "6DOF Ultralight Robot Camera Arm"
---

# 6DOF Ultralight Robot Camera Arm

## Summary

  The goal of this project is to make an extremely rigid yet lightweight robot arm for phones, cameras, and other objects. Smoothness, strength, and low backlash are key, so it must be rigid and able to withstand the forces from the load and its own acceleration. Carbon fiber rods are extremely rigid and light, and they can be made even stronger together in a triangular configuration (shown below). ABS plastic 3D printed with high density will be used to join parts together. Side panels and fairings will be minimal to reduce weight/bulk and showcase the mechanics of the arm. Wires can be slipped through the carbon fiber rods as cable management to retain a sleek design. 

<img width="552" alt="image" src="https://user-images.githubusercontent.com/82012389/212487348-bdc33377-a61e-4f61-9178-9a45b565a3bd.png">
CAD Cross section (to scale). Circles are CF rods and rectangles are GT2 9mm belts for kinematics.

  I want to make a camera arm to assist in making videos and time lapses with my 3d printer. While I'm very familiar with mechanical components and have dabbled with electronics in 3d printers, I have very little experience coding. With the complexity of a robot arm, code can't just be copied from the internet and I will likely have to make a lot of it from scratch. Many robot arm project guides exist on YouTube already, but I want to go through the design process myself with my own ideas and goals. This project is a leap of faith, to see how much I can learn and achieve. 

## Plan

Build and Design Process: 

1. Design the arm in Fusion 360, including all electronics and hardware
    a. Design gear reduction mechanism, likely harmonic drive due to low backlash
    b. Ensure parts all fit together properly and in a satisfactory form factor
2. Begin 3D printing test components to check tolerances for electrical and mechanical parts
    a. Test fit mechanical parts and 3d prints together for strength and rigidity
    b. If 3D printed parts don’t fit together properly, adjust and reprint to correct tolerances
    c. Test harmonic drive to ensure strength and minimal backlash
3. Test electrical components components to ensure parts are working properly before assembly
4. 3D print final components ready for assembly in ABS
5. Begin assembly!
6. Test motors to ensure they are strong enough to support the weight
7. After assembly, simulate 1:1 scale model in Blender to perform inverse kinematics simulations
8. Perform basic tests for smoothness and positional accuracy after kinematics calculations

Tools (hardware and software):
- Screwdrivers (duh)
- 3d printer and filament (ABS and TPU)
- Soldering iron
- Fusion 360 
- Blender (kinematics simulation)

Inspiration and learning from [Jeremy Fielding](https://www.youtube.com/watch?v=HMSLPefUVeE&list=PL4njCTv7IRbyf3XfhUcp_jnkRrAu1UP3I) and 
[稚晖君](https://www.youtube.com/watch?v=F29vrvUwqS4) on YouTube

## Budget

**What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.**

  Many of the materials will be components commonly used in 3d printers, which I already own some of and am very familiar with. For parts I don’t have, Amazon and online 3d printer part stores will cover most if not all of the mechanical and electrical components. 
https://docs.google.com/spreadsheets/d/1o8EGZSA9DsgLYJZ-idwo8wbahZMI09PmzNXrt5GQjlU/edit#gid=0

| Product                               | Supplier/Link                                                                                 | Cost    |
| ------------------------------------- | --------------------------------------------------------------------------------------------- | ------- |
| 10x12x330mm Carbon Fiber Rod (3x)     | https://www.amazon.com/gp/product/B00TF8V05W/ref=ox_sc_act_title_2?smid=A37EFSP4QP9HL5&th=1   | $47.94  |
| GT2 9mm Belt and pulley set           | https://www.amazon.com/gp/product/B01COER836/ref=ox_sc_act_title_6?smid=A15GNHST7KG47K&psc=1  | $24.88  |
| 5x16x5mm Deep Groove Ball Bearings    | Already Owned                                                                                 | $0      |     
| 80x100x10mm Ball Bearings (2x)        | https://www.amazon.com/gp/product/B07RQ4RXDR/ref=ox_sc_act_title_3?smid=A1THAZDOWP300U&psc=1  | $29.98  |
| 5x13x4mm Flanged ball bearings        | Already Owned                                                                                 | $0      |
| 5x60mm Dowel Pins 10x                 | https://www.amazon.com/gp/product/B07MB8QV7J/ref=ox_sc_act_title_5?smid=A30WUG2ZDGM0XM&psc=1  | $9.99   |
| Hardware (M5, M4, M3)                 | Already Owned                                                                                 | $0      |
| Nema14 21Ncm 35mm Stepper Motor (2x)  | https://www.amazon.com/gp/product/B07PQ12SDW/ref=ox_sc_act_title_2?smid=A3HCJ70Z0RHBT6&psc=1  | $27.96  |
| Nema17 59Ncm 48mm Stepper motor       | Already Owned                                                                                 | $0      |
| Nema23 1.9NM Stepper motor (2x)       | https://www.amazon.com/gp/product/B00PNEPI0A/ref=ox_sc_act_title_2?smid=AWQBCGWISS7BL&psc=1   | $59.98  |
| 5x TMC 2208 Stepper motor drivers     | https://www.amazon.com/gp/product/B082LSQWZF/ref=ox_sc_act_title_3?smid=A3CX4TQNUXMB0L&psc=1  | $19.99  |
| Mean Well 24v 150w power supply       | https://www.amazon.com/gp/product/B018RE4CWW/ref=ox_sc_act_title_1?smid=A28HQ7WE3N597P&psc=1  | $9.00   |
| 3D Printer Control Board              | Already Owned                                                                                 | $0      |
| Shipping and Taxes                    |                                                                                               | $43.19  |
| Total                                 |                                                                                               | $272.91 |
