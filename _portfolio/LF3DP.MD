---
title: 3D Printed Syringe Pump
excerpt: "DIY Syringe Pump capable of dispensing 1-10 uL/min of flow rate with adjustable interface."
header:
  image: assets/img/Notes_260113_064504_0.png
  teaser: assets/img/Notes_260113_064504_0.png
---

# Features

** Pump is driven by a stepper motor coupled to a lead screw.
** Flow rate of the pump (mL/min) can easily be set in the Arduino program (i.e., one global variable for flow rate and one for syringe pump diameter). Commanded flow rate may be a decimal (e.g., 0.6 mL/min)
** The syringe pump is compatible with 20 mL and 10 mL syringe sizes and is capable of driving the plunger to the full extent of each syringe until it is completely emptied.
** Has LED that is green when running, yellow when paused, and red when out of liquid.
** One latching button to start and pause the motion of the pump.
** A switch which stops the motion when the plunger has reached its limit (i.e., there is no more liquid left in the pump).
** Two additional monetary buttons that move the motor clockwise and counterclockwise to be able to set the spacing of the plunger holder when loading the syringe without having to move the lead screw with your fingers

# Materials and Parts Needed


| Off the Shelf | 3D Printed |
| ------------- | ------------- |
| 250 mm lead screw with 2 mm pitch and 2 mm lead (x1) | Motor Backplate |
| 250 mm lead screw with 2 mm pitch and 8 mm lead (x1) | Carriage |
| 1/4” x 8mm flexible coupling (x1)	| Syringe End Support |
| 200 mm linear rod with 8 mm diameter (x2) |	End Support |
| LM8UU linear bearing for 8 mm diameter rod (x2)	| Enclosure Base for Arduino |
| 2040 aluminum extrusion 1’ length (x1) | Enclosure Top |
| Nema 17 stepper motor (x1) | Enclosure Lid |
| MEAN WELL RQ-65D AC-DC power supply quad output 5V 12V 24V 12V 4 amp (x1)	| Potentiometer Adapter |
| Arduino Uno (x1) |
| A4988 stepper driver (x1) |	 
| Small breadboard (x1)	| 
| Panel mount latching push buttons (on/off) (x1) |	 
| Panel mount momentary push buttons (x1)	| 
| Limit switch (x1)	| 
| RGB common cathode LED (x3)	| 
| Knob button |

# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Large Format 3D Printer Gallery" %}
