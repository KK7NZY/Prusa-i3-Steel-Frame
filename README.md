P3Steel
---
RepRap P3Steel parts and build instructions.

http://reprap.org/wiki/P3Steel

### Bill of Materials

| Part                                                     |  QTY  |        Supplier        | 
|----------------------------------------------------------|:-----:|------------------------|
| Steel Frame                                              |   1   | Orballo Printing       | 
| Steel X-Carriage Kit                                     |   1   | eBay (131925664995)    |    
| Heated Bed Adjustment M3 Thumb Nut                       |   4   | eBay (221907839576)    | 
| NEMA 17 Stepper Motor                                    |   4   | LulzBot                |
| Half Height NEMA 17 Stepper Motor                        |   1   | LulzBot                |
| All-metal E3D v6 Hotend - 12 Volt / 1.75mm Universal     |   1   | Filastruder            |       
| LM8UU Linear Bearings                                    |   12  | Amazon                 |  
| 8mm x 320mm Precision Chromed Linear Shaft Rod           |   2   | eBay                   |
| 300mm x 8mm Lead 4 Start Lead Screw & Nut                |   2   | eBay                   |
| 5mm to 8mm Shaft Rigid Motor Wheel Coupling Coupler      |   2   | Amazon                 |
| 8mm x 406mm Precision Chromed Linear Shaft Rod           |   2   | eBay (182458794200)    |
| GT2 16T 6mm Width                                        |   2   | eBay (371601051088)    |
| MK3 Aluminum Hot Bed w/Hardware                          |   1   | RepRap Champion        |


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
