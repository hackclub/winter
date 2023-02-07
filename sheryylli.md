---
name: "@sheryylli"
project: "QPong game console"
---

# Qpong game console

## Summary

What are you going to build? What does it do? Why are you excited to build it?

I've recently been getting into quantum computing, and there's this game created called QPong that is basically the classical pong game but quantum version. I'm super excited to create quantum versions of traditional classical games and experiencing them hands on. Most of quantum computing is directed towards algorithmic design and hardware, but I'm curious to see how qubits can affect games (and it's fun)

## Plan

What steps are you going to take to build it? What tools are you going to use? What will you do first, second, third, etc.?

Qiskit has released a tutorial on programming Qpong, which will be my first test run to learn how to make a quantum terminal game. To connect a quantum computer to the arduino, I'll use qiskit to access IBM's quantum computer, get my IBM API token, setup my env (including qiskit), and connect with the arduino. I'll first check the connection by following the connection steps and set it up with led lights on the motherboard- if qubit value is 0, it will light up red; if the qubit value is 1, it will light up blue. 

Physically, I'll connect five buttons to pins 5,10,11,12, and 13. The arduino board and VGA connector will be in a wooden box. 

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Arduino uno REV3    | https://www.amazon.com/ Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=asc_df_B008GRTSV6/?tag=hyprod-20&linkCode=df0&hvadid=309751315916&hvpos=&hvnetw=g&hvrand=10875669126403176495&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9007825&hvtargid=pla-457497319401&psc=1&tag=&ref=&adgrpid=67183599252&hvpone=&hvptwo=&hvadid=309751315916&hvpos=&hvnetw=g&hvrand=10875669126403176495&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9007825&hvtargid=pla-457497319401 | $28.50  |
| DSUB15 Connector | https://www.amazon.com/CableWholesale-Female-Solder-Connector-3530-04115/dp/B000I21YXM?th=1  | $7.66 |
| resistors (need 68ohm, 470ohm, 2ohm specifically) | https://www.amazon.com/BOJACK-Values-Resistor-Resistors-Assortment/dp/B08FHPJ5G8/ref=sxin_15_pa_sp_search_thematic_sspa?content-id=amzn1.sym.14a246c3-7a62-40bf-bdd0-5ac67c2a1913%3Aamzn1.sym.14a246c3-7a62-40bf-bdd0-5ac67c2a1913&crid=3NJWKZJXAYLD5&cv_ct_cx=all+resistors+for+arduino&keywords=all+resistors+for+arduino&pd_rd_i=B08FHPJ5G8&pd_rd_r=f8427baf-b228-4b8c-82f3-bb22d4a9d45e&pd_rd_w=iasZd&pd_rd_wg=4OdFz&pf_rd_p=14a246c3-7a62-40bf-bdd0-5ac67c2a1913&pf_rd_r=5RAKXSRV5AYKRPQ63CTS&qid=1673849687&sprefix=all+resistors+for+arduino%2Caps%2C127&sr=1-2-a73d1c8c-2fd2-4f19-aa41-2df022bcb241-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzRVdYQ01ZOVNGUlYmZW5jcnlwdGVkSWQ9QTAxMDI2MTcyS0JTRlJNNFdFNDgxJmVuY3J5cHRlZEFkSWQ9QTAxOTU1NDkxTk84SVI1MUQ1UUZUJndpZGdldE5hbWU9c3Bfc2VhcmNoX3RoZW1hdGljJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==  | $13.99 |
| pentiometers   | https://www.amazon.com/TWTADE-Adjustable-Potentiometer-Resistance-XH2-54-3P/dp/B082FCRQS2/ref=sr_1_3?crid=ACGOR3LH4K89&keywords=10+kOhm+linear+potentiometers&qid=1673849825&sprefix=10+kohm+linear+potentiometers%2Caps%2C397&sr=8-3 | $10.99  |
| pack of wires  | https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78/ref=sr_1_6?crid=2HFTQRPM2CDF9&keywords=arduino%2Bcable&qid=1673850157&s=industrial&sprefix=arduino%2Bcable%2Cindustrial%2C87&sr=1-6&th=1 | $6.98  |
| cable | https://www.amazon.com/DIYmall-Cable-Arduino-2560-Pack/dp/B09JRXT1TY/ref=sr_1_3?crid=2BXIUM6V66XGK&keywords=arduino+cable&qid=1673850284&s=industrial&sprefix=arduino+cable%2Cindustrial%2C162&sr=1-3 | $6.99  |
| cable | https://www.amazon.com/DIYmall-Cable-Arduino-2560-Pack/dp/B09JRXT1TY/ref=sr_1_3?crid=2BXIUM6V66XGK&keywords=arduino+cable&qid=1673850284&s=industrial&sprefix=arduino+cable%2Cindustrial%2C162&sr=1-3 | $6.99  |
| solder | https://www.amazon.com/dp/B097XX76V4/ref=sspa_dk_detail_4?psc=1&pd_rd_i=B097XX76V4&pd_rd_w=rid5f&content-id=amzn1.sym.dd2c6db7-6626-466d-bf04-9570e69a7df0&pf_rd_p=dd2c6db7-6626-466d-bf04-9570e69a7df0&pf_rd_r=AT2DZ5YTAVN2K5S5F3WG&pd_rd_wg=TlcQK&pd_rd_r=69bf8ce8-fe49-42bd-bf80-2fe0b9abeeb8&s=hi&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWxfdGhlbWF0aWM&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyS1NQNzNLVVdJVlRCJmVuY3J5cHRlZElkPUEwNTc0NTEyR1Y4Uk9GWlFPMEtIJmVuY3J5cHRlZEFkSWQ9QTAwMTQxMDMzMEk0SjJTQ1BXVjFZJndpZGdldE5hbWU9c3BfZGV0YWlsX3RoZW1hdGljJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ== | $17.99  |
| display | https://www.amazon.com/Treedix-Display-Screen-Arduino-Mega2560/dp/B0872S57HG/ref=sr_1_16?crid=2S1PEHMIPE9CO&keywords=arduino+display+big&qid=1673851205&s=electronics&sprefix=arduino+display+big%2Celectronics%2C74&sr=1-16 | $18.99  |
| shipping and tax: $3.37 free shipping |
| Total           |                                       | $112.37 |
