---
name: "@Bhoomi-2115"
project: "Glucose Tracking Using Raspberry Pi"
---

# Project Name
Glucose Tracking Using Raspberry Pi

## Summary

Owing to the genetics, me and my sister carry a high risk for diabetes and we are advised to check the blood glucose leevls regularly. But, the conventional meters do not have any advanced tracking functionality which can track levels of two individuals with same device. So using the power of Internet of Things and Machine Learning to analyse the data collected. I aim to improve the diagnostic ability of blood glucose measuring. I am excited to work on this project as I will be learning a lot at the same time.

## Plan

[Reference Document](http://www.ece.utep.edu/courses/web1305/EE1305/modules/module_6.htm) from University of Texas at El Paso
First of all I will wait for the components to arrive since it will need a bit of trial and error.
1. Use the Operational Amplifier to build a circuit that will measure the voltages and currents that are produced due to the electrochemical reacion on the glucose testing strips.
  - Build a circuit using the Arduino UNO, the operational amplifier, resistors and breadboard. (Will require a bit of trial and error due to change of voltages across dffere brands of strips)
  - Connect the Arduino UNO to Raspberry PI and set up serial logging.
  - Follow the same document to create a rudimentary probe for the electrodes using bent metal strips. Alternatively, the head of an existing glucometer can be repurposed.

2. Calibration
  - Probing an existing functional glucose meter to measure the change in voltage over time and the reference reading.
  - Perform the same usig Raspberry Pi and Arduino UNO to build corellations
  - [Reference Document](https://www.nxp.com/docs/en/application-note/AN4364.pdf)

3. Measure the parameters using Arduino UNO and send them to Raspberry Pi (For Streaming Data) to categorize the data wheter it is me or my sister and send it to the storage and analysis Raspberry Pi.
  - Since the voltage changes with time, the change in voltage with time is measured to determine the blood glucose level. Owing to the computational limitation of UNO, this has to be done on Rspberry Pi.
  - The voltage values are fed to the Raspberry Pi.
  - Raspberry Pi determines the blood glucose level
  - Sends it to storage server

4. Data is received on storage server along with unique ID of individual and the trends are stored and the risk of diabetes is visualised with the help of existing trained models of Diabetes Data and displayed on the screen.

## Budget

| Product                                                               | Supplier/Link                                                                                 | Cost (in INR)  |  Approx Cost (in USD) |
| --------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | -------------- | --------------------- |
| Raspberry Pi 4 Model-B with 8 GB RAM (For Streaming Data)             | https://robu.in/product/raspberry-pi-4-model-b-with-8-gb-ram/                                 | ₹7999          | $97                   |
| Raspberry Pi 4 Model-B with 8 GB RAM (For Storing and Analysing Data  | https://robu.in/product/raspberry-pi-4-model-b-with-8-gb-ram/                                 | ₹7999          | $97                   |
| SanDisk Micro SD/SDHC 32GB Class 10 Memory Card                       | https://robu.in/product/sandisk-micro-sd-sdhc-32gb-class-10-memory-card-with-adapter/         | ₹489           | $5.92                 |
| Waveshare 4.3 Inch Capacitive Touch Display for Raspberry Pi 800?480  | https://robu.in/product/waveshare-4-3-inch-capacitive-touch-display-for-raspberry-pi-800x480/ | ₹3299          | $39.09                |
| Official USB type-C 15.3W Power Supply For Raspberry Pi 4             | https://robu.in/product/official-usb-type-c-15-3w-power-supply-for-raspberry-pi-4/            | ₹749           | $9.07                 |
| LM358P PDIP-8 High Gain Operational Amplifier (Pack of 5 ICs)         | https://robu.in/product/lm358p-pdip-8-high-gain-operational-amplifier-pack-of-5-ics/          | ₹49            | $0.59                 |
| Pack of Resistors                                                     | Already Own                                                                                   | ₹0             | $0                    |
| Breaboard and Power Supply for Arduino                               | Already Own                                                                                   | ₹0             | $0                    |
| Multimeter                                                            | Already Own                                                                                   | ₹0             | $0                    |
| Total                                                                 |                                                                                               | ₹20584         | $248.67               |
