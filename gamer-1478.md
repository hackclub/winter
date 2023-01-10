---
name: "@gamer-1478"
project: "Digital Chess Board"
---

# Digi Chess Board

## Summary

This winter, i am planning on building a digital chess board which can track your pieces and which even you can play with solo through stockfish. 
I plan to opensource it and make sure that everyone can build theres easily, from making intuitive designs and flowcharts to readable code. 
The past month i have been a enthuisiast at the game of chess, and think DGT's monopoly on it needs to be broken and open sourced, Hence i am very excited about this opurtunity to do so. 

## Plan

1. I would attach hall effect sensors and configure them to work with the magnetic chess pieces. 
2. I would work on the wiring the hall effect sensors such that they get adequate power from a power supply/Battery. 
3. I would connect all the hall effect sensors to the arduino to read the voltage output. I would then send that data over serial bus to the rsapberry pi. 
4. I would read the data in raspberry pi and configure the chess.com software in nodejs or python. Stockfish and other UI will also be added in the same software.
5. The arduino will also be connected to some buttons and a display to make a chess clock timer. 

## Budget
What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product                                   | Supplier Link                                                                                                  | Cost    |
|-------------------------------------------|----------------------------------------------------------------------------------------------------------------|---------|
| Chess Set with Magnetic Pieces            | https://www.amazon.in/NSXEEN-Chessboard-Educational-Improving-Intelligence/dp/B096RKVKMR                       | 9.10$   |
| Chess Set with a mat                      | https://www.amazon.in/Wigano-Roll-Up-Vinyl-Tournament-Queens/dp/B071CJBLPM                                     | 8.44$   |
| Hall Effect Sensor - Linear - WSH49E * 70 | https://www.electronicscomp.com/wsh49e-hall-effect-sensor-linear                                               | 36.44$  |
| Arduino Mega                              | https://robu.in/product/orange-basic-kit-for-arduino-mega/                                                     | 24.43$  |
| LCD Display For Chess Timer               | https://www.electronicscomp.com/1602-blue-lcd-display-with-i2c-interface                                       | 5.11$   |
| Buttons * 5                               | https://robu.in/product/green-electronic-building-blocks-big-key-button-module-high-level-output/              | 2.43$   |
| Self Locking Buttons *5                   | https://robu.in/product/green-ds-429a-10mm-2pin-self-locking-square-push-button-switch-with-lock/              | 0.85$   |
| Thin Wire                                 | https://robu.in/product/plusivo-24awg-hook-up-wire-kit-600v-pre-tinned-stranded-silicon-wire-of-6-colors-x-9m/ | 9.73$   |
| Raspberry Pi                              | https://robu.in/product/raspberry-pi-4-model-b-with-8-gb-ram/                                                  | 97.28$  |
| Raspberry Pi Starter Accessories          | https://robu.in/product/orange-raspberry-pi-4-beginner-kit/                                                    | 30$     |
| Battery                                   | https://robu.in/product/orange-11-1v-1800mah-3s-40c-lipo-battery-pack-xt60-connector/                          | 19$     |
| Battery Charger                           | https://robu.in/product/b3-20w-compact-lipo-charger/                                                           | 13.38$  |
|                                           |                                                                                                                | 256.65$ |
