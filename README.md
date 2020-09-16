# IDD_Fa20_AltLab2

## Part A. Design your Arduino+

**a) What is the + improvement of your Arduino+**

For my Arduino+, I decided to add a second 2.5mm power jack to allow for a dedicated 12V power supply for LED components.

**b) What Arduino form-factor/design are you basing your design off of?**

The base board for this design is the Arduino UNO Rev3. 

**c) What features/parts need to be incorporated for your Arduino+? Include your research!**

I decided to use the PJ-102B 2.5mm barrel jack. This jack has a small form factor on the board itself, and handles up to 2.5A of current. The LED strip I plan to run from it pulls up to 2A of current, so the jack satisfies all design requirements. 

**d) What is the timeline for the overall development of your Arduino?**

After finishing this lab, I will submit the PCB order through OSH Park. I think OSH Park is the best option because they offer reasonably cheap prices while staying in range of domestic shipping. I've found that international shipping during the pandemic can be unreliable, so I'd rather avoid it. Shipping time is 15 days, after which I will solder the components to the board and attach all the peripheral systems. All told, system development should take under a month. 

**e) Which fabrication company are you using, what do you plan to order, and what is the design rationale for the selection?**

As stated above, I will be using OSH Park because I would like to avoid international shipping. My experience with international shipping during the pandemic was that it was slow and unreliable. 


## Part B. Order parts for your Arduino+
Develop a bill of materials for your Arduino +.

currently unsure of how to populate a BOM for the parts that are already on the UNO design. 


## Part C. Prototype your Arduino+

**Describe key design questions (how big are the parts? what pins need to be connected?) and how you used/will use prototyping to answer them.**

The primary device that will interface with the board is a large string of LED lights that is integrated into my prototyping desk. To prototype, I will test the capability of a stock Arduino UNO to run the proper PWM signals from its digital pins, and I will rig up a 12V wall adapter directly to the power pin of the LED strip. I am still researching the proper way to interface with the LEDs and how to set up the power circuit, but I will complete a prototype before sending the board to be manufactured. 

## Part D. Layout your Arduino+

My EAGLE files are stored in this repository. I managed to fit the new part into the space between the digital pins and the Arduino logo on the original board, though doing this required me to sacrifice the board's UART interface. Since I don't anticipate using UART for anything, I cut the traces from digital pins 0 and 1, and instead grounded them to make room for the barrel jack's 3 large through hole solder points. 

## Part E. Send your board off to be made

Still getting there on this, am meeting with Ilan tomorrow. 

## Part F. Pain Points



