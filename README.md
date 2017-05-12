P3Steel
---
RepRap P3Steel parts and build instructions.

http://reprap.org/wiki/P3Steel

### Bill of Materials

#### Vitamins

| Part                                                                |  QTY  |
|---------------------------------------------------------------------|:-----:|
| Steel Frame V2.01                                                   |   1   | 
| Steel X-Carriage Kit                                                |   1   |

#### Proteins

| Part                                                                |  QTY  |
|---------------------------------------------------------------------|:-----:|

#### Electronics

| Part                                                                |  QTY  |
|---------------------------------------------------------------------|:-----:|
| Azteeg X5 mini v1.1                                                 |   1   |
| 12v/30a DC Universal Regulated Switching Power Supply 360w          |   1   |
| 9 ft. 14/3 Power Tool Replacement Cord                              |   1   |
| All-metal E3D v6 Hotend - 12 Volt / 1.75mm Universal                |   1   |
| MK3 Aluminum Hot Bed w/Hardware                                     |   1   |

#### Hardware

| Part                                                                |  QTY  |
|---------------------------------------------------------------------|:-----:|
| 8mm x 320mm Precision Chromed Linear Shaft Rod                      |   2   |
| 300mm x 8mm Lead 4 Start Lead Screw & Nut                           |   2   |
| 8mm x 406mm Precision Chromed Linear Shaft Rod                      |   2   |
| Heated Bed Adjustment M3 Thumb Nut                                  |   4   |
| MK8 Filament all-Metal Remote Bowden Extruder Parts                 |   1   |
| Aluminum Spacer (6 x 1/4" x 3/8")                                   |   3   |

#### Mechanical parts

| Part                                                                |  QTY  |
|---------------------------------------------------------------------|:-----:|
| LM8UU Linear Bearings                                               |  11   |
| 5mm to 8mm Shaft Rigid Motor Wheel Coupling Coupler                 |   2   |
| GT2 2mm pitch 6mm wide Timing Belt                                  |   -   |
| GT2 Pulley 16T 6mm Width                                            |   2   |
| 608 Ball Bearing                                                    |   2   |
| NEMA 17 Stepper Motor                                               |   4   |
| Half Height NEMA 17 Stepper Motor                                   |   1   |


#### Optional

| Part                                                                |  QTY  |
|---------------------------------------------------------------------|:-----:|
| Heated Bed Tempered Borosilicate Glass Plate (213mm x 200mm x 3mm)  |   1   |
| Dupont 2.54mm Connector Housing Female                              |   5   |
| Dupont Jumper Wire Cable Female Pin Connector 2.54mm                |  30   |
| Mellow-Yellow MDPC-X Sleeve (25ft)                                  |   1   |
| Mechanical Endstop Switch                                           |   3   |


### Temperature Control

http://smoothieware.org/temperaturecontrol?s[]=temperaturecontrol&s[]=pid&s[]=autotuning#pid-autotuning


**E3D-v6 Hotend**

https://wiki.e3d-online.com/wiki/E3D-v6_Assembly

```shell
M303 E0 S230 C10
// Cycle 4: max 236.676,min:225.84,avg seperation: 0.281876
   Ku: 59.9243,Pu 35.25
   Kp: 36.0
   Ki: 2.040
   Kd: 158
```

**Hotbed**

```shell
M303 E1 S50 C8
// Cycle 4: max: 50.6263, min: 49.3329, avg separation: 0.00749207
   Ku: 502.053, Pu: 52.1
   Trying:
   Kp: 301.2
   Ki: 11.564
   Kd:  1962
```
