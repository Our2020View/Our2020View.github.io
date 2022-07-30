---
layout: page
title: Holding Tank Heater Ammeter
permalink: /ourmods/ammeter/
---

Note:  I have not done this mod yet - I'm still troubleshooting a wiring snag that came from the factory.  But, I'm almost there so hope to have this hooked up soon... Christmas is coming.  I've detailed the troubleshooting process in case you ended up on this page due to a snag of your own involving the tank heaters from Winnebago.

During some past late December dry camping, we needed the protection from the Winnebago installed holding tank heaters.  When I turned them on and watched my Victron app to take note of the amperage change, I noted that they were only pulling between 1 and 2 amps.  Those heaters are supposed to pull about 5 amps each at temperatures well below freezing, so I suspected we had a problem.  Doing a tactile check on the pads confirmed my suspicions, as I could not detect any heat on the pads anywhere.  
I can’t say that they have ever worked – the only other time I used them we were popping up above freezing during the daytime hours, so the risk to the tanks was low - but thinking about it later, the current draw at that time was only about 2 amps as well.   

At the time I checked the wiring where I could – voltage leaving the fuse box, voltage at the switch, voltage out of the switch -  I also did a half-hearted search for the ground wire on the fuse box -  but no luck anywhere  – so basically I gave up and assumed the problem was wiring related downstream of the switch, or somewhere that I never would have been able to find.  I started going on the assumption that I would have to run new wires from the heating pads, to ensure that I understood where everything was directed.

My thinking then turned to a way to make darn sure these things were working in cold conditions when I flicked the switch to ON.  Currently, the light in the switch only confirms that the switch has changed positions; it does not confirm that current is actually going to the heating pads.  So how about adding an ammeter to the circuit so I could see the 10 amps that is supposed to register?  After doing some research, it turns out that a fairly inexpensive ammeter can be purchased from Amazon, and installed relatively simply:

