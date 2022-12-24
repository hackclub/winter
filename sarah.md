---
name: "@Sarah"
project: "AI robotic arm"
---

# AI robotic arm

## Summary

AI will kill us all. I'd like to help.

This robotic arm will have a wide range of motion, as well as use on-device machine vision to pick up objects.

At the heart of the project is the Google Coral Dev Board Mini, which contains the Edge TPU, which will help greatly with machine vision.

It will be controlled remotely using the Dev Board's on-board Wi-Fi.

It's also powered by USB-C, bscause I thought that was funny :)

## Plan

-   Design the robotic arm using some 3D modelling software.
-   Print its parts via a 3D printing provider (I don't have a printer, unfortunately)
-   Solder everything together. This is one of the few things I actually own.
-   Assemble.
-   Use Rust and a pre-compiled AI model for Coral to implement machine vision.
-   Hope it does not catch on fire.

## Budget

| Product                       | Supplier                                                                                       | Cost (in GBP) |
| ----------------------------- | ---------------------------------------------------------------------------------------------- | ------------- |
| Google Coral Dev Board Mini   | [Pi Hut](https://thepihut.com/products/google-coral-dev-board-mini)                            | £121          |
| Google Coral Camera           | [Pi Hut](https://thepihut.com/products/google-coral-camera)                                    | £19.50        |
| Shipping                      | Pi Hut                                                                                         | £2.99         |
| 5x NEMA-17 Stepper motors     | [Amazon](https://www.amazon.co.uk/iMetrx-stepper-42x34mm-Creality-extruder/dp/B097JK4D85/)     | £33.99        |
| USB-C Laptop charger          | [Amazon](https://www.amazon.co.uk/Adapter-Charger-Lenovo-ThinkPad-Chromebook/dp/B09DP22KTM/)   | £17.99        |
| 5x A4988 Motor drivers        | [Amazon](https://www.amazon.co.uk/Pieces-Driver-Stepper-Stepstick-Printer/dp/B096XM7J4Z/)      | £7.79         |
| 2x Buck converter             | [Amazon](https://www.amazon.co.uk/Converter-1-25-36V-Voltage-Regulator-Display/dp/B0895QT2YH/) | £12.99        |
| 5A Type-C PD/QC Trigger board | [eBay](https://www.ebay.co.uk/itm/255577092563)                                                | £1.54         |
| **Total**                     | -                                                                                              | £217.75       |
| **Total (in USD)**            | -                                                                                              | $262.45       |

Note that tax is included in the price.
