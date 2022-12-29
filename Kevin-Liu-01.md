---
name: "@Kevin-Liu-01"
project: "ResinReach"
---

# Project Name
ResinReach - Expand your Reach

## Summary

For this project, I am going to build "ResinReach," a prosthetic hand that will be made using resin and an Arduino Nano. 
The hand will be designed to mimic the movement and function of a human hand as closely as possible, using a combination of muscle sensors and servo motors.

The prosthetic hand will be able to perform a wide range of tasks, such as grasping and holding objects, typing on a keyboard, 
and performing other fine motor skills. It will be controlled using a combination of Myoware sensors on the skin that detect muscle stimulation and 
an Arduino microcontroller that processes the signals and controls servo motors to pull the fingers. I have several motors at home I can use for this project, 
as well as the Arduino Nano.

I am excited to build this project because I believe it has the potential to make a real difference in the lives of people who have lost the use of 
their hand due to injury or disability. By creating a device that can replicate the functions of a human hand, it can help people regain their 
independence and improve their quality of life. I am also excited to explore the technical challenges of building a device like this, and to learn 
more about the possibilities of using resin and Arduino for prosthetics. Additionally, if this works, it would be a proof of concept for an ultra-cheap 
prosthetic made of resin that would not only be more comfortable but more accessible as well.

I am specifically using resin instead of traditional 3d printer filament. There are several reasons why using resin instead of plastic is better for tools such as a prosthetic hand:

1. Resin is generally stronger and more durable than plastic: Resin is known for its high strength-to-weight ratio, which means it can be used to create lightweight yet sturdy structures. This can be particularly useful in a project like a prosthetic hand, where the parts need to be strong enough to withstand the forces of everyday use, but also lightweight enough to be comfortable for the user to wear.

2. Resin can be more flexible and resistant to breaking: Some types of resin, such as urethane resin, are known for their flexibility and ability to withstand impact. This can make them more resistant to breaking or cracking under stress, which can be an advantage in a project like a prosthetic hand, where the parts will be subjected to a wide range of forces and movements.

3. Resin can be used to create intricate and detailed parts: Many types of resin are known for their ability to create intricate and detailed parts, thanks to their smooth, glossy finish and ability to hold fine details. This can be useful in a project like a prosthetic hand, where the parts need to be as realistic and lifelike as possible.

4. Resin is more comfortable - plastic often leaves sharp, gnarled edges while resin forms smooth, even shapes that are better for complex contours like those of the hand. This is better for the end user.

## Plan

1. Design: Design the hand in Fusion 360 to create a detailed 3D model of the prosthetic hand, including all the parts and components. I will use
scientific literature to ensure my design is sound. As such, I will consider the size and shape of the hand, as well as the types of movements and tasks it will need to be able to perform.

2. 3D print the parts: Use a 3D printer to print all the parts for the prosthetic hand, including the fingers, palm, wrist, and any other components. The hand will
not necessarily wrap all around the hand like a glove - it will simply rest on top of it firmly, making adjustments as needed. Appropriate settings and procedures will be used to achieve the desired results.

3. Solder the circuits: I have soldered in school, so I only need the tools necessary to do this project at home. I will attach a breadboard onto the hand and then solder electronic 
components to create the circuits that will power the prosthetic hand. This will entail soldering sensors, motors, and other components to the breadboard.

4. Assemble the hand: I will use the 3D printed parts and the assembled circuits to build the prosthetic hand. I will attach the motors and sensors to the hand, 
and connect all circuits to my Arduino Nano.

5. Testing: Once the hand is assembled, I will test it to make sure all the parts are working correctly and that the hand is able to perform the desired tasks. 
This may involve adjusting the sensors and motors or writing some dummy code for the Arduino.

6. Write the code: I will write some C++ loops for the Arduino that will control the prosthetic hand. The code will interpret signals from the sensors and use 
that information to control the motors and make the hand move.

7. Fine-tune and refine: As I test and use the prosthetic hand, I will most likely need to make adjustments and refinements to the design and code to make it more 
effective and reliable. I am prepared to iterate and improve the hand as I go.

Originally, I considered outsourcing the resin printing to a 3rd party company, but as I began brainstorming I realized that this would be too inefficient for my project.
I would have little to no control over the printing process and would not be able to make changes and adjustments as needed. This is particularly unfortunate for 
prototyping and testing multiple designs or making quick changes on the fly. I can only begin designing and testing a new iteration when the company is ready,
forcing me to wait for the new design to arrive any time I make any design change, which is contrary to rapid prototyping and would most likely go over the 10 days
I would have for this project. On top of that, I would have to pay for the shipping, (potentially) the resin, and a whole bunch of other costs, like service fees, 
and I would not be able to present these costs upfront (a stipulation for a grant).

As such, because it was in my  combined budget, I decided to buy a 3D printer and resin instead. It may take some time out of the 10 days to assemble, 
but it will save me a lot of time in the prototyping and testing cycle. It will ultimately save me an extremely valuable amount of time in the development process 
and allow me to quickly prototype and test different hand designs. 

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Pack of wires   | https://www.adafruit.com/product/1957 | $1.95  |
|Soldering Iron Kit|https://www.amazon.com/Soldering-Kit-Temperature-Desoldering-Electronics/dp/B07GTGGLXN/ref=sr_1_6?crid=28QD0NK9LQJCB&keywords=soldering+iron&qid=1672283598&s=industrial&sprefix=soldering+iron%2Cindustrial%2C92&sr=1-6| $18.99|
|Myoware Muscle Sensors	|https://www.amazon.com/gp/product/B01GU6QMLI/ref=ox_sc_act_title_1?smid=A1ZW8W51C7XKQ5&psc=1|$24.99|
|3d printer|https://www.amazon.com/Creality-Photocuring-Filtering-Off-line-Printing/dp/B082XDH8NB/ref=sr_1_1_sspa?crid=PY7GGJQ6IWZ5&keywords=3d%2Bprinter&qid=1672283154&sprefix=3d%2Bprinte%2Caps%2C98&sr=8-1-spons&ufe=app_do%3Aamzn1.fos.18ed3cb5-28d5-4975-8bc7-93deae8f9840&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExVFpDQVROQkozSTlWJmVuY3J5cHRlZElkPUEwNDI1MDU4Mk4zTFZIT0pNSkVSMCZlbmNyeXB0ZWRBZElkPUEwMzczNzU0MzNQOEJPOUxNWU0ySiZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU&th=1|$179.00|
|Resin|https://www.amazon.com/ANYCUBIC-UV-Curing-Precision-Excellent-Fluidity/dp/B07G3663HD/ref=pd_day0fbt_sccl_1/144-1393969-1265224?pd_rd_w=lTkoV&content-id=amzn1.sym.c2062204-a945-491b-941c-359f18d6fec5&pf_rd_p=c2062204-a945-491b-941c-359f18d6fec5&pf_rd_r=R6HZ8TKZ5AM715HAY5S7&pd_rd_wg=T76GC&pd_rd_r=a3793903-8bd6-48f8-ae06-d1269ff3a1f8&pd_rd_i=B07G3663HD&th=1|$24.99|
| Total           |                                       | $249.92 |
