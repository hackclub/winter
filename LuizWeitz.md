---
name: "@LuizWeitz"
project: "Cloud Server for less than 200 dollars with self-management"
---

# Cloud Server for less than 200 dollars with self-management

## Summary

Hello, in this project I will show you how to create a high-performance cloud server in your home with self-management. 
We will have the following functions

- Heat management -> The server will control its temperature automatically, that is, if it reaches a certain temperature, it will activate 2 mini coolers until it reaches a cold temperature
- Dashboard with temperature graphics and hardware consumption
- Deploying projects via CD|CI pipeline with GitActions
- Alerts via email/consumer slack... deploy

To build we will use
- Orange Pi (8-core 64-bit processor 8GB ram)
- Golang
- Arduino language
- ESP8266
- SD card 128 gb
...
And a lot of pizza 😋

## Plan

First part
- Let's create a rest api using Golang and a panel using Angular

Second part
- Let's assemble our server (hardware)

Third part
- Installation and configuration of Ubuntu and our API

Fourth part
- Let's load a rest API on our server

Fifth part
- Let's connect a DNS domain to our server

OBS : I will be creating a tutorial so more members can do it at home

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ | 
| Orange Pi 5 (Bundle 3) | https://pt.aliexpress.com/item/1005005089388848.html?spm=a2g0o.cart.0.0.484a7f06bws0Nd&mp=1&gatewayAdapt=glo2bra | US$127.56  |
| 5V Sleeve 2P2.0 7F (2x) | https://www.aliexpress.com/item/32884821022.html?spm=a2g0o.cart.0.0.484a38daPX2q2H&mp=1  | US$8.42 |
| Lexar Micro SD Card 128gb | https://www.aliexpress.com/item/1005003780732823.html?spm=a2g0o.cart.0.0.484a38daPX2q2H&mp=1 | US$15.06 |
| DS18B20 Temperature Sensor Module Kit | https://www.aliexpress.com/item/1005004510890825.html?spm=a2g0o.cart.0.0.484a38daPX2q2H&mp=1 | US$6.15 |
| ESP-32S | https://www.aliexpress.com/item/1005002611857804.html?spm=a2g0o.cart.0.0.484a38daPX2q2H&mp=1 | US$14.15 | 
| source of strength | i have | US $0.0  |
| breadboard | i have | US $0.0 |
| jumpers | i have | US $0.0 | 
| Total |                                                  | $171.34 |
