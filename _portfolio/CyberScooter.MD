---
title: "3D Printed Syringe Pump"
excerpt: "DIY Syringe Pump capable of dispensing 1-10 uL/min of flow rate with adjustable interface."
header:
  image: assets/img/Notes_260113_064504_0.png
  teaser: assets/img/Notes_260113_064504_0.png
---
title: "Features"
*Pump is driven by a stepper motor coupled to a lead screw.
*Flow rate of the pump (mL/min) can easily be set in the Arduino program (i.e., one global variable for flow rate and one for syringe pump diameter). Commanded flow rate may be a decimal (e.g., 0.6 mL/min)
*The syringe pump is compatible with 20 mL and 10 mL syringe sizes and is capable of driving the plunger to the full extent of each syringe until it is completely emptied.
*Has LED that is green when running, yellow when paused, and red when out of liquid.
*One latching button to start and pause the motion of the pump.
*A switch which stops the motion when the plunger has reached its limit (i.e., there is no more liquid left in the pump).
---
Title: "Materials and Parts Needed" 

