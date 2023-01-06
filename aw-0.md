---
name: "@aw-0"
project: "Haptic VR Gloves"
---

# 🧤 Haptic VR Gloves

## Summary

Gloves that let you interact with the virtual world have always been a sci-fi dream, for everyone and me as well! Even though companies like Meta have been able to build handtracking into their headsets' with CV, you can't beat dedicated hardware to solve the problem. So, I'm planning to build VR gloves based on LucidVR's [open source 3D files and software, called lucidgloves](https://github.com/LucidVR/lucidgloves), which can allow you to interact with SteamVR games with your hands, and allow you to feel objects inside of them! This will be my first time diving head-first into a hardware project, and I'm super excited to build something that will not only let me learn about hardware, but also potentially contribute back to this amazing open source project.

## Plan

Like mentioned above, I'll be basing this project off of the [lucidgloves Prototype 4](https://github.com/LucidVR/lucidgloves). Here's a step-by-step walkthrough of my plan:

1. [3D print all of the parts](https://github.com/LucidVR/lucidgloves/wiki/Prototype-4-Printing-Guide) with my 3D printer, and due to the sheer amount of the parts, I'll be most likely printing these before the 10 days begins.
2. Begin [assembly](https://github.com/LucidVR/lucidgloves/wiki/Prototype-4-Building-Tutorial) and [wiring](https://github.com/LucidVR/lucidgloves/wiki/Prototype-4-Wiring-Diagram), which will most likely come hand-in-hand. This is what I expect to take up the majority of the 10 days, as I'm a beginner to all this, and want to build the gloves with all the best practices in-mind.
3. Load the [lucidgloves firmware](https://github.com/LucidVR/lucidgloves/wiki/Firmware-Setup-and-Customization-Tutorial) onto the ESP32, and troubleshoot any issues that might pop up.
4. Test the glove with my Oculus Quest 2 and SteamVR.
5. I plan to build one glove, as I'm not sure how ambitious this project may be. But, if there's more time and enough materials, I'll go ahead and build a second one to create a matching pair.

## Budget

I'll be following [the reccomend parts list for the Prototype 4](https://github.com/LucidVR/lucidgloves/wiki/Prototype-4-Parts-List), along with other required items like PLA filament for the 3D printer, a soldering iron, and a JST crimping kit.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| b10k ohm Potentiometers   | [Amazon](https://www.amazon.com/TWTADE-Amplifier-Potentiometers-Knurled-RK097N-3-10K/dp/B07XQ1Q9RN/ref=sr_1_4?th=1) | $12.66  |
| 9g MG90S Servo Motors | [Amazon](https://www.amazon.com/RGBZONE-Geared-Helicopter-Airplane-Controls/dp/B07R3ZYQLC/ref=sr_1_11?crid=1V8YVESJQ17JZ&keywords=mg90s&qid=1643044117&sprefix=mg90s,aps,49&sr=8-11&th=1)  | $31.99 |
| ESP32 Dev Board | [Amazon](https://www.amazon.com/KeeYees-Development-Bluetooth-Microcontroller-ESP-WROOM-32/dp/B07QCP2451/ref=sr_1_5?th=1 ) | $13.99 |
| Retractable Badge Reels (for the rotary springs) | [Amazon](https://www.amazon.com/gp/product/B0732Z7T8W/ref=ox_sc_act_title_11?smid=A12N14GC39SHEQ&psc=1)  | $16.95 |
| Joystick | [Amazon](https://www.amazon.com/gp/product/B00P7QBGD2/ref=ox_sc_saved_title_5?smid=A30QSGOJR8LMXA&psc=1)  | $12.58 |
| MicroUSB Pinout | [Amazon](https://www.amazon.com/gp/product/B07KS1RPMP/ref=ox_sc_saved_title_4?smid=AB5D7200EYCEL&psc=1)  | $6.99 |
| Nylon Gloves | [Amazon](https://www.amazon.com/Static-Care-Conductive-Electronics-Semiconductor/dp/B09D8GNQ4J/ref=sr_1_25?keywords=nylon+inspection+gloves&qid=1673023571&sr=8-25&th=1) | $5.00 |
| Vecro Straps | [Amazon](https://www.amazon.com/gp/product/B08P2HDKL6/ref=ox_sc_act_title_1?smid=A2QHPZ3L88WS89&psc=1) | $3.99 |
| Power Banks | [Amazon](https://www.amazon.com/Portable-20000mAh-Charging-External-Compatible/dp/B094G1GL8T/ref=sr_1_3?crid=2H3W69RCVK1RB&keywords=20000mah+power+bank+2&qid=1673023804&s=electronics&sprefix=20000mah+power+bank+2,electronics,100&sr=1-3&th=1) | $29.95 |
| Foam Sheet | [Michael's](https://www.michaels.com/12x18-foam-sheet-by-creatology/M10597609.html?dwvar_M10597609_color=Gray) | $1.98 |
| JST Crimping Kit | [Amazon](https://www.amazon.com/Qibaok-Crimping-Ratcheting-Connectors-0-1-0-5mm%C2%B2/dp/B07ZK5F8HP/ref=sr_1_12?th=1) | $36.99 |
| Soldering Iron | [Amazon](https://www.amazon.com/YIHUA-Soldering-194%C2%BAF-896%C2%BAF-Adjustable-Calibration/dp/B082F1WKP9/ref=sr_1_10?crid=37XP61JZW0I7Z&keywords=soldering+iron&qid=1673025124&s=hi&sprefix=soldering+iron,tools,98&sr=1-10&th=1) | $39.99 |
| PLA Filament | [Amazon](https://www.amazon.com/gp/product/B00J0ECR5I/ref=ox_sc_act_title_1?smid=ANPI0LINHGMTA&psc=1) | $24.99 |
| Subtotal           |                                       | $238.05 |
| Amazon Coupons           |                                       | -$5.57 |
| Shipping           |                                       | FREE |
| Est. Taxes           |                                       | $18.52 |
| Total           |                                       | $251 |


*Happy to cover the extra $1 out-of-pocket :)*