# giant-hamax-bike-mount
Adapter for mounting Hamax child seat onto a Giant e-bike
## Front bracket
* [front bracket](https://drive.google.com/open?id=0B5_mAlpV8IjvVjJNTEVIU1ZCUmM)
* [front bracket_pic2](https://drive.google.com/open?id=0B5_mAlpV8IjvczJOUTBDSXNsVDA)

## Back bracket
* [back bracket](https://drive.google.com/open?id=0B5_mAlpV8IjvdmJTcnJxTV9HT0U)

# Output files
* [g-code file (for LinuxCnC)](https://drive.google.com/open?id=0B5_mAlpV8IjvbHlTNG1saUJGbk0)
* [PDF-file of drawing, with markings for drills](https://drive.google.com/open?id=0B5_mAlpV8IjvUTZYWENMREZweDg)

# Description
The DXF file shows the outline of the brackets.  Each bracket consists of three pieces: a top, middle and bottom piece.  [HeeksCnC](https://github.com/Heeks/heekscnc) has been used to convert the DXF-to G-code.  The G-code is loaded into a LinuxCnC milling machine.  Starting from a 10mm Delrin plate, a 4mm mill will make the pieces for you in a few minutes.  
After milling, holes must be drilled down on the 10mm wide side of the piece using a 4.2mm drill.  The PDF-file shows you the distances.  After that, tap M5-screw thread.

# Mounting
Use M5x35 countersunk screws to fix the top-piece to mid-piece.  
Use M5x25 countersunk screws to fix the bottom-piece to the mid-piece.  Longer swrews could be used, but the M5-tap I used only taps down to 18mm.
