---
Title: "Quarter Past Five"
Author: "Padimo"
Description: "Word Clock with minute level precision"
Created On: "8/12/2025"
---

# Day 1

Created the schematic based on the Xiao RP2040. Read MAX7219 datasheet to understand daisy chaining of multiple matrices.
Implemented daisy chaining for easier programming. 
Then I realized that I don't need a separate CS for everything and even those can be chained! modified as such. 

![img1](sch.jpg?raw=true)

*time spent: 3h*

# Day 2

Autorouting broke so I had to route by hand. Created mental layout first and then added other components afterwards. 

Then I came up with the idea to add a photoresistor for auto-brightness. Added to schematic and circuit board.

Rerouted the daisy chain for more straightforward wiring without crossing with vias. Bottom two matrices are upside down, so that will be updated in code. 

![img2](pcb.jpg?raw=true)

*time spent: 4h*
