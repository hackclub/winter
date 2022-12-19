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

| Component                     | Quantity | Purpose                                                          |
| ----------------------------- | -------- | ---------------------------------------------------------------- |
| Controller: Raspberry Pi Pico | 1        | Controls drone by changing motor speeds                          |
| Frame                         | 1        | Provides structure to the drone                                  |
| Brushless Motor               | 4        | Rotates propellers                                               |
| Drone Propellers              | 12       | Provides thrust to fly (4 use + 8 spare)                         |
| Electronic Speed Controller   | 1        | Lets control drone motor speed for manuvering                    |
| Inertial Measurement Unit     | 1        | Provides basic physical data to the drone to acccount for errors |
| Power Distribution Board      | 1        | Distributes power from battery among motors                      |
| Video Trasmitter              | 1        | Transmits video from drone to remote/ground hardware             |
| NRF24L01 Transmitter          | 1        | Communicates with remote                                         |
| 4000 mAh Battery              | 1        | Provides electricity to drone                                    |
| LiPo Battery Charger          | 1        | Charges battery                                                  |
| Camera                        | 1        | Records video                                                    |

### Remote

| Component                       | Quantity | Purpose                   |
| ------------------------------- | -------- | ------------------------- |
| Controller: Raspberry Pi Pico W | 1        | Controls remote           |
| NRF24L01 Transmitter            | 1        | Communicates with drone   |
| Video Receiver                  | 1        | Receives video from drone |

### Misc

| Component     | Quantity | Purpose                                         |
| ------------- | -------- | ----------------------------------------------- |
| Breadboard    | 2        | Organize connections                            |
| Jumper cables | 50       | Connect everything together                     |
| Antenna       | 4        | Extends range of NRF24L01 and Video transmitter |

## Budget

```
// TODO find part sources and exact parts list  
// Exclude items already present like jumpers
```
