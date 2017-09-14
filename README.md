# giant-hamax-bike-mount
Adapter for mounting Hamax child seat onto a Giant e-bike

## Front bracket
<img src="https://github.com/LieBtrau/giant-hamax-bike-mount/blob/master/20161003_200435.jpg" alt="Drawing" style="width:100px"/>
<img src="https://github.com/LieBtrau/giant-hamax-bike-mount/blob/master/20161003_200530.jpg" alt="Drawing" style="width:100px"/>

## Back bracket
<img src="https://github.com/LieBtrau/giant-hamax-bike-mount/blob/master/20161003_200504.jpg" alt="Drawing" style="width:100px"/>

# Output files
* [g-code file (for LinuxCnC)](https://drive.google.com/open?id=0B5_mAlpV8IjvbHlTNG1saUJGbk0)
* [PDF-file of drawing, with markings for drills](https://drive.google.com/open?id=0B5_mAlpV8IjvUTZYWENMREZweDg)

# Description
The DXF file shows the outline of the brackets.  Each bracket consists of three pieces: a top, middle and bottom piece.  [HeeksCnC](https://github.com/Heeks/heekscnc) has been used to convert the DXF-to G-code.  The G-code is loaded into a LinuxCnC milling machine.  Starting from a 10mm Delrin plate, a 4mm mill will make the pieces for you in a few minutes.  
After milling, holes must be drilled down on the 10mm wide side of the piece using a 4.2mm drill.  The PDF-file shows you the distances.  After that, tap M5-screw thread.

# Mounting
Use M5x35 countersunk screws to fix the top-piece to mid-piece.  
Use M5x25 countersunk screws to fix the bottom-piece to the mid-piece.  Longer swrews could be used, but the M5-tap I used only taps down to 18mm.
