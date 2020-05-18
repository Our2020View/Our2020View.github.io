---
layout: page
title: Electrical
permalink: /ourmods/electrical/
---

<h1>Electrical System Highlights of the “Stock” 2020 View</h1>

First, let’s talk about what came out of the factory.  For the 2020 model year on the View / Navion, Winnebago made some significant electrical changes as a result of their LifePO4 option, requests from Mercedes Benz, and the feedback from owners.  After weighing the additions and deletions, I believe the changes enhance the capability of the motor home tremendously:

1 – Alternator charging of the house batteries – According to Winnebago, knowing that the introduction of the LifePO4 option created the potential for significant higher charging currents that could affect the temperature and life of the chassis alternator, Mercedes requested that a current limited electronic charge relay be added to the alternator charging circuit.  Winnebago complied.

[Mastervolt Charge Mate Pro 40 current limited charge relay](https://www.mastervolt.com/products/charge-mate-to-connect-two-batteries/charge-mate-pro-40/)

This charge relay replaced the “booster solenoid” that Winnebago has used in the View / Navion for many years.  Similar to the legacy solenoid found under the co-pilot’s seat, not only does the new charge relay allow charging of the house batteries when the alternator is outputting appropriate voltage, and provides chassis battery isolation during coach battery discharging, it limits the charging current to 40 amps; well within the long life requirements of the Mercedes alternator.  The legacy booster solenoid does not provide this type of protection.  

The option to be able to connect the house batteries to the chassis battery is no longer available, another request from Mercedes Benz.  However, after reading the brochure found at a link on this page, you will note that the Charge Mate Pro does have this capability built in.  Over to you if you want to rig something up to be able to manually close the isolator to allow the house batteries to be used to boost the chassis battery.  Winnebago requests that this capability not be used.  The topic of a chassis battery maintainer is discussed later...

2 – LifePO4 option for house batteries – We chose not to take the lithium option out of the factory, instead opting to save some money and have some fun installing the batteries ourselves.  But, even though you can choose to do the upgrade on your own, there does not appear to be any penalties associated with this choice.  Winnebago has made the upgrade very simple.  They have taken care of the potential for alternator damage with the Charge Mate Pro 40, the Zamp solar charger has a Lithium chemistry selection, and the new Xanrek Freedom XC inverter / charger also has a Lithium chemistry selection.  The only thing missing in the Winnebago gear is a battery monitor system that provides a quality battery state of charge reading, as opposed to just a battery voltage reading.  The topic of a good battery monitor is discussed later...

3 – Xantrex Freedom XC 2000 – The increased power capacity of this new inverter has allowed Winnebago to connect all the household 120V outlets to the inverter, including the microwave oven outlet.  This was a huge benefit to us, as in all of our previous coaches we have had to start the Onan genset to be able to run the microwave while in parking lots, rest stops, or while tucked away on a lakeside tent site at a provincial or state park.  Starting the Onan to heat up some water for a tea or coffee just did not make sense to us.

Also, as mentioned earlier, the fact that the out-of-the factory inverter / charger is Lithium capable makes an in the field battery upgrade pretty easy, and takes away the potential downsides of not charging the batteries to their full capacity.

4 – Automatic Transfer Switch – This was a surprise to us, when we started researching late model Views and Navions.  We had no idea that this functionality was not standard, until the 2020 model year.  Now that it is included as standard on the 2020 models, we will not have to worry about leaving the coach to plug in the shore power chord to the generator outlet located in a locker at the rear of the motor home.  We have never had to do that before, so are happy to be not starting!

5 – Roof Access Port – Now, this is another great idea.  Gone are the days when I had to get creative to figure out how to get the cellular booster antenna cable from the roof to the inside of the coach.  At this point I don’t believe we will be hooking anything else up there, but if we do, it will be equally easy to accomplish.  (See the dedicated mod description of what we did to get the magnetic antenna to stay on our non-metallic roof.)

<h1>Electrical Mods</h1>

Battery Maintainer – Our previous coaches had the capability to trickle charge the coach battery from the house battery charging system.  This was one of those “no brainers” that we took for granted on our Class B Sprinter.  If there was solar feeding the coach batteries, there was solar floating the chassis battery as well.

I was very surprised to learn that View owners had to resort to aftermarket solutions to deal with chassis batteries that would drain during extended periods of storage.  While there are a number of options out there, YouTube convinced me that the Trik – L – Start product from LSL Products of San Antonio, Texas, was a pretty simple and reliable choice.  It was by far the preferred choice for owners of all types of lead acid batteries, but I did not see much info on what owners of Lithium batteries had done when making their choice.

After some research on the LSL website, I noted that their big brother product, the Amp – L – Start had a dedicated setting for Lithium batteries, and has voltage control points that are considerably different from the Trik – L – Start.  I contacted the company, and had a really thorough and productive email exchange with the General Manager.  Here is what I learnt about how Lithium batteries co-exist with their chassis battery maintenance products:

 - The Trik – L – Start will work with Lithium coach batteries, but unfortunately will continuously provide current to the chassis battery until the coach batteries are less than 20 % state of charge.  Because the Trik – L – Start is programmed for a lead acid chemistry, and wants to disconnect from the chassis battery when the coach battery is observed not to be charging, the Trik – L – Start waits for the coach battery to drop to a voltage close to what it thinks should be an appropriate resting voltage.  A voltage close to a resting voltage on a lead acid battery is actually less than 20% state of charge on a lithium battery.  Essentially, the Trik – L – Start remains engaged for almost a full discharge cycle of the Lithium coach battery.  If you have a Trik – L – Start hooked up with Lithium coach batteries, you are not obtaining all the performance you have signed up for with your LifePO4 batteries.  

   The amount of coach battery discharge will depend on the health of your chassis battery; a healthy chassis battery that is content to sit at its resting voltage with little help from the Trik – L – Start will not cause an excessive coach battery drain.  But an unhealthy chassis battery will gladly accept help from the Lithium coach batteries until they have less than 20% state of charge remaining.

   The actual numbers for the Trik – L – Start are: active at 13.0 volts, and inactive at 12.8 volts.  A 13.0 volt engage setting will mean that the Trik – L – Start incorrectly assumes a charge on the Lithium coach battery is occurring, and becomes eager to pass current to the chassis battery.  When the 12.8 volt disengage setting is reached in the Trik – L – Start, your Lithium battery will be at approximately a 17% state of charge, having been attempting to pass current to your chassis battery for almost the full duration of the Lithium batteries’ discharge cycle. 

•	The Amp – L – Start, on the other hand, has a user pin programmable configuration that caters to the relatively high operating voltages of a Lithium battery.  This option is standard on the G2 and later versions, of the product.  The voltage control points are set to ensure that the Amp – L – Start only connects to the chassis battery when the Lithium coach batteries are truly charging or floating, and disconnects quickly once it is recognized that no charging or floating is present and the Lithium battery is undergoing a discharge cycle. The Amp – L – Start engaged voltage is 13.45 volts, which is slightly higher than its resting voltage.  It becomes disengaged at 13.35 volts, ensuring that the Lithium battery is very close to having its entire capacity available to the coach loads only.

The drawbacks to having to buy an Amp – L – Start instead of a Trik – L – Start?

•	It is slightly more expensive.
•	You have to supply your own connection wires – The Amp – L – Start is designed to supply more current to your chassis battery, if required.  As a result, the wire needs to be at least 12 gauge (10 gauge for long wire runs) which will carry three time the current the thin gauge wires attached to the Trik – L – Start are rated to carry.
•	The Lithium configuration pin strap and connection terminals are exposed to the environment, while the Trik – L – Start has all of its components fully sealed in its resin block.  (Not a big deal, really, everything under the co-pilot’s seat is exposed anyway)

Advantages to buying an Amp – L – Start?

•	If you have not yet decided to go Lithium, you can simply configure the pin strap to allow the Amp – L – Start to be compatible with lead acid chemistry.  Once you have sprung for Lithium, change the pin strap and you are all set for LifePO4.
•	If you have lead acid coach batteries in combination with a temperature compensated house battery charger, the Amp – L – Start also allows a pin configuration that will optimize the control voltages taking into account temperature compensation.

I don’t expect to require the increased current capability of the Amp – L – Start during its chassis battery maintenance function, so it will be overkill for this role in our View.  But, the capability to function optimally with Lithium batteries makes it worth the few extra dollars for us.

Details of the mod are below:
