# Extension board for ECP5_BGA381_FT2232HQ_FIFO
This is an extension board for the [ECP5_BGA381_FT2232HQ_FIFO](https://github.com/gildobjanschi/ECP5_BGA381_FT2232HQ_FIFO) board. It is used to validate the main board design and to provide audio output connectors for I2S (HDMI) and SPDIF (Coaxial).

## Software
The software that supports this board is located in the main board [ECP5_BGA381_FT2232HQ_FIFO](https://github.com/gildobjanschi/ECP5_BGA381_FT2232HQ_FIFO/tree/main/hdl_test) project. The [host software](https://github.com/gildobjanschi/ECP5_BGA381_FT2232HQ_FIFO/tree/main/host_test) is an application for testing the FIFO interface.

## Project Status
The board has been submitted to manufacturing to PCBWay.

[Schematic PDF](https://github.com/gildobjanschi/ECP5_BGA381_FT2232HQ_FIFO_EXT/blob/main/kicad/ECP5_Ext.pdf)

![Board rendering](https://github.com/gildobjanschi/ECP5_BGA381_FT2232HQ_FIFO_EXT/blob/main/ECP5_Ext.jpg)

## How To setup KiCAD
Checkout the KiCAD project and open it. In the Configure Paths dialog add: Name: ECP5_BGA381_FT2232HQ_FIFO_EXT and Path: "The full path to the GitHub directory"/GitHub/ECP5_BGA381_FT2232HQ_FIFO_EXT

In the Manage Symbol Libraries click the Project Specific Libraries tab and add: Name: ECP5_BGA381_FT2232HQ_FIFO_EXT and Library Path: ${ECP5_BGA381_FT2232HQ_FIFO_EXT}/symbols/Symbols.kicad_sym

In the Manage Footprint Libraries click the Project Specific Libraries tab and add: Name: ECP5_BGA381_FT2232HQ_FIFO_EXT and Library Path: ${ECP5_BGA381_FT2232HQ_FIFO_EXT}/footprints/Footprints.kicad_sym
