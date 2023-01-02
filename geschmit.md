---
name: "@geschmit"
project: "Forbidden Airprinter"
---

# Forbidden Airprinter

## Summary
My project is to take a vintage line/dot-matrix printer from a reseller market and enable AirPrint on it via an external SBC, which will allow modern devices to use it like a generic network-connected printer. These devices are usually only accessable via old and obsolete protocols, like RS232 and various parallel types, which can defeat their actual purpose of, well... printing, since modern computers don't have driver support or ports themselves to connect to.

## Plan
My plan is to:
- First, obtain a working printer capable of connecting via RS232 communications. This will be the hardest part, as most resellers cannot test if their printers work or not due to the aformentioned reasons above.
- Afterwards, construct and connect a WiFi-enabled SBC(in this case, I'm using a ESP32) to the printer's serial to advertise it as a network-connected printer.
- Finally, experience the loud noises of an obsolete technology that will definitely get me evicted from my house.

## Budget

| Product | Supplier/Link | Cost | Additional notes |
| --- | --- | --- | --- |
| RS232-TTL converter | https://www.elecrow.com/rs232-to-ttl-converter-module-max3232-p-762.html | 0.80$ | I'm unable to find one that connects directly to parallel. |
| Parallel(new)-parallel(old) cable | N/A | N/A | Already in possession of. |
| Printer | https://www.ebay.com/itm/363857048431?epid=18053339161 | ~$125.00  | I am allocating 125$ as finding a working printer will be the hardest part of my project. Several items on EBay look promising, but I'm willing to take suggestions if any better sources are known. |
| SBC | https://www.adafruit.com/product/3591 | 20.95$ | N/A |
| RS232-parallel(new) cable | | |
| Total | => | 140.95$$ | |
