# Logisim-BIG-TTL-CMOS-Library
This is TTL 7400 series and CMOS 4000/4500 series library for Logisim 2.7.1 and Logisim-evolution.
This library was originally designed as a catalog for IC selection, but it also works well in simulations.

# Project objectives
* Cover the 74 series from 00 to 899 as much as possible.
* Reproduce the behavior of the real thing as much as possible.

# File Extension
The original file extension for both software is ".circ", but the formats that can be opened by the two companies are clearly different. Therefore, the library for Logisim-evolution is explicitly listed with the extension ".cricevo".

# Limitations
* This library does not contain Memory (ROM, RAM, Register File, FIFO, Controller, etc.), PLA, Analog, 11 bits or larger bit width devices.
* Those for which gate-level logic diagrams are not provided are not included.
* Glitch, Skew, Hazard, Racing, Fanout limitation, and some abnormal conditions may not be perfectly reproduced.
* Buffers and inverters not related to logic may be omitted to optimize simulator performance.
* The pin number assignments are for popular dual inline packages.

# Bug Report
I have never used an actual IC unless otherwise noted.
Since it is copied from an old datasheet, if the datasheet is incorrect, it may behave differently from the actual IC.
If you found any problems such as different logic, Open Collector attribute, trigger type or etc., please contact me.

# Supported Devices
<img width="1178" height="674" alt="Supported_Devices" src="https://github.com/user-attachments/assets/0d98d485-a7fd-4caa-9f2d-e148b3ba4489" />
