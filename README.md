# teaMachineFCBMicroUSBAdapter

## Requirements
teaMachine used to use a COTS (Commercial Off-The-Shelf) micro USB cable. However, the connector is too large and does not fit when the device is fully assembled. Goal of the project was to design FPCB (flexible printed circuit board) which will connect touch panel to the raspberry pi zero (USB hub is only for debug pruposes)

![Device](images/device.png)

## Solution
To resolve this issue, a custom flexible printed circuit board (FPCB) was designed:
- Designed in **EasyEDA** (quick and COTS components to buy from LCSC).
- Utilized a micro USB plug from **LCSC**.
- Manufactured by **JLCPCB**.
- optimized the size to be smaller than 10x10cm (below those dimensions FPCB are for 2$, exceeding those dimensions can increase the prise easily even 10 times)

## Project Overview

### Prototyping

First prototypes has been made with 'PaperCAD' to test fit dimensions.

![PaperCAD](images/paper_cad.jpeg)

### Stackup
![FCB Stackup](images/FCB_stackup.png)

### 3D Views
**Top View**  
![Top View](images/3d_view_top.png)

**Bottom View**  
![Bottom View](images/3d_view_bottom.png)

### Trace Design
**100 Ohm Differential Pair Routing**  
![100 Ohm Differential Pair](images/100ohm_diff.png)

### Flex Preview
![Flex Preview](images/flex_preview.png)



## Assembled flat cable

Assembled cable is working, dimensions are correct, only micro USB footprint is horrible to solder, so this should be corrected.

![Assemled](images/assembled.png)

