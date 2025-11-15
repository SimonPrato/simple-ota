# Simple OTA Design

This repository contains a simple one-stage OTA design done with Cadence EDA tool, using the C35B4C3 technology of AMS. 

## File Structure

A PDF with detailed information, which has been submitted as a solution for an universitary task, is located in the Documentation folder. Simulation, schematic and layout Cadence files are in the Cadence folder. Images for documentary purposes are in the Images folder. 

## Technology
The MOSFET models used are nmos4 and pmos4 of the PRIMLIB library. From the same lib, poly resistances are used. Pad components are used from the IOLIB_ANA_4M library.


## Schematics
![schematic_ideal_cm](Images/schematic_ideal_cm)

First, the OTA has been simulated using an ideal current mirror for biasing

![current_mirror](Images/real_current_mirror)

After successful dimensioning of the OTA, the current mirror is replaced with the simple schematic above. 

## Layout
![layout](Images/layout.png)

## Layout Closeup

![layout_closeup](Images/layout_closeup.png)

Finally, the layout is created.

