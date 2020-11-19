# PCB for soldering wires to Neutrik NE8FDV

<p align="center">
  <img width="512" height=602" src="https://raw.githubusercontent.com/mjcourte/neutrik-ethercon-quad-balanced-audio-pcb/main/photos/NeutrikEthercon.png">
</p>

- **This is an unoffical PCB, use at your own risk.**
- **This is not designed for ethernet networking!**
- The PDF datasheet was retrieved from Neutrik's website Feb 25 2020. The document belongs to them and is subject to changes on their end. This copy is here for reference only.
- This is for making a quad-balanced (XLR or TRS) breakout box with ethernet or EtherCON backhaul (cat5* or cat6a).

## Example build

I used this PCB to create a single cable backhaul for an Axe FX II guitar processor (without using USB audio because I use a different interface). 
The rack the processor lives in already has a breakout panel, so I added one NE8FDV to the rear, and linked it to the other connectors.
A breakout box that lives at the back of my desk has one NE8FDV and 4x Neutrik NJ3FP6C locking TRS 1/4" connectors.

<p align="center">
  <img width="512" height=602" src="https://raw.githubusercontent.com/mjcourte/neutrik-ethercon-quad-balanced-audio-pcb/main/photos/pcbfit-crop.jpg">
</p>

Turns out the PCB fits like a glove. 
After soldering the pins, I used hot glue on the plastic alignment pins to protect the ethernet pins from strain.

<p align="center">
  <img width="512" height=602" src="https://raw.githubusercontent.com/mjcourte/neutrik-ethercon-quad-balanced-audio-pcb/main/photos/gutshot.jpg">
</p>

Here is the internal wiring of the breakout box with 4 TRS jacks. The wires were too long, but I was too lazy to cut and re-strip/twist/tin 12 wires again.

<p align="center">
  <img width="512" height=602" src="https://raw.githubusercontent.com/mjcourte/neutrik-ethercon-quad-balanced-audio-pcb/main/photos/exterior-crop.jpg">
</p>

Finally, the exterior of the box.
I used an old cat5e cable fitted with Neutrik NE8MX RJ45 carriers.

