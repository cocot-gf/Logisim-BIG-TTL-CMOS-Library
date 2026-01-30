# Logisim-BIG-TTL-CMOS-Library
This is TTL 7400 series and CMOS 4000/4500 series library for Logisim 2.7.1 and Logisim-evolution.
This library was originally designed as a catalog for IC selection, but it also works well in simulations.

# Project objectives
The development was based on Logisim 2.7.1, then extended to the CMOS4000 series and ported to Logisim-evolution.

* Cover the 74 series from 00 to 899 as much as possible.
* Reproduce the behavior of the real thing as much as possible.

# Supported Devices
<img width="1178" height="674" alt="Supported_Devices" src="https://github.com/user-attachments/assets/0d98d485-a7fd-4caa-9f2d-e148b3ba4489" />

# File type and Extension
Although both software programs use the native file extension ".circ", the formats they can open are distinctly different, which is why Logisim-evolution's libraries are explicitly listed with the ".cricevo" extension.

# Limitations
* This library does not contain Memory (ROM, RAM, Register File, FIFO, Controller, etc.), PLA, Analog, 11 bits or larger bit width devices.
* Those for which gate-level logic diagrams are not provided are not included.
* Glitch, Skew, Hazard, Racing, Fanout limitation, and some abnormal conditions may not be perfectly reproduced.
* Buffers and inverters not related to logic may be omitted to optimize simulator performance.
* The pin number assignments are for popular dual inline packages.

# File diff issue
The file contents of Logisim-evolution are sorted and saved by section, but the original Logisim randomly rewrites the file contents even if you just save it over without making any changes. Therefore, text difference comparison does not work at all with the original Logisim library.

# Bug Report
I have never used an actual IC unless otherwise noted.
Since it is copied from an old datasheet, if the datasheet is incorrect, it may behave differently from the actual IC.
If you found any problems such as different logic, Open Collector attribute, trigger type or etc., please contact me.
