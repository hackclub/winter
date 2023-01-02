---
name: "@l3gacyb3ta"
project: "Collapse-resistant Mesh Networking"
---

# Collapse-resistant Mesh Networking

## Summary

I want to build a super simple mesh-network, for a theoretical post-collapse world. I mean collapse as in major infrastructure failing to provide support anymore, so what most people would call off-grid (i guess i have CollapseOS brianrot :3 [^1]). Ideally this would support many forms of interaction, so it could work even if people lost acess to phones. Some previous work I am inspired by is:
- [meshtastic](https://meshtastic.org/)
- [disaster.radio](https://disaster.radio/)
- [LOW←TECH MAGAZINE's solar website](https://solar.lowtechmagazine.com/about.html)

## Plan

1. Research actual networking solutions.
1. Get a serial-based version working.
1. Optimize power usage and online-offline transition
1. Build a web interface.
    * Probably using something like <https://randomnerdtutorials.com/esp32-web-server-arduino-ide/> and a small HTML framework I am currently working on
1. Test at a larger scale.
1. Deployment at my school!

## Budget

| Product                       | Supplier/Link                                                                                                                                                    | Cost    |
|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| LILYGO® TTGO US(915MHz) x 3   | https://store.rokland.com/products/lilygo-ttgo-meshtastic-t-beam-v1-1-esp32-lora-915-mhz-wireless-module-wifi-gps-neo-6m-with-oled-display-for-arduino-q202-l206 | $128.30 |
| TTL Serial USB Adapter        | https://www.amazon.com/DSD-TECH-Adapter-FT232RL-Compatible/dp/B07BBPX8B8/                                                                                        | $15.40  |
| 5v 1.2w Solar Panel x 3       | https://www.adafruit.com/product/5368                                                                                                                            | $55.33  |
| 3.3-6v to 3.3v Buck Converter | https://www.aliexpress.us/item/2251832868235446.html?gatewayAdapt=glo2usa4itemAdapt&_randl_shipto=US                                                             | $8.10   |
| 18650 Batteries x 3           | https://www.amazon.com/Tokeyla-1%EF%BF%B58%EF%BF%B56%EF%BF%B55%EF%BF%B50-Rechargeabe-Batteries-Flashlights/dp/B0BG8CX93Q                                         | $24.99  |
| Total                         |                                                                                                                                                                  | $232.12 |

[^1]: <https://collapseos.org>
