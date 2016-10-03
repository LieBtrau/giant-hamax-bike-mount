# giant-hamax-bike-mount
Adapter for mounting Hamax child seat onto a Giant e-bike
## Front bracket
![front bracket](https://lh6.googleusercontent.com/MLkOdM3IxOejjGTVLpDcURmQtPC3J10r2vRD_nHHPq3eG13htN7ycsIGmAGl-OjWT14Q7GSA38GdwXU=w1366-h651-rw)
![front bracket_pic2](https://lh6.googleusercontent.com/Nnv74u8p37wB-XHLCDT2xYkQls2tgZJJobhRCt_YOIFonj7YcldxhS2gEHQAESmEK9fUHsfW_QlAtAE=w1366-h651-rw)
## Back bracket
![back bracket](https://lh5.googleusercontent.com/gXLEMozvUytM4_ecarjTSROg7ta174gBidE9qgYr_XVlXVZ5TfZrclUZ5fPvr5NRPYHrADZdK-LRz0Q=w1366-h651-rw)

# Output files
* [g-code file (for LinuxCnC)](https://drive.google.com/open?id=0B5_mAlpV8IjvbHlTNG1saUJGbk0)
* [PDF-file of drawing, with markings for drills](https://drive.google.com/open?id=0B5_mAlpV8IjvUTZYWENMREZweDg)

# Description
The DXF file shows the outline of the brackets.  Each bracket consists of three pieces: a top, middle and bottom piece.  [HeeksCnC](https://github.com/Heeks/heekscnc) has been used to convert the DXF-to G-code.  The G-code is loaded into a LinuxCnC milling machine.  Starting from a 10mm Delrin plate, a 4mm mill will make the pieces for you in a few minutes.  
After milling, holes must be drilled down on the 10mm wide side of the piece using a 4.2mm drill.  The PDF-file shows you the distances.  After that, tap M5-screw thread.

# Mounting
Use M5x35 countersunk screws to fix the top-piece to mid-piece.  
Use M5x25 countersunk screws to fix the bottom-piece to the mid-piece.  Longer swrews could be used, but the M5-tap I used only taps down to 18mm.
