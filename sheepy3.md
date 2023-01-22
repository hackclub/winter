---
name: ["@sheepy3", "@D3thclaw", "@jaaldecrga"]
project: "MPCNC, Macropads, and a budget PC"
---



Shawn (slackID:U04BBP8H9FA) Cleifton (SlackID:U04H1CUR81X), and Jaylan (SlackID:U04GRS3T9J8) have decided to split our collective $750 budget (250x3) among 3 projects. 
We will all collaborate on each one of them, both on designing and assembling.

The tools at our disposal are
* Side-cutter pliers
* Autodesk Fusion360/CADD Software
* 3D Printer
* Screws
* Soldering Iron
* Hot Glue
* Copper wire (upon purchase)
* Plastic Cement
* Miter saw, table saw
* hotwire cutter
* drills, screw drivers, etc.
* measuring tape, rulers, carpenters square
* brushes
* all the paints
* airbrush
* wirebrush
* A Blender(?)

---
## Project A) the MPCNC
The main project we will be working on is a Mostly Printed CNC, is a CNC router built from mostly printed parts. Costs will go towards filament 
and electrical components, as well as some hardware. 

### Plan
We will be following this guide: https://docs.v1engineering.com/mpcnc/intro/

After aquiring the parts, I will print the parts out while our group works in parallel
to construct a table from wood I already have. We'll then assemble the CNC on it, and connect the stepper motors to the mainboard, 
which I will design an enclosure for. Outside of cutting tubing, screwing components together, and wiring the stepper motors to the mainboard, the construction process 
isn't much more complex than that. The most difficult aspect may simply be getting our measurements as accurate as possible. 

We're excited to build a CNC machine as we just love building things, especially functional tools. It will be a really useful tool in cutting RC aircraft parts from foam,
or wood pieces for shawnn's model houses or dioramas. We may end up using wooden components milled on the MPCNC machine in our PLTW engineering class, 
for our final products in Engineering Design Development. 

The CNC will live in shawns garage, and as we all live near each other, any of us can use it for future projects.

---
## Project B) the Macropads
Our second project is to create custom macropads for Shawn and Jaylan. As artists, hotkeys are crucial in saving time. we want to have physical devices for use in
artistic programs like Blender, CLIP STUDIO Paint, Krita, etc. where custom keybinds are almost always necessary. The Macropad would help in the ease
of access for mapping and accessing custom keybinds.We want to create custom macropads to fit our respective needs. Shawn's macropad will host 12 mechanical switches, 
a 5 way switch, and two rotary encoders. Jaylan's will also host 12 switches, an OLED display, and RGB (because of course). 
Shawn's will be Pico based and Jaylan's will be Arduino pro micro based. As our pads will be different, we'll get to experiment with different components
and how to program them to fit our needs.

### Plan

We will be following this guide: https://www.instructables.com/Custom-Macro-Mechanical-Keypad/
Firstly, we'll be going to design the prototype for our device on paper, then we'll proceed to recreate it digitally using CADD in order to have a design that
can be printed out. Then, we'll cut up the RGB LED strips and glue them underneath the bottom of the 3D-printed plate to give the device a backlight. We'll then
slot keyboard switches into the holes of the plate. Secondly, I'll connect the Pro Micro to the I2C OLED using a breadboard and inject code into the Pro
Micro so that it can control the OLED. We will then wire and solder the LED units together, then finally wire the LEDs to the Pro Micro. We will then use the guide
linked above as an aid to help us create code that allows for the easy mapping of keybinds and assigning them to a button on the Macropad, as well as programming the
LEDs, the keyboard switches themselves, and the I2C OLED display. Lastly, we'll assemble the final product into the chassis, inserting the Pro Micro inside the chassis
and securing it with glue, slotting the I2C OLED display into its proper place, screwing everything shut (using plastic cement to close seams if necessary), then finally
putting the keycaps on top of the keyboard switches.

As for Shawns Macropad, His will follow a very similar procedure, save for no RGB and containing Rotary encoders and a 5 way switch instead of a Display.
Additionally,a pico will be used in place of a pro micro.


---
## Project B) the PC

The final project we will be working on is a Low Budget - High performance PC for Cleifton. We have entered this event because we want to further our skills 
with computer hardware and software. However, Only jaylan and shawn has PC's for use in CADD or programming. While Cleifton could use something like Replit, he's still very limited by his old chromebook.  
Only shawn has PC buiding experience, and so Project C will help introduce the fun of PC building to Jaylan and Cleifton. 

### Plan
Unlike the other two, this project is designed entirely by ourselves. after scouring for the best deals, Shawn and Jaylan put together a component list. Next, 
Shawn will design a custom case on a budget, and print the components. We will then all meet to assemble the custom case and PC, and get either windows 10 or linux(Mint XFCE) up and running.

