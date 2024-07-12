<!--
Title:              QSFP28 Mezzanine Card
Author(s):          Orcel Thys
Date Created:       20 July 2023
Date (Last) Edited: 15 August 2023
-->

# QSFP28 Mezzanine Card 


## Getting started

This is the main repository of the QSFP28 Mezzanine card.<br>
QSFP28 supports high data rates, typically up to 40 Gbps (4 channels at 10 Gbps each).<br> 
This makes it ideal for applications that require fast data transfer, such as networking equipment and data centers.

The schematic document of the mezzanice board can be found [here](./[v01]/QSFP28_Mezzanine.pdf).<br> 
The 6-layers PCB layout is still in progress due to time constraints.  

## Specifications

This Mezzanine is designed to work with any FPGA carrier board compatible with ANSI/VITA 57.4 FPGA Mezzanine Card Plus (FMCP).                                                                                                                 

The interfaces of this mezzanine are: 
- Access to direct power from the carrier board (1.2v, 1.8v, 3.3v ... 5v)
- 6 x QSFP+ connectors for high-speed optical communiucation 
- 10 x SMA sockets for I/O and clock signals 
- Power LED

## Authors
* **Orcel Thys**   - Designer and updates