---
layout: page
title: RV Tank Heater Retrofit | RV Mods
permalink: /ourmods/tankheaters/
---
<h3>Troubleshooting the Factory Snag</h3>

Have you found this page because your tank heaters are suspect, and you want to replace them?  You have come to the right place!  It took me three years and a lot of frustration to get some heat on our tanks, so read on if you want some help troubleshooting, or just want to see what someone else did to get new heat pads on the Grey and Black tanks of a Winnebago View / Navion.

During some past late December dry camping, we needed the protection from the Winnebago installed holding tank heaters.  When I turned them on and watched my Victron app to take note of the amperage change, I noted that they were only pulling between 1 and 2 amps.  Those heaters are supposed to pull about 5 amps each at temperatures below 45 degrees F, so I suspected we had a problem.  Doing a tactile check on the pads confirmed my suspicions, as I could not detect any heat on the pads anywhere.  I can’t say that they have ever worked – the only other time I used them we were popping up above freezing during the daytime hours, so the risk to the tanks was low - but thinking about it later, the current draw at that time was less than two amps as well.   

At the time I checked the wiring where I could – voltage leaving the fuse box, voltage at the switch, voltage out of the switch - I also did a half-hearted search for the ground wire on the fuse box -  but no luck with anything  – so basically I gave up and assumed the problem was wiring related downstream of the switch, or somewhere that I never would have been able to find.  I started going on the assumption that I would have to run new wires from the heating pads, to ensure that I understood where everything was directed.  (The possibility of a double pad failure never crossed my mind.)

My thinking then turned to a way to make darn sure these things were working in cold conditions when I flicked the switch to ON.  Currently, the light in the switch only confirms that the switch has changed positions; it does not confirm that current is actually going to the heating pads.  So how about adding an ammeter to the circuit so I could see the 10 amps that is supposed to register?  As a result of that thought - independent of trying to get our tank heaters to work, I added an ammeter to the panel where the tank heat switch is located.  The mod went well, but unfortunately it absolutely confirmed that the tank heaters were inoperative.  If interested, you can see the tank heater ammeter mod here:

<a href = "https://our2020view.ca/ourmods/ammeter/ " target="_blank">Tank Heater Ammeter Mod </a>

Subsequent troubleshooting of my basic heater problem produced discouraging results, so I queried the Winnie Owner’s Forum to see if someone else had seen this problem before.  It turns out that someone else had indeed seen it, but in a 2015 Trend.  Following the thread, I was able to pick up on some really valuable thoughts that helped me quite a bit.

The Trend owner had determined that the tank heater switch was powered by the water pump circuit, of all things.  And, with the switch on, pulling the 15 amp fuse for the tank heaters had no effect on the light in the switch, or the blown fuse indication on the fuse panel.  With this in mind, one of the commenters wondered if there was a relay that was worked by the switch, allowing power to the tank heaters when closed.  A relay that allows another circuit to power the heating pads?  Interesting thought...

After confirming that my switch was powered by the water pump circuit as well, I went back to the drawings, yet again, and this time struck pay dirt – a relay that was evidently located under the bed area, behind the back wall of the shower.  An uncomfortable under the bed search for the relay yielded no success, of any kind.  But, later, I did recall that while poking around in the wet bay for another mod, I saw something that looked like a 12 volt relay.  I dug out the pictures from that mod, and was able to view the wire identifiers that it was hooked up to.  Checking the drawings again revealed that it was indeed a relay, and for sure was the one I was looking for.  

I waited for a quiet time in the neighbourhood, opened the bathroom door, and very carefully worked the switch around its contact point to see if I could hear the relay operating down there in the wet bay...  Yes!  There was no doubt, the relay was clicking quietly and using about 1.8 amps – that mysterious load that I could not explain earlier.  Ok, so the relay was working, so why had it not allowed power from the tank heater circuit to energize the pads during cold weather?  Well, I guess just because it was “clicking” did not necessarily mean that the contact was allowing the circuit to actually close correctly.  Don’t know.  Using the process described in my “Cold Weather Capability” mod, I removed the access panel to the wetbay, and had a look at the relay.  It was very difficult to remove from its contactor block, but when I finally was able to, noted that one corner of the contact area was badly corroded.  Very strange – maybe it got wet in there at one time during manufacture?  At any rate, I cleaned up the contacts as best I could and then seated the relay again on its contactor block.  

