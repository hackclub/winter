---
name: "@Dishit79"
project: "Selfhosted Home Assitant"
---

# "Hey Jarreth: A selfhosted Home Assitant"

## Summary

I am excited to build my own self-hosted home assistant using Python. I have always wanted to have an home assistant but I do not want to get one from some big tech company as I am concerned about their ability to snoop on me. By building my own home assistant, I will have complete control over my data and privacy. I am looking forward to the challenge of creating my own assistant and the benefits it will bring to my daily life.

## Plan

I have already developed a plan for this project. It will have two main components: a listening device and a processing device. The listening device will first capture audio from the app, which will be created using React Native or Flutter. Then, it will stream the audio to the processing server (which is my home server) where it will be translated to text using the Python library [https://pypi.org/project/SpeechRecognition/](https://pypi.org/project/SpeechRecognition/). To determine what command is being asked, it will use the Python library [https://pypi.org/project/awesome-pattern-matching/](https://pypi.org/project/awesome-pattern-matching/) which can match keywords from the sentence given. For example, if a command called "set timer" is created, and the keywords associated with it are "timer, alarm," the program will look for those keywords and, once it identifies that it is that command, it will then look for subcommands like "hours, seconds, minutes." The objective is to build simple commands that can be handled by simple algorithms and build a framework where more commands can be added to it. This may seem like a "dumb" approach, but it will be used before learning how to pattern match key text using AI and tools like TensorFlow. Once the command is handled, the text will be streamed back to the app, which will then vocalize the answer. (I plan on making a command like "hey jarreth, explain [topic]" which will send the topic to the ChatGPT3 API to give me an awesome answer) :)

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Home Server (old dell optiplex)   | n/a | Owned  |
| Ethernet Cable   | https://www.amazon.ca/AmazonBasics-Cat-5e-Network-Ethernet-Cable/dp/B001TH7GVO | $15.60  |
|  Samsung s6 Tablet| https://www.facebook.com/marketplace/item/606919971242436/?hoisted=false  | $220 |
| Total           |                                       | $235.60 |


