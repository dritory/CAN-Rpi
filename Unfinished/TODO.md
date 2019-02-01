# CAN-Rpi

## TODO:

* Open  project

* make new schematic

* add header from misc library

* add MCP2515

* add net label to connect spi bus and power to the chip
  * press Ctrl+w to begin wire mode
  * press right click or ESC to return
  

* add bypass capacitors

* add crystal from altium vault

* add capacitors for crystal oscillator

* make new schematic

* add ports for tx, rx and 3.3V

* go to main schematic, place sheet symbol and synchronise

* find datasheet for can tranceiver, add symbol with symbol wizard

* add pcb footprint with wizard according to datasheet

* add can tranceiver to sheet

* add other components and connect to ports

* add header

* go to main schematic

* annotiate schematic

* pretty much finished with schematic

* Import changes to PCB

* Open pcb 

* Make yourself comfortable, move around

* Edit rules

  * Set minimum width to 0.2, normal 0.4, max 0.8 something. The important one is minimum!
  
  * Set minimum clearance to 0.2 (may be as low as 0.1) 

* Edit from mills to mm

* Configure grid to 0.25mm

* Start layout by moving components in ish the right position, play around with the orientation (space to rotate)

  * Start with the biggest components, aka the IC's and headers.
  * Bypass capacitors should be places as close to the IC as possible
  * Remember big enough traces for power
  * Don't bother with GND yet

* When you are certain with the placement of a component you can start tracing a little bit
  * Don't invest lots of work here, you will probably need to redo it
  * Different types of tracing modes and styles
  * Press 3 to change width
  * Press shift+space to change style
  * Press shift+r to change tracing mode
  * Press shift+s to see different layer modes

* Tip on traces
  * Make it beautiful - then the magic circuit elves will thrive and make stuff work
  * Try to mimic those cool motherboard circuit pcb like a true professional
  * Think two steps ahead: What is connecting where and how to get there
  * When tracing you can reroute a trace at any time to make it better
  * Practice makes perfect!
 
* Press 3 to look at the masterpiece and gain motivation!
  * Press 2 to get back to reality
  
* Place a polygon pour on the pcb with GND as the net
  * press "t g a" to repour
  * press "t g h" to shelf
  * press "t g e" to reenable
  * all Altium commands are available in keyboard hotkeys

* Probably should at one point edit the clearance for polygon pours to avoid short circuit when soldering

* Add texts to all the pins on the header and assign them to top layer
  * remember to repour "t g a"
  
* Press 1 to go to board definition

* Redefine the board shape to something more reasonable

* Press 3 again to marvel at your creation!

* Export BOM


