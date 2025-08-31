# Quarter Past Five

This is a small 16x16 word clock that can tell the time with a minute resolution. It uses a Xiao RP2040 with four daisy-chained MAX7219 as the display with four key switches to set the time. Breakout pins for connecting a DS3231 RTC are included as well. Has a photoresistor for automatic light adjustment.

### Why?

Because reading the time in words gives me a sense of urgency that reading numbers does not. It makes me get things done more effectively. 

### Building instructions

Obtain parts labeled in the BOM. See either the table below. 

| Component     | Identifier     | Price    | Amazon link |
|---------------|----------------|----------|-------------|
| Xiao RP2040   | XIAO-RP2040    | $9.99    | [Amazon](https://www.amazon.com/Microcontroller-Dual-Core-MicroPython-CircuitPython-Interfaces/dp/B09NNVNW7M/)|
| DS3231        | RTC            | $12.99   | [Amazon](https://www.amazon.com/HiLetgo-AT24C32-Arduino-Without-Battery/dp/B00LX3V7F0/)|
| Switches      | switches       | $10.99*4 | [Amazon](https://www.amazon.com/Mciepny-Waterproof-Dustproof-Pre-Lubricated-Mechanical/dp/B0FF9MBBDR?th=1)|
| MAX7219       | led-matrix     | $8.28    | [Amazon](https://www.amazon.com/3PCS-MAX7219-Matrix-Display-Module/dp/B0FB99TY1Z/)|
| Photoresistor | photoresistor  | $7.39    | [Amazon](https://www.amazon.com/HiLetgo-Dependent-Photoresistor-Photoconductive-Resistance/dp/B00N1ZJUN4/)|
| CR2032        | N/A(separate)  | $3.97    | [Amazon](https://www.amazon.com/Amazon-Basics-CR2032-Compatible-Mercury-Free/dp/B0787K2XWZ/)|

Solder each component into the PCB accordingly, or follow the schematic to wire the pieces together. If using the PCB, make sure that things go the right direction. When soldering the MAX7219, solder the board with the LEDs first and then solder that to the PCB, not the other way around. It's a lot easier.

### Images

![sch](https://github.com/Omegon0/wordclock/blob/main/sch.jpg?raw=true)
![pcb](https://github.com/Omegon0/wordclock/blob/main/pcb.jpg?raw=true)
![r1](https://github.com/Omegon0/wordclock/blob/main/r1.jpg?raw=true)
![r2](https://github.com/Omegon0/wordclock/blob/main/r2.jpg?raw=true)