If a detailed rundown of pc building is necessary:
1) we will insert the processor into the motherboard, and clean the IHS surface. We will apply thermal paste, and install the CPU cooler (which we will have cleaned). 
Next, we'll plug in the 1x8 stick of ram, and mount the motherboard in our custom case. We'll then install and wire up the power supply.
The graphics card will then be installed and plugged in. An IO cutout and GPU cutout will be made. We will also installa wifi PCIE card and power button.
Finally, a fan will be mounted and plugged in. We'll then boot the pc and check for errors. 


---
## Budgeting
We compiled our information in a spreadsheet, which be found here: https://docs.google.com/spreadsheets/d/1EwkFUslRxFg4BUSeKEYayMCVuiP4EmGo8mbpw0vN8Oo/edit?usp=sharing
If there are any errors in the budget list below, it may be a result of misformatting.

The budget below will be split for clarity.

Project A Budget
|  Product                                       | Supplier/Link                                                                      		| Cost	    |
|  --------------------------------------------- | -------------------------------------------------------------------------------------------- | --------- |
| Polymaker PolyLite PLA PRO                     |https://www.amazon.com/Polymaker-Filament-1-75mm-Rigidity-Cardboard/dp/B09J186Z13   		|  $49.98   |
| Stepper motors			         |https://www.amazon.com/Stepper-Motor-Bipolar-4-lead-Printer/dp/B00QEYADRQ			|  $55.00   |
| 16 Teeth 2GT Timing Pulley                     |https://www.aliexpress.us/item/3256802495067578.html						|  $8.65    |
| 20T W10 B5 without T Timing Pully              |https://www.aliexpress.us/item/2251832608763422.html						|  $8.24    |
| POWGE 2MGT 2M 2GT Open Synchronous Timing belt |https://www.aliexpress.us/item/2251800716378037.html						|  $9.99    |
| 12V 6A 72W Kastar AC Adapater                  |https://www.amazon.com/Kastar-Adapter-5-52-5mm-Wireless-Security/dp/B003TUMDWG	  	|  $13.99   |
| 608 Ball Bearings				 |https://www.aliexpress.us/item/3256803779818763.html						|  $21.28   |
| T8 Lead Screw					 |https://www.aliexpress.us/item/2251832509292162.html						|  $4.32    |
| Coupler					 |https://www.aliexpress.us/item/3256803558253052.html						|  $7.06    |
| Super Lube 					 |https://www.amazon.com/Super-Lube-21030-Synthetic-Grease/dp/B000XBH9HI/			|  $8.99    |
| RAMPS 1.4 Controller				 |https://www.amazon.com/OSOYOO-Printer-Controller-Stepper-Heatsink/dp/B0111ZSS2O	  	|  $45.99   |
| Dewalt 660					 |https://www.amazon.com/DEWALT-DW660-Cut-Out-Rotary-Collets/dp/B000051WQX			|  $65.99   |
| Cable ties					 |https://www.aliexpress.us/item/3256804679472449.html						|  $0.99    |
| Dupont Connectors				 |https://www.aliexpress.us/item/3256803472719944.html						|  $9.39    |
| M2.5x12mm Screws 				 |https://www.amazon.com/uxcell-M2-5x12mm-Phillips-Stainless-Fasteners/dp/B07MF41CZS/ 		|  $7.99    |
| M5 metric locknut				 |https://www.amazon.com/Milliontronic-Nylon-Insert-Locknut-Metric/dp/B09582Q721	        |  $8.80    |
| M5 x 30mm Screws 				 |https://www.amazon.com/Phillips-Suitable-Replacement-Mechanical-Equipment/dp/B08F7DZMNS/	|  $19.98   |
| Cooling Fan					 |https://www.aliexpress.us/item/2251832675392477.html						|  $4.27    |


Project B Budget
| Product                           | Supplier/Link                                                                                    | Cost   |
| --------------------------------- | ------------------------------------------------------------------------------------------------ | ------ |
| Kailh Blue Switches (set of 10)   | https://www.aliexpress.com/item/4000907409650.html                                               | $11.49 |
| 3.2ft WS2812B RGB strip light     | https://www.amazon.com/ALITOVE-Individual-Addressable-Programmable-Non-Waterproof/dp/B01MG49QKD/ | $7.99  |
| Pro Micro USB-C                   | https://www.aliexpress.us/item/2251832581993895.html                                             | $6.68  |
| 128x32 I2C OLED Display (set of 4)| https://www.amazon.com/dp/B08LQM9PQQ/                                                            | $13.29 |
| Solder Sucker                     | https://www.aliexpress.us/item/2251832678314085.html                                             | $3.07  |
| Rotary Encoder (quant. 2)         | https://www.aliexpress.us/item/2251832728829977.html                                             | $6.70  |
| Kailh Blueberry                   | https://www.aliexpress.us/item/3256801264771224.html                                             | $7.67  |
| 5-way Switch                      | https://www.aliexpress.us/item/3256804170760833.html                                             | $3.15  |
| Pi Pico (quant. 2)                | https://www.aliexpress.us/item/3256804360324658.html                                             | $10.98 |
| Solder Wool                       | https://www.aliexpress.us/item/3256803501471341.html                                             | $1.94  |
| Kailh Pink box                    | https://www.aliexpress.us/item/2255800583879201.html                                             | $7.27  |
| 20m Copper wire                   | https://www.aliexpress.us/item/3256804149903490.html                                             | $8.20  |


