---
layout: page
title: RV Holding Tank Heater Ammeter | RV Mods
permalink: /ourmods/ammeter/
---

So, good news / bad news on this one.  The good news is that the mod I had been waiting to get finished is finally done, and works like a champ.  The bad news is that the new mod has definitively, conclusively, and unceremoniously, confirmed that my Winnebago installed tank heaters have never worked.  In the process of the installing the mod, I tested the heat pads in cold temperatures, using numerous methods, and ended up concluding what I have always suspected: they were installed without being tested and given to us hoping that if they didn’t work, we would never notice.  At any rate, if you’d like to know if your tank heaters are really working, read on below.  Or, if you wound up on this page because your tank heaters are currently not working, it is possible that the information on this page might also be of some use with your troubleshooting.

<h3>The Ammeter Mod</h3>

How do you know the holding tank heaters are actually working?  The light in the switch just tells you that the switch has changed positions, and maybe, perhaps, sure hope so ... power is being sent to the holding tank heater relay down in the wet bay area.  Installing an ammeter gauge that lights up only if the relay allows holding tank heater circuit power to flow to the pads, and will only show a current draw if the pad thermostats are actually allowing power to flow to the pads to keep them warm, is what this mod is all about...

Over the course of a long time troubleshooting a tank heater snag that came out of the factory, here is what I learned about the tank heater circuit:

1 - The tank heater switch is powered from the circuit associated with the water pump.  (Yes ... the water pump.)  The switch does not directly turn on the heaters, and the light simply indicates that the switch has changed positions.  The switch operates a relay, located in the wetbay in our View, which in turn closes a contact to allow electricity from the actual tank heater circuit to flow to the pads.  

2 – The relay uses a little bit of power when it is in use (.5 amps), whether or not the pads are actually energized.

3 – The wires from the relay to the pads flow through a connector, about 6” downstream, also located in the wet bay.

4 – Because of the thermostats at the heating pads, you can’t test the wiring downstream of the wetbay connector until the pads are cold enough to close the pad contactors.  Checking the voltage at the wetbay connector just tells you the relay has closed.

5 – When the pad thermostats close, and current flows through the pads and then to a coach ground, pulling the tank heater fuse will illuminate the blown fuse light on the panel.  If the thermostats are not closed, current is not flowing through the tank heater circuit, and therefore the blown fuse indicator in the fuse panel is not standing by to light if a fuse blows.  You might potentially only see the blown fuse indicator if the switch has been thrown, and it is cold outside...

This diagram shows the original Winnebago system:

<img src="/assets/weboriginalheatercircuit.jpg"/>

I wanted to put an ammeter gauge in the cabinet above the cooktop, beside the tank heater switch, so here is what I needed to do:

1 – Find an ammeter that would be appropriate for the job.  I settled on this one:

<a href = "https://www.amazon.ca/gp/product/B08FX7JZ5D/ref=ppx_yo_dt_b_asin_title_o00_s01?ie=UTF8&psc=1 " target="_blank">12 Volt Ammeter </a>

2 – Power the gauge from the output of the relay, so the gauge will only light up when the switch is thrown and the relay actually sends power to the pads.  Doing it this way will always confirm if the relay has worked.  I needed to splice into the relay power output, and then send the wire out of the wetbay via the hole in the floor under the shower, under the bed, up to the top of the fridge, and then into the cooktop cabinet to be connected to the gauge.  Let's call this Wire #1.

3 – Take the ground exiting the pads, sever its original Winnebago return path, butt splice it to a new grounding wire, feed it out of the wet bay to follow the same path as the power wire described above, and connect it to the gauge.  Let' call this Wire #2.

4 – Take another new grounding wire from the remaining negative post on the gauge, send it out of the cabinet to the top of the fridge, down the back, into the Truma box, and then hook it up to the grounding post on the back of the fuse box.  This will be Wire #3.

(I got rid of the connector downstream of the power relay, as my new circuit only uses the power wire; the Winnebago ground wire was cut and became redundant.)

The vendor I purchased my ammeter from did not provide any instructions, but I found the info I needed on another vendor’s advertisement of the same type of product.  Here is an illustration of how the ammeter gets connected:

<img src="/assets/webammeterdiagram2.jpg"/>

