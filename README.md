![toolheadfront1.jpg](assets/toolhead-front-1.jpg)

# Wishbone Toolhead

A toolhead for RatRig V-Core printers that support the Chube Conduction hotend and LGX Pro extruders. The CPAP Ducts kind of look like a wishbone.

*Now with simpler belting and a more robust frame.*

## General

I designed this toolhead because I wanted to run a Chube Conduction hotend with water cooling on my RatRig V-Core 3.1.

That presented some challenges, as the only way to do that (with the Conduction water block from LL designed for the LGX Pro) was to use an LGX Pro extruder and attach the extruder, waterblock, and Chube Conduction without any joining plate between them.



#### My goals

* [X]  Simple installation and maintenance
* [X]  Ability to use my current watercooling setup
* [X]  Ability to use the best hardware available atm
* [X]  Minimal X/Y loss
* [X]  Improved Shaper results
* [X]  2 unused m3 heat insert points on the CPAP ducts for adding accessories (cameras)
* [X]  Fully utilize the V-Core 3.1 AWD setup

## Printing

### FDM Printing

#### What to Print (in STL/)

- Beacon Mount.3mf
- CPAP Brace.3mf
- CPap Ducts.3mf
- EBB42 Mount.3mf
- X-Endstop Mount.3mf
- LGX Pro filament sensor.3mf (if you want to use one)

##### Print Settings

- Walls: 5
- Infill: 50%
- Material: ASA/ABS if enclosed, whatever you want if open-air
  - I would print the ducts and duct brace out of ASA or ABS, they're pretty close to the hotend and get a bit toasty.

### SLM Printing

* This toolhead is designed to be printed in aluminum (SLM). PCBWay or in3dtec are good places to go.

- There are M3 threads in this design - the PDFs should be used to tell them how to tap them, or you can do it yourself.

#### What to Print (in SLM/)

- Bottom Toolhead Plate.step
  - Tapping PDF: V-Core Wishbone Toolhead Drawing - Bottom Toolhead Plate.pdf
- LGX Pro + Chube Conduction SLM Plate.step
  - Tapping PDF: V-Core Wishbone Toolhead Drawing - LGX Pro + Chube Conduction SLM Plate.pdf
- Upper-lower plate joiner (x2).step
  - Tapping PDF: V-Core Wishbone Toolhead Drawing - Upper-lower plate joiner.pdf

### *Note

I would not run this unless you have an AWD setup - this thing is heavy at around 500g

# Happy printing!
