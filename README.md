##Turing Mini Voltages Expander   

This is a simple, low-parts count, low-current expander for the Turing Machine Random Sequencer in 4HP. 

It acts like a variable 5-bit digital-to-analog converter, taking 5 bits from the Turing Machine GATES expansion port, running them through five potentiometers and giving one summed voltage output.   

Multiple mini expanders can be daisychained from one Turing sequencer to give melodically different outputs that are all related to (and change with) the main Turing sequence.   

Designed in one day while on holiday in Cornwall.   

NB: the panel design in this repository is a bit strange; raw fibreglass with gold lines and no text - you might want to tweak it if you want a panel that matches the other the Turing expanders. 

BOM: 
- 5 x Vertical 50k Linear Potentiometers ([Alpha 9mm](https://www.thonk.co.uk/shop/alpha-9mm-pots/) will work well)
- 8 x 10k Resistors 
- 1 x 1k Resistor 
- 1 x TL072 Op Amp 
- 2 x 100n Ceramic Capacitors 
- 1 x [Thonkiconn Socket](https://www.thonk.co.uk/shop/thonkiconn-3-5mm-jack-sockets-x50/)  
- 2 x 16 Pin Headers 2x8 (for example 649-67997-216HLF from Mouser)
- 1 x Ribbon cable
- 5 x Knobs

This board should be built with pots that bolt to the panel, like the Alphas above. Plastic shaft pots (or the little ones with an indicator line on the shaft) will work fine, but the only support between the board and the panel will be the nut on the socket. There is a mounting hole on the PCB, so you can screw an 11m hex spacer to that, and epoxy the other end to the panel, if you want to use those pots. 

Status:  
January 2016: Updated prototype built, working well. 
September 2015: First board validated idea, contained embarrassing errors. Those fixed, second prototypes ordered.  
August 2015: Awaiting first prototypes  


![First image mockups](https://raw.githubusercontent.com/TomWhitwell/Turing-Mini-Voltage-Expander/master/Collateral/panels.jpg)