The left hand bronze terminal takes Wire #1 from the output of the relay down in the wetbay, the middle silver terminal takes the new ground Wire #2 from the heating pads, and the right hand silver terminal takes the new ground Wire #3 that goes down to the grounding post on the fuse box.  

Here is a wiring diagram of what I ended up with - I left out all of the irrelevant ground wires, and concentrated just on the new wires I will need to add:

<img src="/assets/webammeterdiagramV5.jpg"/>

Once you have got this hooked up, if it is warm outside and the pad thermostats are not going to close to allow current to flow through the pads, throwing the switch will give you this result:

<img src="/assets/webammeter16.jpg"/>

The switch, powered by the water pump circuit, has passed voltage to the tank heater relay in the wet bay, and the relay is allowing power to be passed on to the heat pads and the ammeter guage.  The thermostats have not closed, so there is no current flowing through the pads.

If it is cold enough outside, or both of your pads have duff thermostats and are  allowing a token amount of current to pass regardless of temperature, you will see the ammeter register some current:  (for two good heating pads you should see about 9 amps register on the ammeter – this is a picture illustrating my tank heater snag)

<img src="/assets/webammeter17.jpg"/>

With this mod, you will know three things, instead of just one, if you throw the switch in cold weather:

1 – The health of the relay - is it working and is trying to pass power to the heating pads?

2 – The health of the pads – are they working per design and allowing current to flow when they are colder than 45 degrees F?

3 – As per the Winnebago design, have the switch contacts changed position and illuminated the switch light?

The mod works great, and looks pretty cool as well!

<h3>History of the Mod and troubleshooting the factory snag</h3>

During some past late December dry camping, we needed the protection from the Winnebago installed holding tank heaters.  When I turned them on and watched my Victron app to take note of the amperage change, I noted that they were only pulling between 1 and 2 amps.  Those heaters are supposed to pull about 5 amps each at temperatures below 45 degrees F, so I suspected we had a problem.  Doing a tactile check on the pads confirmed my suspicions, as I could not detect any heat on the pads anywhere.  I can’t say that they have ever worked – the only other time I used them we were popping up above freezing during the daytime hours, so the risk to the tanks was low - but thinking about it later, the current draw at that time was less than two amps as well.   

At the time I checked the wiring where I could – voltage leaving the fuse box, voltage at the switch, voltage out of the switch - I also did a half-hearted search for the ground wire on the fuse box -  but no luck with anything  – so basically I gave up and assumed the problem was wiring related downstream of the switch, or somewhere that I never would have been able to find.  I started going on the assumption that I would have to run new wires from the heating pads, to ensure that I understood where everything was directed.  (The possibility of a double pad failure never crossed my mind.)

My thinking then turned to a way to make darn sure these things were working in cold conditions when I flicked the switch to ON.  Currently, the light in the switch only confirms that the switch has changed positions; it does not confirm that current is actually going to the heating pads.  So how about adding an ammeter to the circuit so I could see the 10 amps that is supposed to register?  The plan was to install the ammeter gauge up on the left side of the switch, on the panel behind the kitchen cabinet door above the stove top.

Subsequent troubleshooting of my basic problem produced discouraging results, so I queried the Winnie Owner’s Forum to see if someone else had seen this problem before.  It turns out that someone else had indeed seen it, but in a 2015 Trend.  Following the thread, I was able to pick up on some really valuable thoughts that helped me quite a bit.

The Trend owner had determined that the tank heater switch was powered by the water pump circuit, of all things.  And, with the switch on, pulling the 15 amp fuse for the tank heaters had no effect on the light in the switch, or the blown fuse indication on the fuse panel.  With this in mind, one of the commenters wondered if there was a relay that was worked by the switch, allowing power to the tank heaters when closed.  A relay that allows another circuit to power the heating pads?  Interesting thought...

After confirming that my switch was powered by the water pump circuit as well, I went back to the drawings, yet again, and this time struck pay dirt – a relay that was evidently located under the bed area, behind the back wall of the shower.  An uncomfortable under the bed search for the relay yielded no success, of any kind.  But, later, I did recall that while poking around in the wet bay for another mod, I saw something that looked like a 12 volt relay.  I dug out the pictures from that mod, and was able to view the wire identifiers that it was hooked up to.  Checking the drawings again revealed that it was indeed a relay, and for sure was the one I was looking for.  

