---
name: "@khrj"
project: "Video Capture Drone"
---

# Video Capture Drone

## Summary

I'm going to build a drone that can capture video, and perhaps even charge itself. 
I plan to make it controllable over the internet (via a website for example) too by customizing the hardware used to build the remote.
I'm excited to build this because I've attempted to build a drone at a workshop before, and it didn't fly.

## Plan

1. Initially, I'll be assembling the hardware and I'll test whether the motors and ESCs work individually.
2. Following that, I'll be writing code to:
    1. Start/stop the motors and fly
    2. Communicate with the remote
    3. Control the device without physically using the remote by communicating with the remote using my phone via the internet
    4. [OPTIONAL] Add code to encode and transmit video to a device.
        - Otherwise, I can later get the video from the drone

## Hardware overview

Overview of generic components:

### Drone

| Component                   | Quantity | Purpose                                                          |
| --------------------------- | -------- | ---------------------------------------------------------------- |
| Controller: Arduino Due     | 1        | Controls drone                                                   | 
| Frame                       | 1        | Provides structure to the drone                                  |
| Brushless Motor             | 4        | Rotates propellers                                               |
| Drone Propellers            | 12       | Provides thrust to fly (4 use + 8 spare)                         |
| Electronic Speed Controller | 1        | Lets control drone motor speed for manuvering                    |
| Inertial Measurement Unit   | 1        | Provides basic physical data to the drone to acccount for errors |
| Power Distribution Board    | 1        | Distributes power from battery among motors                      |
| Video Trasmitter            | 1        | Transmits video from drone to remote/ground hardware             |
| NRF24L01 Transmitter        | 1        | Communicates with remote                                         |
| 4000 mAh Battery            | 1        | Provides electricity to drone                                    |
| LiPo Battery Charger        | 1        | Charges battery                                                  |
| Camera                      | 1        | Records video                                                    |

### Remote

| Component                       | Quantity | Purpose                   |
| ------------------------------- | -------- | ------------------------- |
| Controller: Raspberry Pi Pico W | 1        | Controls remote           |
| NRF24L01 Transmitter            | 1        | Communicates with drone   |
| Video Receiver                  | 1        | Receives video from drone |

### Misc

| Component       | Quantity | Purpose                                         |
| --------------- | -------- | ----------------------------------------------- |
| Breadboard      | 2        | Organize connections                            |
| Jumper cables   | 50       | Connect everything together                     |
| Generic Antenna | 4        | Extends range of NRF24L01 and Video transmitter |
| Zipties         | 50       | Hold parts together                             | 

## Budget

**Conversion Factor: $1 = ₹82.61**

| Product                                       | Supplier/Link                                                                                                  | Cost                       |
| --------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------- |
| Arduino Due                                   | https://robu.in/product/arduino-due-arm-cortex-m3-cpu-board/                                                   | ₹3400                      |
| Raspberry Pi Pico W                           | https://robu.in/product/raspberry-pi-pico-w/                                                                   | ₹650                       |
| Clone of TBS 500 Carbon Fiber Frame (has PDB) | https://robu.in/product/tbs-500-carbon-fiber-frame/                                                            | ₹2000                      |
| 2x CW 2300KV BLDC Motor                       | https://robu.in/product/rs2205-2300kv-cw-brushless-motor-fpv-racing-quad-motor-fpv-multicopter-qav250-qav300/  | ₹1500                      |
| 2x CCW 2300KV BLDC Motor                      | https://robu.in/product/rs2205-2300kv-ccw-brushless-motor-fpv-racing-quad-motor-fpv-multicopter-qav250-qav300/ | ₹1500                      |
| 4x Standard 30A BLDC ESC                      | https://robu.in/product/standard-30a-bldc-esc-electronic-speed-controller/                                     | ₹2360                      |
| 6x Pair of Glass Fiber Propeller              | https://robu.in/product/orange-hd-propellers-90459x4-5-glass-fiber-nylon-1cw1ccw-1pair-grey-2/                 | ₹900                       |
| 6DoF IMU: DFRobot Fermion ICG 20660L          | https://robu.in/product/dfrobot-fermion-icg-20660l-accelgyro-6-axis-imu-module-breakout/                       | ₹1950                      |
| 2x NRF24L01 Transmitter + Antenna             | https://robu.in/product/2-4ghz-nrf24l01palna-sma-antenna-wireless-transceiver-communication-module-1km/        | ₹360                       |
| 4200 mAh 3S LiPo Battery                      | https://robu.in/product/orange-4200mah-3s-35c-11-1-v-lithium-polymer-battery-pack-lipo/                        | ₹3000                      |
| RunCam Nano 3 800TVL                          | https://robu.in/product/runcam-nano-3-800tvl-camera/                                                           | ₹2000                      |
| 2x Breadboard                                 | https://robu.in/product/transparent-830-points-solderless-breadboard/                                          | ₹220                       |
| 65x M-M Jumpers                               | https://robu.in/product/65pcs-flexible-breadboard-jumper/                                                      | ₹103                       |
| LiPo Battery Charger                          | https://www.amazon.in/Robotbanao-Balance-Charger-Robotics-Science/dp/B09J2BB8T8                                | ₹500                       |
| 50x zipties                                   | https://www.amazon.in/Plastic-Strip-250mm-Locking-Nylon/dp/B076WYNB8L                                          | ₹125                       |
| Video Transmitter + Relevant Antenna          |                                                                                                                | Self-funded                |
| Video Receiver                                |                                                                                                                | Self-funded                | 
| **Total**                                     |                                                                                                                | **₹20568 ≈ $249**       |
