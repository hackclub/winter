---
name: "@masonnamminga"
project: "Smart Snack Machine"
---

# Smart Snack Machine

## Summary

Here is a link to a brief sketch of the project: https://drive.google.com/file/d/1lcVTtpE1dmJsk5uPMtVKJY8mgoLhL7px/view?usp=sharing

I am planning on making a smart snack machine that dispenses snacks via a mobile app that anyone can access on my home network. The snack machine will be built out of plywood and plexiglass. The web app will be written in html/js and hosted on a raspberry pi. This raspberry pi will be attached to a touchscreen monitor fixed to the outside of the snack machine if the user would rather use the screen to order and not a phone. The servo motors that dispense the snacks will be controlled via the Blynk IoT platform and a NodeMCU–allowing for them to be triggered via a JS function. In summary, press a button on your phone or the built-in screen, you get a snack! I am excited to build this project because I have always wanted to build this project, and I feel that I now have the knowledge to bring this idea into reality!

## Plan

I first plan to get the servos and NodeMCU's working and connected to my home network, after this I can create the webhooks that I will call in my js function to individually control the servos. 

Next is assembling all the servos together and verifying that every JavaScript function is working, after all the electronics are working I will create the web app. I plan to make a simple dashboard of buttons. When a button is pressed, the dispense function will be called, allowing for the servo to rotate and drop the snack. 

Finally, I will assemble the box with rows for the snacks and mount the screen and raspberry pi. For this I will use plywood and plexi glass. I will 3d print all needed brackets, and use a vinal cutter for accents and labels. The last step is to add LED light strips that can be contolled with the touchscreen!


## Budget

| Product                 | Supplier/Link                         | Cost    |
| ----------------------- | ------------------------------------- | ------- |
| Raspberry Pi 3          | Already own.                          | $0.00   |
| Touch Screen for Pi     | https://amzn.to/3YvCXQh               | $79.99  |
| x16 360 Degree Servos   | https://amzn.to/3YEQNzU               | $103.96 |
| Plywood/Particle Board  | Already own.                          | $0.00   |
| 3D Printer Filament     | Already own.                          | $0.00   |
| x4 Node MCU WiFi Board  | https://amzn.to/3YvDPo1               | $12.59  |
| Power Supply Module     | https://amzn.to/3YC9RhR               | $9.09   |
| Solderless Breadboards  | https://amzn.to/3BNoFRk               | $6.69   |
| LED WiFi Backlighting   | https://amzn.to/3PGPTi6               | $19.99  |
| Total                   |                                       | $232.31 |