I waited for a quiet time in the neighbourhood, opened the bathroom door, and very carefully worked the switch around its contact point to see if I could hear the relay operating down there in the wet bay...  Yes!  There was no doubt, the relay was clicking quietly and using about 1.8 amps – that mysterious load that I could not explain earlier.  Ok, so the relay was working, so why had it not allowed power from the tank heater circuit to energize the pads during cold weather?  Well, I guess just because it was “clicking” did not necessarily mean that the contact was allowing the circuit to actually close correctly.  Don’t know.  Using the process described in my “Cold Weather Capability” mod, I removed the access panel to the wetbay, and had a look at the relay.  It was very difficult to remove from its contactor block, but when I finally was able to, noted that one corner of the contact area was badly corroded.  Very strange – maybe it got wet in there at one time during manufacture?  At any rate, I cleaned up the contacts as best I could and then seated the relay again on its contactor block.  

After completing this cleanup, I poked around some more in the wet bay and discovered that the output wires from the relay had a connector about 6” downstream -  another potential point of failure.  The connector was by no means “disconnected”, but it seemed to not be on as tight as it should be.  Maybe.  Don’t know.  I wish I had found this sooner, because I could have done a voltage check before cleaning up the relay contacts – and then an after check.  At any rate, I did a power check on the 12 volts leaving the relay and was able to determine that the relay was doing its job when the coach tank heater switch was activated.  Battery voltage was exiting the relay, only when the switch was thrown.  Unfortunately, until it got cold outside, that was about all I could do in the troubleshooting department.

Later in the year, when overnight temperatures started dropping, I started into the mod described above and took the opportunity to isolate the heating pads from the Winnebago factory wiring.  With only power and ground wires to the pads remaining, I put 12 volts and a multimeter on them each in turn, and discovered that at temperatures below the “turn ON” temperature of 45 degrees F ... they were only pulling .6 amps each.  Yup, the pads were not working.  So 1.2 amps for the pads, plus about .5 amps to power the relay – was that the phantom 1.8 amps that I would see on my Victron App in the dead of winter when I tried to get the heaters working?  Very likely.

Here is a photo I took before wiring up the mod; I isolated the pads individually and tested them with an independent power supply, only to discover that neither of them worked:

<img src="/assets/webammeter15.jpg"/>

Once the mod was in place, the new ammeter confirmed what I had found earlier by testing the pads independently; the total draw was only 1.2 amps instead of around the expected 9 or 10 amps.  That is the beauty of an ammeter tieds exclusively to this circuit - there are no mistakes to be made when reading the load - what you see is what you are getting through the pads.

So, looking on the bright side, at least I had discovered what I needed to do to get some heat on the tanks:  replace both pads.  Both pads?  How is that possible that both pads had never worked?  I certainly did not see that one coming either, but have a look at this post from an RV forum on the topic of our specific tank heaters made by ThermaHeat:

From a Forum - <i>I thought I'd post my results in case anyone else needs this information. I have ThermaHeat tank heaters. (Reportedly the same heaters are marketed under some other names as well).  They are rated to draw 4.8 amps and my tests show they draw within .15 amps of that value.  It turns out that assuming the thermostat has activated the heater (in otherwards it's cold enough to turn the heater on) you *can* feel some warmth by placing your hand on the heater (it's not dramatic but definitely noticeable). The other test is to run the heater with antifreeze and measure the temperature. It should be between 45 and 67 degrees F when it's cold out. You should also see a current draw of around 4.8 amps when the heater is running.  What happened in my case is that there was a wiring error and secondly my dealer had a bad batch of heaters. The thermostats were defective in this batch. They replaced all three tank heaters and they still didn't work. They ultimately had to get a new batch of heaters.  It took four visits to finally get things right.  I did get a free wash of the trailer for my trouble.</i>

Is that what we are left with?  Heat pads from a bad batch?  I don’t know, and will never know, but I do know that replacing the pads will be the least of the workload I have been through trying to sort all of this out.  You can bet I will test the new ones before installing them in the spring.  Until then, it looks like another winter of the pink stuff in the grey and black tanks.  

<br>

[Back to Our RV Modifications](/ourmods/)
