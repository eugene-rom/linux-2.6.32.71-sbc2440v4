### Linux kernel for SBC2440-I single board computer.

Linux kernel 2.6.32.72 with patches to support SBC2440-I single board computer (my board marked "SBC2440V4"). Patches based on kernel for Mini2440 board. 

SBC2440-I board is mostly similar to popular Mini2440 board, however includes second Ethernet interface, additional USB port, changed storage layout, changed buttons, etc.

My board originally comes with modified linux kernel 2.6.13 and I was unable to find its source code. So, I modified original Linux kernel 2.6.32.72 to include changes from mini2440 2.6.32.2 kernel and added tweaks for SBC2440-I, where it differs from mini2440.


What does not work (TODO):
- 10Mb Ethernet interface (no driver for CS8900A)
- Only one USB port works (unknown reason for now)


Not tested:
- Camera interface
- IDE interface



Board photo: [sbc2440v4.jpg](_board_info/sbc2440v4.jpg)  
Board specification: [SBC2440I.pdf](_board_info/SBC2440I.pdf)  
Schematic: [sbc2440Isch.pdf](_board_info/sbc2440Isch.pdf)
