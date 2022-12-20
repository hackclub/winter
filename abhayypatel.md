---
name: "@abhayypatel"
project: "PiPriceWatch"
---

# PiPriceWatch

## Summary

The main purpose of this alert system is to notify users of significant changes in the value of a certain cryptocurrency. By monitoring the price of the cryptocurrency and detecting when it goes up or down exponentially, the system can alert the user in real-time and provide them with timely information about market trends. This can be especially useful for people who are actively trading or investing in cryptocurrency, as they may want to stay informed about sudden price movements and make informed decisions about buying or selling their assets.

The raspberry pi will play a key role in this system, serving as both a server to track cryptocurrency prices and a mail server to send out alerts. By hosting a mail server on the raspberry pi, the system can send out alerts to the user via email, ensuring that they receive timely notifications even when they are not physically near the alert system. In addition to email alerts, the system will also use text-to-speech technology to announce the cryptocurrency that is going up or down, providing a visual and auditory notification for the user.

Overall, I am excited to build this project because it combines several different technologies and tools, including the raspberry pi, text-to-speech, and email alerts, to create a unique and useful alert system for cryptocurrency holders. The ability to stay informed about significant price movements in real-time can be valuable for anyone looking to make informed decisions about their cryptocurrency investments, and I am eager to see how this system can help people navigate the volatile world of cryptocurrency trading.


## Plan

1. Set up a Raspberry Pi and configure it as a server. This will involve installing the necessary operating system and setting up any required dependencies.

2. Get a list of the top 1000 cryptocurrencies to monitor and use coinmarketcap to track their price real-time.

3. Implement a system for detecting significant price changes in the cryptocurrency. This will involve setting up a threshold for the percentage change in price.

4. Set up the Raspberry Pi to send email alerts when significant price changes are detected. This will involve installing and configuring a mail server on the Raspberry Pi, as well as writing code to send the emails when triggered by the price change detection system.

5. Implement text-to-speech functionality to announce the cryptocurrency that is going up or down. I'd also be implementing the RBG and alarm sound to go off before the TTS announces the cryptocurrency.

6. Test the system to ensure that it is working properly and sending alerts as expected. This will involve manually triggering alerts by simulating price changes and verifying that the alerts are sent and received correctly.

7. Deploy the system and begin using it to stay informed about significant price changes in the cryptocurrency of choice. This will involve keeping the Raspberry Pi running and monitoring the alerts as they come in.


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |

| Raspberry Pi   | https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TD42S27?tag=georiot-us-default-20&ascsubtag=tomshardware-us-5967095305306638000-20&geniuslink=true&th=1  | $125.67  |
| Raspberry Pi Case | https://www.amazon.com/Flirc-Raspberry-Pi-Case-Silver/dp/B07WG4DW52/ref=sr_1_6?keywords=raspberry+pi+4+case&qid=1671454629&s=electronics&sr=1-6   | $15.95 |
| Raspberry Pi SD Card | https://www.amazon.com/SanDisk-256GB-Extreme-microSD-Adapter/dp/B07FCR3316/ref=sr_1_15?keywords=sd+card&qid=1671462466&sr=8-15   | $33.88 |
| Raspberry Pi Power Supply | https://www.amazon.com/Raspberry-Model-Official-SC0218-Accessory/dp/B07W8XHMJZ/ref=sr_1_3?keywords=raspberry+pi+4+power+supply&qid=1671460848&s=electronics&sprefix=raspberry+pi+4+powe%2Celectronics%2C56&sr=1-3 | $7.99 |
| Raspberry Pi RBG, Speakers, etc. | https://www.amazon.com/Freenove-Complete-Raspberry-708-Page-Tutorial/dp/B09ZXNL2WH/ref=sr_1_13?crid=1KOPVMV5FO7ML&keywords=raspberry+pi+4+accessories&qid=1671460872&s=electronics&sprefix=raspberry+pi+4+acc%2Celectronics%2C54&sr=1-13  | $59.95 |

| Total           |                                       | $243.44 |
