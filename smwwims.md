---
name: "@smwwims"
project: Autonomous Plant Farm
---

# Autonomous Plant Farm

## Summary

I have always had a keen interest in botany, but unfortunately my gardening skills do not quite match my programming skills. 
That is why I came up with the idea of building a fully automatic smart garden. In contrast to the "Smart Planting Sets" 
available on the market, my machine is not a simple control circuit, but a regulation circuit. This means that the water and light 
supply is not simply controlled by the time but responds to the needs of the plants via sensors. Furthermore, my smart garden is not ought to grow plants in as short time as possible, but to give plants a solid environment to grow for a longer period of time.

## Plan

1. Preparing the plant pot:   Install the water tank, demarcate the electronic part
2. Water supply:              Install pump, install water pipe. There are two water pumps: The main water pump supplies the plants with water. Below the ground is an aluminum sheet with holes. The water can run off there and flow into a catch basin. The water is pumped back from this catch basin to the water tank via the secondary pump. This protects the plants from waterlogging. The water pumps are controlled by the arduino via relays. Water tank levels are monitored by ultrasonic distance sensors.
3. Sensors:                   Wire the sensors; Because the "plant farm" is pretty large I need multiple moisture and light sensors in order to measure the soil moisture and the sun exposure acurately. The ultrasonic sensors are used for water level measurement.
4. Light:                     Install and wire the plant light. The plant light is controlled based on the brightness level of its surroundings. This is done via a LDR, which is evaluted by the Arduino. The Arduino controls the plant light via a relay. The Arduino is not controlling the plant light itself, but the relay. The relay works as a switch: If it gets a signal from the Arduino the circuit gets closed and the lamp can shine.
The Arduino also reads in the values from the LDR. If the brightness falls below the threshold programmed in the Arduino, the Arduino switches the plant light on. (except it’s night, then not).
5. Programming:               Make it all work through software

## Budget

| Product                     | Supplier/Link                                                                                     | Cost   |
| --------------------------- | ------------------------------------------------------------------------------------------------  | ------ |
| Plant Pot                   | https://www.amazon.de/-/en/gp/product/B08KWPGMGY/ref=ewc_pr_img_13?smid=A2WPX7PK44TEBQ&th=1       | $42.37 |
| Water Tank                  | https://www.amazon.de/-/en/gp/product/B0B8YSNG5C/ref=ewc_pr_img_1?smid=A3TW56H8H7ZPJ&th=1         | $27.22 |
| Aluminium Sheet             | I already have a few.                                                                             | -      |
| Water Hose                  | https://www.amazon.de/-/en/gp/product/B07RDJY6DT/ref=ewc_pr_img_1?smid=A3JWKAKR8XB7XF&th=1        | $13.07 |
| Plant Lamp                  | https://www.amazon.de/-/en/gp/product/B0B1MRYNWR/ref=ewc_pr_img_1?smid=A1Y73AAMUAXH83&th=1        | $26.13 |
| Arduino Plant Watering Kit  | https://www.amazon.de/-/en/gp/product/B0BJ7W59SS/ref=ewc_pr_img_1?smid=A1X7QLRQH87QA3&th=1        | $26.13 |
| LCD Display                 | I already have one.                                                                               | -      |
| Breadboard PCB              | I already have one.                                                                               | -      |
| Main Water Pump             | https://www.amazon.de/gp/product/B071JXJ9BR/ref=ox_sc_act_title_1?smid=ADNI1MM5F189O&psc=1        | $27.22 |
| Relay                       | https://www.amazon.de/-/en/gp/product/B07CNR7K9B/ref=ewc_pr_img_1?smid=A1X7QLRQH87QA3&psc=1       | $7.60  |
| Moisture Sensors            | https://www.amazon.de/-/en/gp/product/B07CQT5RC8/ref=ewc_pr_img_1?smid=A3BI8G9NTBZUKM&psc=1       | $6.52  |
| LDR's                       | I already have a few.                                                                             | -      |
| Temperature Sensor          | https://www.amazon.de/-/en/gp/product/B078SVZB1X/ref=ewc_pr_img_1?smid=A1X7QLRQH87QA3&psc=1       | $10.17 |
| Wire Stripper               | https://www.amazon.de/-/en/gp/product/B002BDNL4Q/ref=ox_sc_act_title_1?smid=A3JWKAKR8XB7XF&psc=1  | $14.11 |
| Crimping Set                | https://www.amazon.de/-/en/gp/product/B0B1PZBHS2/ref=ox_sc_act_title_2?smid=AXKKVRPZ5O9AK&psc=1   | $22.64 |
| Ultrasonic Distance Sensors | https://www.amazon.de/-/en/gp/product/B07MPZR59P/ref=ox_sc_act_title_3?smid=A25JVW2SL3EPBX&psc=1  | $8.61  |
| Cable Glands                | https://www.amazon.de/-/en/gp/product/B09XGNLD4B/ref=ox_sc_act_title_4?smid=A2UXDZ7ZFKAH1&psc=1   | $15.24 |
| Soldering Set               | I already own one.                                                                                | -      |
| Wires                       | I already have a few.                                                                             | -      |
| Total                       | Including taxes and delivery costs                                                                | $247,03|
