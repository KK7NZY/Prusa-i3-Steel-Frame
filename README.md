P3Steel
---
RepRap P3Steel parts and build instructions.

### Bill of Materials

**Vitamins**

- (1) [Steel Frame V2.01](http://orballoprinting.com/en/frame/8-prusa-i3-steel-frame-p3steel.html)
- (1) Steel X-Carriage Kit

**Proteins**

- (2) psu-clamp-top.stl
- (2) psu-clip.stl
- (1) psu-clamp-bottom.stl
- (2) endstop-holder.stl
- (1) feet-dampner-set.stl
- (1) y-belt-holder.stl
- (1) y-endstop.stl
- (1) ir-sensor-mount.stl

**Electronics**

- (1) [Azteeg X5 mini v1.1](https://www.panucatt.com/azteeg_X5_mini_reprap_3d_printer_controller_p/ax5mini.htm)
- (1) 12v/30a DC Universal Regulated Switching Power Supply 360w
- (1) 9 ft. 14/3 Power Tool Replacement Cord
- (1) [All-metal E3D v6 Hotend - 12 Volt / 1.75mm Universal](https://www.filastruder.com/products/all-metal-e3d-v6-hotend)
- (1) MK3 Aluminum Hot Bed w/Hardware
- (1) [Mini Differential IR Height Sensor](https://www.filastruder.com/collections/electronics/products/mini-differential-ir-height-sensor)

**Hardware**

- (2) 8mm x 320mm Precision Chromed Linear Shaft Rod
- (2) 300mm x 8mm Lead 4 Start Lead Screw & Nut
- (2) 8mm x 406mm Precision Chromed Linear Shaft Rod
- (4) Heated Bed Adjustment M3 Thumb Nut
- (1) MK8 Filament all-Metal Remote Bowden Extruder Parts
- (1) Aluminum Spacer (6 x 1/4" x 3/8")
- (3) Mechanical Endstop Switch

**Mechanical parts**

- (11) LM8UU Linear Bearings 
- (2) 5mm to 8mm Shaft Rigid Motor Wheel Coupling Coupler 
- (1) GT2 2mm pitch 6mm wide Timing Belt (5 Meters)
- (2) GT2 Pulley 16T 6mm Width
- (2) 608 Ball Bearing
- (4) NEMA 17 Stepper Motor
- (1) Half Height NEMA 17 Stepper Motor

**Optional**

- (1) Heated Bed Tempered Borosilicate Glass Plate (213mm x 200mm x 3mm) 
- (5) Dupont 2.54mm Connector Housing Female
- (30) Dupont Jumper Wire Cable Female Pin Connector 2.54mm
- (1) Mellow-Yellow MDPC-X Sleeve (25ft)

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

### Resources:
- [P3Steel Wiki](http://reprap.org/wiki/P3Steel)
- [Triffid Hunter's Calibration Guide](http://reprap.org/wiki/Triffid_Hunter's_Calibration_Guide)
- [Prusa Calculator](http://www.prusaprinters.org/calculator/)
- [Prusa3D Slic3r](https://github.com/prusa3d/Slic3r)
- [RepRap GCode Cheat Sheet](https://thingiverse-production-new.s3.amazonaws.com/assets/87/b0/2c/f5/4c/CheatSheet.pdf)
- [Mini height sensor board](https://miscsolutions.wordpress.com/mini-height-sensor-board/)
