---
name: ["@ProbablySwifty", "@CulturedAsian", "@ShortyPhantom", "@JesusDonCarlos23"]
project: "Home Host"
---

# Home Host

## Summary

The advent of smart home devices is something that is genuinely exciting and has been forever expanding into more and more uses for your home. Amazon recently just released a new innovation, the Ring Always Home Camera, a drone that literally flies around your home to act as a security camera. We want to emulate this experience without the privacy concerns of having a large company being able to literally see your home and control everything. Especially with the recent controversies with companies such as [Eufy](https://www.techradar.com/news/anker-admits-eufy-camera-security-issues) which promised what happened in your home stayed in your home and proceeded to do exactly the opposite. It's hard to trust these companies when time and time again they fail, so,

## Plan

We want to build a computer that would be able to somewhat replace what Amazon and Google's smart home ecosystems is able to do. Hence, this requires heavy compute power in order to power the TensorFlow algorithms we are running, which is an image detection model and a voice recognition model. We want to train these models to largely adapt to a home environment, being able to detect and distinguish faces as well as respond to basic commands. In order to have the simulate the little speakers that Alexa and Google has, we will instead utilize a fleet of old Android devices as well as bluetooth speakers. These Android devices will be utilizing Droidcam in order to redirect both microphone input and camera input to the computer. This was the best solution that we could find to simulate a relatively wireless system within a smart home environment, with the only wire being needed is power. Bluetooth speakers will be deployed alongside these old Android devices in order to emulate the assistant speakers in conjunction with the microphones. For processing this data and pointing it to where it's going, we will be utilizing TensorFlow and training our own model based on our own needs. This will be running on the 6600 xt utilizing [ROCm](https://rocmdocs.amd.com/en/latest/) as our driver to better adapt these machine learning algorithms to our GPU. After setting this up, we'll be able to put in our commands to the script and figure out what the script should do when it detects things. We will have a list of key words that you can say to the device to trigger things such as lights turning on and playing music. However, for everything else, we will be utilizing ChatGPT's API in order to have a conversation with the system. The next key part of this project is that on top of the PC handling these devices, the PC will also function as a wireless router utilizing [OPNsense](https://opnsense.org/), an open source routing software that allows our PC to function as a wireless router. In this way, all the Android devices will wirelessly connect to the PC directly, rather than through a secondary machine. This will decrease latency and increase the speed in which the models will recieve the image/audio, process, and respond. Next, we want to be able to offer something else that these major companies currently do not offer. We will assemble a dual smoke and carbon monoxide sensor in an arduino that can be installed to monitor your home's safety. Through this system, it will send texts based on when one of the alarm triggers, this way, you can feel safer going in your home. Next, it will utilize the bluetooth speakers in order to still make an alarm noise. Lastly, we thought, where could this smart home management system possibly be placed in a PC? This was simple, we would run Android TV on the system and allow it to function as your home's smart TV on top of everything else. Through this, it will allow it to be able to solve the many issues of Smart TVs being slow. This single machine will be able to connect to various devices to use it as an alarm system, smart home system, and lastly, an Android TV. Multi-functional systems, here we come!

Ok, that was a lot of words and probably not the clearest wall of text but below we'll list off the features of this system and what it can do and how it does it. This time, it'll be in one short and sweet list rather than a messy wall of text

- Instantiated System
	- We will be using a Host and VM connection, with the VM managing the home security things. Through this way, it will be able to not have any access at all to the internet and ensure all your cameras are only accessible through one end-point, a dashboard website that will be connected to from the host.
- Wi-Fi Router Capabilities
	- The system will function as a Wi-Fi Router system. This will have a lot of benefits that will be mentioned later on.
- Camera and Smart Home System
	- Don't have the money to buy some cameras to install at home? Use your old phone! 
		- We are most likely going to use [Droidcam](https://www.dev47apps.com/) and modify their open-source client for Linux to handle multiple connections and the passthrough of the streams to TensorFlow
			- The phones connect directly to the system to allow for minimal latency and faster response times. By doing it this way, we can also ensure that the 
		- This also has the added benefit of functioning as a microphone
	- Will also be paired with a Bluetooth speaker accompanying the phone in order to communicate with the voice assistant	
	
- Local TensorFlow Processing 
	- What happens in your home stays in your home!
	- All the image detection and voice detection processing is run locally within the system and processed.
		- Will get the image from the camera and process and detect objects
			- If any of the use configured objects are detected, it can run a script when needed
				- Example use would be if it detected a person, it would send a text to the owner that a person was detected
				- Another example is that it would turn on smart lights if it detects a person walking into a room.
		- Will get voice samples and translate it into words
			- Our current voice activation word will be "Okay Arch" and "Hey Arch" (totally not ripped off)
			- Will be able to do a limited section of specialized voice commands as figured by use
			- Any trigger for conversation will redirect the OpenAI's ChatGPT
	- Will utilize AMD's ROCm to utilize the GPU for processing for faster response times.
- Wireless Carbon Monoxide, Smoke, and Gas Alarm
	- Wirelessly connected through either an Arduino or a Raspberry Pi 4b (we have both but can't decide yet which one to use)
		- The Particle Photon is to turn the alarm into an IOT device.
	- Will leverage the connected Bluetooth speakers to sound an alarm
	- Will also send a text alarm whenever it is trigerred.
- Android TV support
	- Can sit right beside your TV and work as your Smart TV!
	
| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| RX 6600 XT | https://www.amazon.com/PowerColor-Radeon-Gaming-Graphics-Powered/dp/B09BWR9J1M/ref=sr_1_3?crid=1DH0JGU1R48OJ&keywords=6600xt&qid=1673403275&s=electronics&sprefix=%2Celectronics%2C94&sr=1-3&ufe=app_do%3Aamzn1.fos.c3015c4a-46bb-44b9-81a4-dc28e6d374b3&th=1 | $314.97 |
| CPU and Motherboard|https://www.amazon.com/dp/B07PV7GL6C?tag=pcpapi-20&linkCode=ogi&th=1| $65.97 |
| SSD|https://www.amazon.com/dp/B07Q37V1C9?tag=pcpapi-20&linkCode=ogi&th=1 | $92.99 |
| Cooler| https://www.amazon.com/Thermaltake-Motherboard-Addressable-Universal-CL-P105-AL12SW/dp/B09XFKW431/ref=sr_1_2?keywords=lga+1700+cooler&qid=1673534907&sr=8-2 | $24.99 |
| Analog Rotation Potentiometer| https://www.dfrobot.com/product-87.html | $2.90 |
| Analog Gas Sensor  | https://www.dfrobot.com/product-681.html | $6.90 |
| Analog LPG Gas Sensor  | https://www.dfrobot.com/product-684.html | $6.90|
| Analog CO Sensor  | https://www.dfrobot.com/product-686.html | $9.85|
| Particle Photon  | https://www.dfrobot.com/product-1324.html |  $19.00 |
| MPSA13 transistor (Darlington pair) | https://guitarpcb.com/product/mpsa13/ | $0.49 |
| Arduino | https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=sr_1_3?crid=36VFKB0A8DW0P&keywords=arduino&qid=1673581888&sprefix=arduino%2Caps%2C148&sr=8-3 | $28.50 |
| Case|Owned|Owned|
| 750w Power Supply|Owned|Owned|
| Taxes      |                                       | $75.3|
| Shipping | | $9.45|
|Total           |                                       | $1,012.09|
