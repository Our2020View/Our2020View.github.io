---
layout: page
title: RV Holding Tank Heater Ammeter | RV Mods
description: How do you know if your tank heaters are working?
permalink: /ourmods/ammeter/
---

So, good news / bad news on this one.  The good news is that we now have a mod that works like a champ.  The bad news is that the new mod has definitively, conclusively, and unceremoniously, confirmed that our Winnebago installed tank heaters have never worked.  In the process of installing the mod, I tested the heat pads in cold temperatures, using numerous methods, and ended up concluding what I have always suspected: they were installed without being tested and given to us hoping that if they didn’t work, we would never notice.  If you wound up on this page because your tank heaters are currently not working, have a look at our tank heater retrofit found <a href = "https://our2020view.ca/ourmods/tankheaters/ " target="_blank">HERE. </a>  Or, if you’d like to make sure your tank heaters are really working, read on below... 

<h3>The Ammeter Mod</h3>

How do you know the holding tank heaters are actually working?  The light in the switch just tells you that the switch has changed positions, and maybe, perhaps, sure hope so ... power is being sent to the holding tank heater relay down in the wet bay area.  Installing an ammeter gauge that lights up only if the relay allows holding tank heater circuit power to flow to the pad thermostats, and will only show a current draw if the pad thermostats are actually allowing power to flow to the pads to keep them warm - is what this mod is all about...

Over the course of a long time troubleshooting a tank heater snag that came out of the factory on our View / Navion, here is what I learned about the tank heater circuit:

1 - The tank heater switch is powered from the circuit associated with the water pump.  (Yes ... the water pump.)  The switch does not directly turn on the heaters, and the light simply indicates that the switch has changed positions.  The switch operates a relay, located in the wetbay in our View, which in turn closes a contact to allow electricity from the actual tank heater circuit to flow to the pad thermostats.  

2 – The relay uses a little bit of power when the switch is thrown (.5 amps), whether or not the pads are actually being heated.

3 – The wires from the relay to the pads flow through a connector, about 6” downstream, also located in the wet bay.

4 – Because of the thermostats at the heating pads, you can’t test the wiring downstream of the wetbay connector until the pads are cold enough to close the pad contactors.  Checking the voltage at the wetbay connector just tells you the relay has closed.

5 – When the pad thermostats close, and current flows through the pads and then to a coach ground, pulling the tank heater fuse will illuminate the blown fuse light on the panel.  If the thermostats are not closed, current is not flowing through the tank heater circuit, and therefore the blown fuse indicator in the fuse panel is not standing by to light if a fuse blows.  You might potentially only see the blown fuse indicator if the switch has been thrown, and it is cold outside...

This diagram shows the **original Winnebago system**:

<img src="/assets/weboriginalheatercircuit.jpg"/>

I wanted to put an ammeter gauge in the cabinet above the cooktop, beside the tank heater switch, so here is what I needed to do:

1 – Find an ammeter that would be appropriate for the job.  I settled on this one:

<a href = "https://www.amazon.ca/gp/product/B08FX7JZ5D/ref=ppx_yo_dt_b_asin_title_o00_s01?ie=UTF8&psc=1 " target="_blank">12 Volt Ammeter </a>

2 – Power the gauge from the output of the relay, so the gauge will only light up when the switch is thrown **and** the relay actually sends power to the pads.  Doing it this way will always confirm if the relay has worked.  I needed to splice into the relay power output, and then send the wire out of the wetbay via the hole in the floor under the shower, under the bed, up to the top of the fridge, and then into the cooktop cabinet to be connected to the new gauge.  Let's call this Wire #1.

3 – Take the ground exiting the pads, sever its original Winnebago return path, butt splice it to a new grounding wire, feed it out of the wet bay to follow the same path as the power wire described above, and connect it to the new gauge.  Let' call this Wire #2.

4 – Take another new grounding wire from the remaining negative post on the new gauge, send it out of the cabinet to the top of the fridge, down the back, into the Truma box, and then hook it up to the grounding post on the back of the fuse box.  This will be Wire #3.

(I got rid of the connector downstream of the power relay, as my new circuit only uses the power wire; the Winnebago ground wire was cut and became redundant.)

The vendor I purchased my ammeter from did not provide any instructions, but I found the info I needed on another vendor’s advertisement of the same type of product.  Here is an illustration of how the ammeter gets connected:

<img src="/assets/webammeterdiagram2.jpg"/>

The left hand bronze terminal takes Wire #1 from the output of the relay down in the wetbay, the middle silver terminal takes the new ground Wire #2 from the heating pads, and the right hand silver terminal takes the new ground Wire #3 that goes down to the grounding post on the fuse box.  

Here is a wiring diagram of **the new mod** - I left out all of the irrelevant ground wires, and concentrated just on the new wires I needed to add:

<img src="/assets/webammeterdiagramV5.jpg"/>

Once you have got this hooked up, if it is warm outside and the pad thermostats are not going to close to allow current to flow through the pads, throwing the switch will give you this result:

<img src="/assets/webammeter16a.jpg"/>

The switch, powered by the water pump circuit, has passed voltage to the tank heater relay in the wet bay, and the relay is allowing power to be passed on to the heat pads and the ammeter gauge.  The thermostats have not closed, so there is no current flowing through the pads and no current showing on the gauge.  This is normal for warm temperatures.

If it is cold enough outside, you will see the ammeter register some current.  For two Winnebago factory heating pads made by Thermaheat, that actually work, you should see about 10 amps register on the ammeter.  Here is a photo of what we are getting with the four pad combination UltraHeat pads installed during our heating pad retrofit:

<img src="/assets/webammeter99.jpg"/>

With this mod, you will be able to answer three questions, instead of just one, if you throw the switch in cold weather:

1 – As per the Winnebago design, have the switch contacts changed position and illuminated the switch light?

2 – The health of the relay - is it working and is it trying to pass power to the heating pads?

3 – The health of the pads – are they working per design and allowing current to flow when they are colder than 45 degrees F?

The mod works great, and looks pretty cool as well!



<br>

[Back to Our RV Modifications](/ourmods/)