Project C Budget
| Product                     | Supplier/Link                                                                             | Cost   |
| --------------------------- | ----------------------------------------------------------------------------------------- | ------ |
|TP-Link AC1200 PCIe Wireless Wifi PCIe Card (Archer T4E) (Refurbished)		    |https://www.ebay.com/itm/143823963379    						        |$18.99  |
|ARCTIC MX-4 thermal paste | 							    |https://www.amazon.com/ARCTIC-MX-4-Compound-Micro-particles-Durability/dp/B0795DP124/      |$5.45   |
|SP 512GB 3D NAND A55 SLC Cache 7mm Internal Solid State Drive	 		    |https://www.amazon.com/Silicon-Power-Performance-Internal-SP512GBSS3A55S25/dp/B07997QV4Z/  |$25.99  |
|Enermax Cyberbron 500W Power Supply, 80 PLUS Bronze | 				    |https://www.amazon.com/Enermax-Cyberbron-ECB500AWT-Non-Modular-Warranty/dp/B08K1ZBYPZ/     |$34.99  |
|1M Chassis Dust Cover Computer Mesh 30CM 					    |https://aliexpress.us/item/3256803817263252.html					        |$4.27   |
|PC Host Start Power SW Button Switch 						    |https://www.ebay.com/itm/185682929981						        |$3.66   |
|2PCS SATA 3.0 6Gb / s SSD Hard Drive Data Cable				    |https://www.ebay.com/itm/314009883673						        |$1.00   |
|Asus Q170M-C Motherboard i5-7400 @ 3.0Ghz 8GB Ram DDR4 LGA1151 +IO Shield DP125    |https://ebay.com/itm/266040999410							        |$105.65 |
|uphere 3-Pack PWM 4PIN Long Life Computer Case Fan 120mm 			    |https://www.amazon.com/uphere-3-Pack-Computer-Cooling-12BK4-3/dp/B098PZ19KX	        |$15.99  |
---										   ---											       ---	---																					   
we will only buy 1 gpu, superfluous links are redundancies in case a listing ends.  
| Product                     | Supplier/Link                                                                             | Cost   |
| --------------------------- | ----------------------------------------------------------------------------------------- | ------ |
| MSI Radeon RX 580 8GB GDDR5 Graphics Card (RX580ARMOR8GOC) 		 |https://www.ebay.com/itm/125649176167							|$96.00  |
NVINDA Radeon RX 580 8GB							    |https://www.ebay.com/itm/195514955615							|$89.77  |
MSI Gaming X AMD Radeon RX 580 8GB						    |https://www.ebay.com/itm/125649203974							|$106.00 |
---	
1/8/23 Our motherboard combo listing has ended, and so we found a few more options. we will only buy one.				

| Product                     | Supplier/Link                                                                             | Cost   |
| --------------------------- | ----------------------------------------------------------------------------------------- | ------ |
Asus Q170M-C Motherboard i5-6400 @ 2.70Ghz 8GB Ram				    |https://www.ebay.com/itm/266039531773							|107.99	 |
Asus H110M-C Motherboard i3-7100 @ 3.90GHz 8GB RAM				    |https://www.ebay.com/itm/266063317737							|79.00	 |

### TOTAL : ~755.99

with a budget of 750 (250*3), we intend to pay for other out of pocket purchases as well as the overflow in the grand total shown above, as well as any other costs we did not initially account for.

---
1/8/23

I (shawn) plan to start printing parts for the CNC machine as soon as the filament arrives following approval. This is because of the sheer amount of parts needed, as I'm not sure ill be able to finish printing everything in time for feburary. I'll also be printing components for the macropads and PC case out of a significantly less rigid filament that I own as soon as we have designed all of the parts. we'll save assembly for february. 

---

Here is the list of components we intend to buy locally. I have already purchased the dowel rods. 

PC Case:

| Product                   | Cost   |
| ------------------------- | ------ |
| 1 in. x 4 in. x 8 ft. Wood 				| $2.98 |
| 7/8 dowel						| $5.32 |

CNC Machine:
| Product                                               | Cost   |
| ----------------------------------------------------- | ------ |
| 3/4 in. x 5 ft. Electrical Metallic Tubing (EMT)- Steel | $27.92 |
| Everbilt 5/16 x 1 1/2					| $16.93 |
| M3-0.5x10mm						| $5.20  |


### Conclusion

As engineering students, we feel we could learn a lot from each project, as they each tackle different topics (large scale machine design, digital electronics, and improved understanding of computers). They each have application in our lives outside of being learning experiences. Me and Jaylan will use our macropads for art and CAD, and Cleifton does not have a computer for programming and CAD design. The CNC will be freely usable by any of us in any of our projects, to mill wood, foam, or PCBS. 

We would also like to thank hack club for giving others like us the opportunity to learn and further oour computer sciences knowledge. I hope to be able to demonstrate my love of computers and technology to others in this community. 


					