After completing this cleanup, I poked around some more in the wet bay and discovered that the output wires from the relay had a connector about 6” downstream -  another potential point of failure.  The connector was by no means “disconnected”, but it seemed to not be on as tight as it should be.  Maybe.  Don’t know.  I wish I had found this sooner, because I could have done a voltage check before cleaning up the relay contacts – and then an after check.  At any rate, I did a power check on the 12 volts leaving the relay and was able to determine that the relay was doing its job when the coach tank heater switch was activated.  Battery voltage was exiting the relay, only when the switch was thrown.  Unfortunately, until it got cold outside, that was about all I could do in the troubleshooting department.

Later in the year, when overnight temperatures started dropping below freezing, I started into the mod described above and took the opportunity to isolate the heating pads from the Winnebago factory wiring.  With only power and ground wires to the pads remaining, I put 12 volts and a multimeter on them each in turn, and discovered that at temperatures below the “turn ON” temperature of 45 degrees F ... they were only pulling .6 amps each.  Yup, the pads were not working.  So 1.2 amps for the pads, plus about .5 amps to power the relay – was that the phantom 1.8 amps that I would see on my Victron App in the dead of winter when I tried to get the heaters working?  Very likely.

As mentioned above, once the mod was in place, the new ammeter confirmed what I had found earlier by testing the pads independently; the total draw was only 1.2 amps instead of around the expected 9 or 10 amps.  That is the beauty of an ammeter tieds exclusively to this circuit - there are no mistakes to be made when reading the load - what you see is what you are getting through the pads.

So, looking on the bright side, at least I had discovered what I needed to do to get some heat on the tanks:  replace both pads.  Both pads?  How is that possible that both pads had never worked?  I certainly did not see that one coming either, but have a look at this post from an RV forum on the topic of our specific tank heaters made by ThermaHeat:

