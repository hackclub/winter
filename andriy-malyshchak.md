---
name: "@Andriy-Malyshchak"
project: "Autonomous RC Car dev platform"
---

# Project Name
Self-Driving Car
## Summary
I'm trying to learn more about AI/ML and its implications towards self-driving tech. Obviously it's very difficult to break 
into the field with real cars, so I'm trying to mirror that using RC cars. I'm excited to build this because it's a project that can dynamically expand
as I progress through the years. The tech platform can keep getting better and build on past iterations.


## Plan
http://docs.donkeycar.com/

First: Build the physical structure. I'll be using an RC car, which I'll take apart and include either Lidar, or a camera sensor. I'm planning on using
a Nvidia Jetson Nano as the main brain with a PCA9685 servo controller. Basically, I'm trying to find a car that will easily integrate with
the other sensors. I'll 3D print a shell for the camera and other sensors.

Second: Start base programming. Before the car runs I need to include the base "brains" for the car to start learning how to autonomously drive.
I'll achieve this by using an open source Donkeycar software available on the web. This will guide me into the final step.

Third: The final step is where I'll be able to implement my own designs/changes into the software of the car. I'll learn about autonomous
driving, and how to use ROS(Robotic Operating System), as well as systems like Tensorflow. This is also the most fluid step in the process because I'll do
a lot of iterating.

Problems: Some problems that I may encounter is weird software imcompatabilities, and potential hardware malfunctions. I'll tackle those problems by going 
on Donkeycar's support page as well as going through YouTube videos of past projects...

Additional info: The RC car that I chose is one of the models that the website lists as compatible with the hardware. As I move through different iterations, I'll probably run into more alternatives(these are just tested). The antennas and Wifi card are used for communicating to the ground station. Wifi card enables connection, while antennas boost that connection. The car is connected to a laptop while coding and operates on its own via the different sensors on the car. The camera feeds the image into the Nvidia Jetson Nano => into PCA servo controller => motor/steering. Initial success will be if the car is able to follow a demarked loop that I'll probably draw with chalk on the ground(or something similar).

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Nvidia JetsonNano   | https://www.amazon.com/NVIDIA-Jetson-Nano-Developer-945-13450-0000-100/dp/B084DSDDLT/ref=sr_1_3?crid=8AG2PWH8H3MR&keywords=nvidia+jetson+nano&qid=1671664292&s=electronics&sprefix=nvidia+jetson+nano%2Celectronics%2C103&sr=1-3  | $157  |
| Wifi Card | https://www.amazon.com/Edimax-EW-7811Un-V2-Compatible-2-6-18-4-14/dp/B08F2ZNC6J/ref=sr_1_1?crid=6NNV79DQX5LM&keywords=Edimax+EW-7811Un&qid=1671743931&sprefix=edimax+ew-7811un%2Caps%2C85&sr=8-1
  | $9 |
Camera | https://www.amazon.com/NVIDIA-Jetson-Development-Camera-Application/dp/B0854CP54X/ref=sr_1_3?crid=GF1ETUWHGVMK&keywords=nvidia+jetson+camera&qid=1671674825&refinements=p_36%3A-2000&rnid=386442011&sprefix=nvidia+jetson+camer%2Caps%2C105&sr=8-3
  | $10 |
Servo Driver | https://www.amazon.com/Dorhea-PCA9685-Interface-Controller-Raspberry/dp/B07RMTN4NZ/ref=sr_1_2?crid=R34O5ZSS82I7&keywords=PCA9685%2BServo%2Bcontroller&qid=1671743646&sprefix=pca9685%2Bservo%2Bcontroller%2Caps%2C161&sr=8-2&th=1
 | $9 |
Antennas | https://store.donkeycar.com/products/2x-molex-wifi-antennas-for-jetson-nano
  | $7 |
RC Car |  https://www.exhobby.com/products/short-course-30mph-high-speed-truck-with-shock-absorber-system-and-water-splash-proof-structure?currency=USD&variant=38102061449406&utm_medium=cpc&utm_source=google&utm_campaign=Google%20Shopping&cmp_id=17850712706&adg_id=&kwd=&device=c&gclid=Cj0KCQiA-oqdBhDfARIsAO0TrGGEqSlXQYCNL5MrJeAoJuaj3pc3D4PDEGlsEubY63Dtxrm9pJqY3zMaAmfHEALw_wcB | $60 |
Wires | https://www.amazon.com/Antrader-Breadboard-Dupont-Arduino-Raspberry/dp/B07S2RH6Q4/ref=sr_1_12?crid=7QJI5I1NGUGM&keywords=single+pin+wires+robotics&qid=1671749510&sprefix=single+pin+wires+robotic%2Caps%2C100&sr=8-12
 | 5.49$
| Total           |     257.49$               |  |
