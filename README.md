# microUSBextender

# Flexible Custom Board (FCB) Design Documentation

## Problem Statement
The device uses a COTS (Commercial Off-The-Shelf) micro USB cable. However, the connector is too large and does not fit when the device is fully assembled.

![Device](images/device.png)

## Solution
To resolve this issue, a custom flexible printed circuit board (FPCB) was designed:
- Designed in **EasyEDA**.
- Utilized a micro USB plug from **LCSC**.
- Manufactured by **JLCPCB**.

## Project Overview

### Stackup
![FCB Stackup](images/FCB_stackup.png)
- Optimized for flexibility and durability.

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


## Repository Structure
- **README.md**: Main documentation.
- **docu/**: Supporting documents.
- **exports/**: Output files (Gerber, BOM, etc.).
- **images/**: Visual assets for documentation.
- **project-files/**: EasyEDA project files.