From a Forum - <i>I thought I'd post my results in case anyone else needs this information. I have ThermaHeat tank heaters. (Reportedly the same heaters are marketed under some other names as well).  They are rated to draw 4.8 amps and my tests show they draw within .15 amps of that value.  It turns out that assuming the thermostat has activated the heater (in otherwards it's cold enough to turn the heater on) you *can* feel some warmth by placing your hand on the heater (it's not dramatic but definitely noticeable). The other test is to run the heater with antifreeze and measure the temperature. It should be between 45 and 67 degrees F when it's cold out. You should also see a current draw of around 4.8 amps when the heater is running.  What happened in my case is that there was a wiring error and secondly my dealer had a bad batch of heaters. The thermostats were defective in this batch. They replaced all three tank heaters and they still didn't work. They ultimately had to get a new batch of heaters.  It took four visits to finally get things right.  I did get a free wash of the trailer for my trouble.</i>

So, we had two pads that left the factory inoperative.  Ok, how about I just go to the dealer and order a couple more?  I mean, what is the probability of getting another two that did not work either?  Well,  based on the above post from a forum, maybe the probability was higher than I wanted to believe?

<h3>The Installation</h3>

1 - The heat pads that came with our View were made by Thermaheat, a Lasalle Bristol company.  These are the pads that are pretty common on the web, and the least expensive.    They are theoretically rated at 78 Watts, about 5.8 amps at 13.5 volts, and should have a resistance of about 2.3 ohms.  (The numbers were important to me, as I wanted to test any replacements I got, BEFORE I installed them on the motorhome.)  These factory installed pads measured 25" long by 7.25" wide, and were factory installed with the end of the pads folded up the ends of the tanks.

I special ordered two Thermaheat pads from our Winnebago dealer, with the agreement that I could return them if they did not work.  They were shipped directly from the Winnebago factory, so I'm led to believe that these would have ended up on a production motorhome if we had not diverted them from their parts inventory.  

And, upon testing them down in the basement ... they didn't work...  

Great, just great.

To come to this realization, here is what I did:

- Knowing they have a built in thermastat that will only close and allow current to flow if below 45 degrees F, I checked the resistance while the pads were warm.  They correctly showed infinite resistance, or no continuity.  This can easily be tested with a multimeter set to the continuity test function, and the probes on both leads.
- Next I put both pads in the freezer, waited for them to drop in temperature, and then did a continuity test again.  One of the pads now correctly registered continuity, a little less than 3 ohms, but the other pad continued to show infinite resistance - the built in thermastat would not close to allow electricity to flow through the pad, no matter how long I left it in the freezer.
- With the possiblity of one good pad, I left that pad in the freezer, hooked up a 12 volt power supply (12.4 volts) and rigged my test setup to measure current.  It showed a current draw of about 4.5 amps - a bit less than the rated current - but it was working ... so far so good.
- I used a infrared digital thermometer to indeed confirm the pad was warming.

And then, after a few hours in the freezer, the pad failed.  I don't know if it was the themastat that failed, or the heating mesh failed somewhere, but that pad was now dead as well.  I checked the resistance and confirmed that it was inoperative.

Ok, back to the dealer to return both pads, and move on to Plan B.

Plan B was to order the expensive heat pads from UltraHeat of Elkhart, Indiana.  They did not have a product that matched the specs of the factory heating pads - the best match was a 12" by 7.25" pad rated at only 55 Watts (compared to the 78 Watt pads that came from the factory).  The next size up would have fit the footprint of our black tank, but would have been too large for our grey tank.  And those pads were rated at just under 10 amps each, so the combination of the two would have overwhelmed the 15 amp wiring that came on our View.  

We have previous good experience with the UltraHeat products, having installed gate valve heat pads on our dump valves.  

Link to Winter Capability

Knowing that the Ultraheat pads were only rated to keep 25 gallons of water warm, not the 41 gallons that our tanks can hold, I ordered two of the 55 Watt pads intending to limit the volume we would fill the grey and black tanks to.  I thought this was a good compromise for the few times a year we would really need the heat protection. 

<img src="/assets/webtankheaters1.jpg"/>

The model number of the pads we ordered are AMM900, and can be found at this link:

Link to Pads

The pads arrived super quick from Ultraheat, but testing showed both of the pads were only making about 50% power. I reached out to UltraHeat, and they explained that the power would increase a bit after initial use - but they were not confident that the pads would meet the numbers they advertise - so they shipped two more pads to us as replacements.  The two new pads were much better, and tested satisfactorily - not the 62 Watts they advertise - but closer ...

I cut a piece of cardboard to match the heat pad size, and started experimenting with potential locations for the new pads.  I quickly realized that there was enough room on the black tank for two of these pads, and possibly room on the grey tank for two pads, if I got creative.  Why not use the first two (low power) pads as well, in an attempt to get closer to the power rating that Winnebago claims their factory pads produce?

After cleaning up the tank bottoms with cleaner and a 50/50 mix of rubbing alcohol and water, the pads installed easily on each tank.  The wiring was equally straightforward - remembering to wire these in parallel.

Here is a picture of a low power and a high power pad mounted to the black tank:

<img src="/assets/webtankheaters2.jpg"/>

2 - Knowing that our original two, defective, factory pads got pretty beat up from road debris, I thought this time I would come up with some way to protect the pads and wiring.  My idea was to cover the bottom of the tanks with some polyethylene tarp, and maybe add some cushioning / insulation in their as well.  I cleaned off the tank edges and ran some adhesive velcro strips along the sides of the tanks, cut some tarp, added some velcro, cut some old insulation I had in the basement, and fitted the covers to the tanks.  The covers look good, and I think will hold up well.  I worried about water intrusion under the cover to soak the insulation, so added some Gorilla Tape to the perimeter of the tarp.  After the addition of the tape the job did not look as clean, but hopefully it will be functional.

Here is one of the cut tarps and insulation:

<img src="/assets/webtankheaters3.jpg"/>

Here is the grey tank before I decided to add some tape:

<img src="/assets/webtankheaters4.jpg"/>

and here is the grey tank with the tape added, for belt and braces:

<img src="/assets/webtankheaters5.jpg"/>

NOTE - On our View / Navion 24J, the panel that protects the black tank can be opened up.  There are some sheet metal screws down at the bottom of the frame, and once removed, the panel hinges up to allow access to the black tank:

<img src="/assets/webtankheaters6.jpg"/>

3 - Testing the pads one last time - just to make sure they installed with no damage?  Before I buttoned up the covers for good, I took advantage of the just installed velcro strips on the edges of the tank to support a bag of frozen berries positioned over the pad thermastats.  (I put the bag on a wooden board, and strapped the board to the bottom of the tank.)  It took about five minutes, but I did get the thermostats to close and register current when the in-coach tank heater switch was thrown.  I had initially tried a block of ice on the thermastats, but was only successful on two of the the four pads.  This method was successful on the other two pads.

4 - Once we had settled in to some cool fall weather, turning on the tank heater switch as outside temperatures approached freezing showed that current was flowing to all of the pads:

<img src="/assets/webammeter17a.jpg"/>

After three years of frustration, we finally have heat on our tanks.  









