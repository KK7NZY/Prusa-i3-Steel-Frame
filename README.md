P3Steel
---
RepRap P3Steel parts and build instructions.

http://reprap.org/wiki/P3Steel

### Bill of Materials

| Part                                                                |  QTY  | Supplier               | 
|---------------------------------------------------------------------|:-----:|------------------------|
| Azteeg X5 mini v1.1                                                 |   1   | Panucatt               |
| NEMA 17 Stepper Motor                                               |   4   | LulzBot                |
| Half Height NEMA 17 Stepper Motor                                   |   1   | LulzBot                |
| All-metal E3D v6 Hotend - 12 Volt / 1.75mm Universal                |   1   | Filastruder            |
| MK8 Filament all-Metal Remote Bowden Extruder Parts                 |   1   | eBay (272606962516)    |
| LM8UU Linear Bearings                                               |  11   | Amazon                 | 
| 8mm x 320mm Precision Chromed Linear Shaft Rod                      |   2   | eBay                   |
| 300mm x 8mm Lead 4 Start Lead Screw & Nut                           |   2   | eBay                   |
| 5mm to 8mm Shaft Rigid Motor Wheel Coupling Coupler                 |   2   | Amazon                 |
| 8mm x 406mm Precision Chromed Linear Shaft Rod                      |   2   | eBay (182458794200)    |
| GT2 Pulley 16T 6mm Width                                            |   2   | eBay (371601051088)    |
| MK3 Aluminum Hot Bed w/Hardware                                     |   1   | RepRap Champion        |
| Heated Bed Adjustment M3 Thumb Nut                                  |   4   | eBay (221907839576)    |
| Heated Bed Tempered Borosilicate Glass Plate (213mm x 200mm x 3mm)  |   1   | Amazon                 |
| 12v/30a DC Universal Regulated Switching Power Supply 360w          |   1   | Amazon                 |
| 9 ft. 14/3 Power Tool Replacement Cord                              |   1   | HomeDepot              |
| Dupont 2.54mm Connector Housing Female                              |   5   | Amazon                 |
| Dupont Jumper Wire Cable Female Pin Connector 2.54mm                |  30   | Mod-One                |
| Mellow-Yellow MDPC-X Sleeve (25ft)                                  |   1   | Mod-One                |
| Mechanical Endstop Switch                                           |   3   | Amazon                 |
| Aluminum Spacer (6 x 1/4" x 3/8")                                   |   3   | HomeDepot              |


**Autopid**

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
