# 4bitCounter
Up/Down counter circuit with SN74LS191 chip 

## Requirements
### Hardware
    - SN74LS191N 16 pin 
    - 5 Leds 
    - 5 Resistors (220 Ohm)
    - wires (F-M)
    - clock (e.g Arduino's clock)


## Documentation
### SN74LS191N
| Pin | Connected to ...|
|-----|---------------|
| VCC | 5v |
| A | GND |
| CLK | clock |
| RCO | LOAD (to itself)|
| MAX/MIN | LED +|
| LOAD | RCO (to itself) |
| C | GND |
| D | GND |
| B | GND|
| QB | LED |
| QA | LED |
| CTEN | GND |
| D/U | GND (Up) |
| QC | LED|
| QD | LED |
| GND | GND|

## Note
The connection explained in the documenation is for a up count from zero to fifthen. In case the oposite is desire the following connection need to be wired:
### SN74LS191N
| Pin | Connected to ...|
|-----|---------------|
| VCC | 5v |
| A | 5V |
| CLK | clock |
| RCO | LOAD (to itself)|
| MAX/MIN | LED +|
| LOAD | RCO (to itself) |
| C | 5V |
| D | 5V |
| B | 5V |
| QB | LED |
| QA | LED |
| CTEN | GND |
| D/U | 5V (Down) |
| QC | LED|
| QD | LED |
| GND | GND|
