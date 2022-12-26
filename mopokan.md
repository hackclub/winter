---
name: "@mopokan"
project: "OpenKlino"
---

# OpenKlino

## Summary
  OpenKlino is a project about 3D Clinostat or another name Random Position Machine(RPM). This apparatus has been used in space science research to simulate long-term 
microgravity for Biology experiments ex. Changes in Plant Growth Processes under Microgravity Conditions Simulated by a Three-Dimensional Clinostat [(Hoson et al.1992)](https://link.springer.com/article/10.1007/BF02489403).This device is using gravity vector averaging principle to eliminate gravity and create a microgravity environment.The most interesting of this project is there is no Youtube or website tutorial that mentions how to build it in a frank way. The thing that I can rely on is 
research papers from the past. So this project is like challenging my potential and If this project is successful, I can use my own Random Position Machine(RPM) 
to conduct the future experiment without renting the expensive Random Position Machine(RPM) from the vendor website!


## Plan

1.I will design the whole RPM structure base on this quote "The RPM is operate by 2 rotating motor. Each one mount to the inner frame and outer frame so each frame can rotate independently and because of this it can eliminate gravity vector"(like shown in fig1.).When finish my design, I will run simulation in CAD program to see the result if everything is correct(the net gravity vector in the rotaing frame is nearly 0 ) I will continue to step 2


<p align="center">
  <img alt="3DClinostat" src="https://github.com/mopokan/winter/blob/main/Schematic-view-of-the-MicroG-Center-3-D-clinostat.png?raw=true" width="848" height="500">
</p>
   

2.In this step, I will design rotating path algorithm for my RPM base on [this paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4223831/) by using my computer.

3.The last step is Assemble and fine tune for the best accuracy.


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| 2 Dynamixel MX-12W motors        | https://inex.co.th/home/product/mx-12w/ | $184 |
| Dynamixel Shield for Arduino uno | http://www.smile-robotics.com/p/58      | $20  |
| 2 Slip rings                     | https://bit.ly/3WlXIfr                  | $18  | 
| Arduino uno                      | https://bit.ly/3hWnrw5                  | $6   |
| Acrylic sheet 5mm (60*90cm)      | https://bit.ly/3vfO1U1                  | $10  |
| Switching Power Supply 12V,3A    | https://bit.ly/3WlGNtN                  | $10  |
| Total           |                                       | $248 |

*Note the cost in the table is include shipping cost already

*All suppliers are in thailand.

*Know more about [clinostat](https://pure.uva.nl/ws/files/903914/79169_metis316931.pdf)
