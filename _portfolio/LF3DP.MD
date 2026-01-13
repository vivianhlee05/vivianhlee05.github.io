---
title: "assets/img/Notes_260113_064504_0.png"
excerpt: "DIY Syringe Pump capable of dispensing 1-10 uL/min of flow rate with adjustable interface."
header:
  image: assets/img/Notes_260113_064504_0.png
  teaser: assets/img/Notes_260113_064504_0.png
---

# Features

* **Pump is driven by a stepper motor coupled to a lead screw.
* **Flow rate of the pump (mL/min) can easily be set in the Arduino program (i.e., one global variable for flow rate and one for syringe pump diameter). Commanded flow rate may be a decimal (e.g., 0.6 mL/min)
* **The syringe pump is compatible with 20 mL and 10 mL syringe sizes and is capable of driving the plunger to the full extent of each syringe until it is completely emptied.
* **Has LED that is green when running, yellow when paused, and red when out of liquid.
* **One latching button to start and pause the motion of the pump.
* **A switch which stops the motion when the plunger has reached its limit (i.e., there is no more liquid left in the pump).
* **Two additional monetary buttons that move the motor clockwise and counterclockwise to be able to set the spacing of the plunger holder when loading the syringe without having to move the lead screw with your fingers

# Materials and Parts Needed

| Off the Shelf                                      | 3D Printed                    |
______________________________________________________________________________________



# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Large Format 3D Printer Gallery" %}
