---
title: 3D Printed Syringe Pump
excerpt: "DIY Syringe Pump capable of dispensing 1-10 uL/min of flow rate with adjustable interface."
header:
  image: assets/img/Notes_260113_064504_0.png
  teaser: assets/img/Notes_260113_064504_0.png
---

# Features

- Pump is driven by a stepper motor coupled to a lead screw.
- Flow rate of the pump (mL/min) can easily be set in the Arduino program (i.e., one global variable for flow rate and one for syringe pump diameter). Commanded flow rate may be a decimal (e.g., 0.6 mL/min)
- The syringe pump is compatible with 20 mL and 10 mL syringe sizes and is capable of driving the plunger to the full extent of each syringe until it is completely emptied.
- Has LED that is green when running, yellow when paused, and red when out of liquid.
- One latching button to start and pause the motion of the pump.
- A switch which stops the motion when the plunger has reached its limit (i.e., there is no more liquid left in the pump).
- Two additional monetary buttons that move the motor clockwise and counterclockwise to be able to set the spacing of the plunger holder when loading the syringe without having to move the lead screw with your fingers

# Materials and Parts Needed


| Off the Shelf            | 3D Printed    |
| ------------------------ | ------------- |
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

# Arduino Code
https://github.com/vivianhlee05/Arduino-Code-for-Syringe-Project.git

# How to Operate
The syringe pump operates by first connecting the power supply, after which the Arduino Uno runs preloaded code with preset syringe diameter, flow rate, and motor settings. Upon startup, the LCD displays the current speed and a “Ready” status while the LED turns yellow, indicating the system is awaiting input. A 10 mL or 20 mL syringe is secured in the holder, and the carriage is aligned with the plunger using forward and reverse buttons to ensure proper positioning. The user sets the desired flow rate using a dial, with the selected speed shown on the LCD in milliliters per minute. Pressing the start/stop button initiates pumping, turning the LED green as the stepper motor drives the lead screw and advances the carriage to dispense fluid at the chosen rate. The pump can be paused at any time, and once the syringe is empty, a limit switch stops the motor and signals completion with a red LED. Mechanically, the system converts the stepper motor’s rotational motion into linear motion of the carriage via a lead screw, allowing precise and adjustable fluid delivery through software-controlled step frequency without requiring hardware changes.

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028110f9dc5c5441513e5?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

