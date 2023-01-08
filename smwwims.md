---
name: "@smwwims"
project: Autonomous Plant Farm
---

# Autonomous Plant Farm

## Summary

I have always had a keen interest in botany, but unfortunately my gardening skills do not quite match my programming skills. 
That is why I came up with the idea of building a fully automatic cultivation machine. In contrast to the "Smart Planting Sets" 
available on the market, my machine is not a simple control circuit, but a regulation circuit. This means that the water and light 
supply is not simply controlled by the time but responds to the needs of the plants via sensors.

## Plan

1. Preparing the plant pot:   Install the water tank, demarcate the electronic part
2. Water supply:              Install pump, install water pipe. There are two water pumps: The main water pump supplies the plants with water. Below the ground is an aluminum sheet with holes. The water can run off there and flow into a catch basin. The water is pumped back from this catch basin to the water tank via the secondary pump. This protects the plants from waterlogging. The water pumps are controlled by the arduino via relays.
3. Sensors:                   Wire the sensors; Because the "plant farm" is pretty large I need multiple moisture and light sensors in order to measure the soil moisture and the sun exposure acurately. 
4. Light:                     Install and wire the plant light. The plant light is controlled based on the brightness level of its surroundings. This is done via a LDR, which is evaluted by the Arduino. The Arduino controls the plant light via a relay. The Arduino is not controlling the plant light itself, but the relay. The relay works as a switch: If it gets a signal from the Arduino the circuit gets closed and the lamp can shine.
The Arduino also reads in the values from the LDR. If the brightness falls below the threshold programmed in the Arduino, the Arduino switches the plant light on. (except it’s night, then not).
5. Programming:               Make it all work through software

## Budget

| Product                     | Supplier/Link                                                                                | Cost   |
| --------------------------- | -------------------------------------------------------------------------------------------- | ------ |
| Plant Pot                   | https://www.amazon.de/-/en/gp/product/B08KWPGMGY/ref=ewc_pr_img_13?smid=A2WPX7PK44TEBQ&th=1  | $41.69 |
| Water Tank                  | https://www.amazon.de/-/en/gp/product/B0B8YSNG5C/ref=ewc_pr_img_1?smid=A3TW56H8H7ZPJ&th=1    | $26.78 |
| Aluminium Sheet             | https://www.amazon.de/-/en/gp/product/B07XC24C9G/ref=ewc_pr_img_1?smid=A34I19W3628WJL&th=1   | $20.41 |
| Water Hose                  | https://www.amazon.de/-/en/gp/product/B07RDJY6DT/ref=ewc_pr_img_1?smid=A3JWKAKR8XB7XF&th=1   | $12.85 |
| Plant Lamp                  | https://www.amazon.de/-/en/gp/product/B0B1MRYNWR/ref=ewc_pr_img_1?smid=A1Y73AAMUAXH83&th=1   | $25.71 |
| Arduino Plant Watering Kit  | https://www.amazon.de/-/en/gp/product/B0BJ7W59SS/ref=ewc_pr_img_1?smid=A1X7QLRQH87QA3&th=1   | $25.92 |
| LCD Display                 | https://www.amazon.de/-/en/gp/product/B07Y4RFLZ5/ref=ewc_pr_img_1?smid=A1A7E5ILEFA1R3&psc=1  | $15.64 |
| Breadboard PCB              | https://www.amazon.de/-/en/gp/product/B0734XYJPM/ref=ewc_pr_img_1?smid=AZF7WYXU5ZANW&psc=1   | $14.99 |
| Main Water Pump             | https://www.amazon.de/gp/product/B071JXJ9BR/ref=ox_sc_act_title_1?smid=ADNI1MM5F189O&psc=1   | $26.78 |
| Relay                       | https://www.amazon.de/-/en/gp/product/B07CNR7K9B/ref=ewc_pr_img_1?smid=A1X7QLRQH87QA3&psc=1  | $7.49  |
| Moisture Sensor             | https://www.amazon.de/-/en/gp/product/B07CQT5RC8/ref=ewc_pr_img_1?smid=A3BI8G9NTBZUKM&psc=1  | $6.42  |
| LDR's                       | https://www.amazon.de/-/en/gp/product/B07DDNSKLC/ref=ewc_pr_img_1?smid=A1X7QLRQH87QA3&psc=1  | $6.42  |
| Temperature Sensor          | https://www.amazon.de/-/en/gp/product/B078SVZB1X/ref=ewc_pr_img_1?smid=A1X7QLRQH87QA3&psc=1  | $10.17 |
| Soldering Set               | I already own one.                                                                           | -      |
| Wires                       | I already have a few.                                                                        | -      |
| Total                       | Including taxes and delivery costs                                                           | $241,27|
