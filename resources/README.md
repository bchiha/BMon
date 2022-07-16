# BMON Resources

This directory contains resources that can be used on the TEC-1F with BMON.

- Tiny Basic sample programs and Instruction Manual
- TEC Magazine Code.  Almost all example programs are from issues 10-15 of the Talking Electronics Magazine.  Use Intel Hex Loader.  Start at `0x2000` and press `GO`.  Use Menu to select the program.  Press `Shift-GO` to go back to the menu.  __Note:__ Some programs require an 8x8 Matrix Add-on connected to Output Port 5 and 6. 
- Music for the Play Tune program `0x1D60` or `Shift-D`.  Load using Intel Hex Loader or SIO-In for binary file.  Set Start Address of tune at `0x3F9A`
- A Special message for the ASCII Scroll Program.  Load at `0x2000` and Press `Shift-0` then select `Banner` from the menu and enter `2000` as the start address. 
- JMON Notes with a bit more detail on some of its features.