[12 Volt Ammeter](https://www.amazon.ca/gp/product/B08FX7JZ5D/ref=ppx_yo_dt_b_asin_title_o00_s01?ie=UTF8&psc=1)

The plan was to install the ammeter gauge up on the left side of the switch, on the panel behind the kitchen cabinet door above the stove top.

Subsequent troubleshooting of my basic problem produced discouraging results, so I queried the Winnie Owner’s Forum to see if someone else had seen this problem before.  It turns out that someone else had indeed seen it, but in a 2015 Trend.  Following the thread, I was able to pick up on some really valuable thoughts that helped me quite a bit.

The Trend owner had determined that the tank heater switch was powered by the water pump circuit, of all things.  And, with the switch on, pulling the 15 amp fuse for the tank heaters had no effect on the light in the switch, or the blown fuse indication on the fuse panel.  With this in mind, one of the commenters wondered if there was a relay that was worked by the switch, allowing power to the tank heaters when closed.  A relay that allows another circuit to power the heating pads?  Interesting thought...

After confirming that my switch was powered by the water pump circuit as well, I went back to the drawings, yet again, and this time struck paydirt – a relay that was evidently located under the bed area, behind the back wall of the shower.  An uncomfortable under the bed search for the relay yielded no success, of any kind.  But, later I did recall that while poking around in the wetbay for another mod, I saw something that looked like a 12 volt relay.  I dug out the pictures from that mod, and was able to view the wire identifiers that it was hooked up to.  Checking the drawings again revealed that it was indeed a relay, and for sure was the one I was looking for.  

I waited for a quiet time in the neighbourhood, opened the bathroom door, and very carefully worked the switch around its contact point to see if I could hear the relay operating down there in the wetbay...  Yes!  There was no doubt, the relay was clicking quietly and using about 1.8 amps – that mysterious load that I could not explain earlier.  Ok, so the relay was working, so why had it not allowed power from the tank heater circuit to energize the pads during cold weather?  Well, I guess just because it was “clicking” did not necessarily mean that the contact was allowing the circuit to actually close correctly.  Don’t know.  As described in my “Cold Weather Capability” mod, I removed the access panel to the wetbay, and had a look at the relay.  It was very difficult to remove from its contactor block, but when I finally was able to, noted that one corner of the contact area was all corroded.  Very strange – maybe it got wet in there at one time during manufacture?  At any rate, I cleaned up the contacts as best I could and then seated the relay again on its contactor block.  

After completing this cleanup, I poked around some more in the wetbay and discovered that the output wires from the relay had a connector about 6” downstream -  another potential point of failure.  The connector was by no means “disconnected”, but it seemed to not be on as tight as it should be.  Maybe.  Don’t know.  I wish I had found this sooner, because I could have done a voltage check before cleaning up the relay contacts – and then an after check.  At any rate, I did a power check on the 12 volts leaving the relay and was able to determine that the relay was doing its job when the coach tank heater switch was activated.  Battery voltage was exiting the relay, only when the switch was thrown.

The picture for this circuit was starting to become clearer:

1 – The tank heater switch is powered from the circuit associated with the water pump.  It does not directly turn on the heaters, and the light simply indicates that the switch has changed positions.  The switch operates a relay, located in the wetbay in our View, which in turn closes a contact to allow electricity from the tank heater circuit to flow to the pads.  

2 – The relay uses a little less than 2 amps when it use, whether or not the pads are actually energized.

3 – The wires from the relay to the pads flow through a connector, about 6” downstream.

4 – Because of the thermostats at the heating pads, you can’t test the wiring downstream of the wetbay connector until the pads are cold enough to close the pad contactors.  Checking the voltage at the wetbay connector just tells you the relay has closed.

5 – I assumed that when the thermostats close, and current flows through the pads and then to a coach ground, pulling the tank heater fuse would illuminate the blown fuse light on the panel.  Maybe.  Don't know, but it is logical.

After I put some ice on the pad wiring, or wait until the cool weather, I’ll be able to determine if my problem was a corroded relay, a loose connector, or something else.  If it is the “something else”, I think my only recourse will be to replace the wiring to the pads downstream of the connector.

Back to the ammeter mod this page is supposed to be about.  Now knowing the system has a relay has saved me a bunch of time and trouble.  My old plan of hooking up the ammeter was never going to work, so on to Plan B.

I still would like to put the gauge in the cabinet above the cooktop, so here is what I need to do:

1 – Power the gauge from the output of the relay, so the voltage will show up on the gauge only when the switch is thrown and the relay tries to send power to the pads.  Doing it this way will always confirm if the relay has worked.  I’ll need to splice into the relay output downstream of the connector, and send the wire out of the wetbay via the hole in the floor under the shower, under the bed, up to the top of the fridge, and then into the cooktop cabinet to be connected to the gauge.  Let's call this Wire #1.

2 – Take the ground exiting the pads, sever its return path through the wetbay connector, splice it to a new grounding wire, have it follow the same path as the power wire described above, and connect it to the gauge.  Let' call this Wire #2.

3 – Take another new grounding wire from the remaining post on the gauge, send it out of the cabinet to the top of the fridge, down the back, into the Truma box, and then hook it up to the grounding post on the back of the fuse box.  Wire #3.

Doing all of this really only leaves the wetbay connector performing one job – creating a disconnect for the power coming out of the relay – so I might just get rid of it completely and save some confusion that I might face one day when I can’t remember how I did all of this...

The vendor I purchased my ammeter from did not provide any instructions, but I found the info I needed on another vendor’s advertisement of the same type of product.  Here is an illustration of how the ammeter gets connected:

<img src="/assets/webammeterdiagram.jpg"/>

The left hand bronze terminal takes Wire #1 from the output of the relay down in the wetbay, the middle silver terminal takes the new ground Wire #2 from the heating pads, and the right hand silver terminal takes the new ground Wire #3 that goes down to the grounding post on the fuse box.  

(I checked to see if this thing was going to work by hooking up a test 12 volt light bulb circuit in the basement, and am happy to say that it correctly showed a voltage and an appropriate load.)

Here is a wireing diagram of what I think I will end up with - I left out all of the irrelevant ground wires, and concentrated just on the new wires I will need to add:

<img src="/assets/webammeterdiagramV5.jpg"/>

The web reports that these Therma Heat holding tank heater pad thermostats close their contactor at a temperature of 45 degrees F (7 degrees C) as things cool, and have a turn off temperature of 67 degrees F (19 degrees C) as things warm.  As I mentioned before, my assumption in all of this has been that I have a wiring issue, and not a problem associated with these two thermostats.

So, that is where I am as of July 2022.  Hopefully I will be able to continue my tank heater troubleshooting at some point soon.  

<br>

[Back to Our RV Modifications](/ourmods/)
