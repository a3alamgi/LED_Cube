LED Cube
========	
	
For my first project to get into electronics I made a 4x4x4 LED cube with 64 LEDs controlled with 12 pins via multiple stages of multiplexing from an existing design. Basic design from here: https://www.youtube.com/watch?v=lZyc6ulpkyM 

<img src="https://raw.githubusercontent.com/a3alamgi/LED_Cube/master/images/ledcube.jpg"/>   
  

Materials:
----------
-	x12, NPN transistors [2N3904TF](http://www.fairchildsemi.com/ds/MM/MMBT3904.pdf) 
-	x64, 3mm green LEDs [WP710A10SGC](http://www.kingbrightusa.com/images/catalog/SPEC/WP710A10SGC.pdf)
-	x4, 120Ω resistors
-	x20, 1kΩ resistors
-	x1, 6”x6” Perforated prototype board
-	Soldering assembly (solder, iron, braid, etc.)

Design & Assembly:
------------------
-	Multiplexed 64 LEDs in an array to reduce the number of pins required for control (Read more about multiplexing: http://en.wikipedia.org/wiki/Multiplexed_display)
-	Array controlled with 16 anodes and 4 cathodes with a NPN transistor (see Figure 1)
-	Anodes multiplexed further in a 4x4 array to reduce pins required for anode control from 16 to 8 (see Figure 2)
-	Assembled and soldered basic shape of LEDs into 4 sets of 4x4 layers
-	Soldered layers together and into a prototype board 
-	Attached and soldered transistors and resistors to the cube with connecting wires  
-	Control basic image with a control array
-	Light an LED one at a time and use persistence of vision to show multiple LEDs on at once  
 

<img src="https://raw.githubusercontent.com/a3alamgi/LED_Cube/master/images/cube_leds.jpg"/>   
Figure 1: 16x4 LEDs

<img src="https://raw.githubusercontent.com/a3alamgi/LED_Cube/master/images/cube_anodes.jpg"/>   
Figure 2: 4x4 Anode Multiplexing