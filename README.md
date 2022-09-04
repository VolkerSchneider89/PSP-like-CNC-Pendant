# PSP-like-CNC-Pendant
1 Handwheel, 3 Encoder/Buttons, 14 Buttons, Arduino Micro

![alt text](https://github.com/VolkerSchneider89/PSP-like-CNC-Pendant/blob/main/Images/CAD-Rendered.jpg?raw=true)

## Intro ##
I'll try not to ramble too much and get straight to the point. I am currently in the process of planning a CNC milling machine (the second to be exact. This one should be more stable and ideally mill steel as well. The first one is a MPCNC) and to be able to control the milling machine independently from the pc. I need a pendant. The pendants I don´t like the ones I found so I have designed my own. The outer dimensions correspond to a PSP (of course it is not so flat :D).

A disclaimer at the beginning. Since I do this beside my job and beside the care of my son everything is certainly not super tidy. But I hope it gives the one or the other an idea. It is also a work in progress at the moment.

I plan to use the keymap function of the Universal Gcode Sender and it is based on an Arduino. It is important that it is a Micro, pro micro or Leonardo, because they can also communicate via USB with the computer (like a keyboard). Other arduinos probably can't do that (afaik). 


## Requirements ##
For me the pendant must fulfill some requirements, which I list below. This resulted in the CAD model you can find in the CAD folder (Fusion 360 and step files)
          
1. 14x push buttons (diameter 12mm)
   1. Start
   2. Pause
   3. Stop
   4. Zeroing X Axis
   5. Zeroing Y Axis
   6. Zeroing Z Axis
   7. Homing
   8. Minimum quantity lubrication On/Off
   9. Open Valve for compressed ait to change tool (manual change)
   10. Move to parking position to fix the workpiece (1st macro)
   11. Four placeholders for further macros
2. 3x KY-040 encoders (with push button to enable selection)
   1. Select axis for jog command
   2. Select resolution of jog command
   3. Set spindle speed
3. Handwheel
   1. To select the steps for the jog command 
4. Display 
   1. Optical feedback
   
   
## Layout ##

To give you an overview of the parts to be made, an exlosion view is attached below. I use a mixture of milled parts (acrylic front panel, wooden frame, PCB) and 3D printed parts (base, display holder). It should be no problem to 3D print or mill all parts depending on the looks you want to have.

![alt text](https://github.com/VolkerSchneider89/PSP-like-CNC-Pendant/blob/main/Images/Pendant_Exploded_view.png?raw=true)

