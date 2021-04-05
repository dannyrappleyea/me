# Electric motor bike upgrade
I have an older Cannondale commuter bike that I wanted to upgrade to electric, so installed a Tongsheng TSDZ2 motor. It's a sweet setup that's a lot of fun to ride. But its definitely an involved DIY project, that took a **lot** of research to figure everything out. There's a lot of confusing information out there, so adding my own install notes.

![Cannondale Bike](https://raw.githubusercontent.com/dannyrappleyea/me/main/biking/cannondale_tongsheng_upgrade.png)

## My bike
* Older Cannondale commuter
* 67mm wide bottom bracket
* Rim brakes
* Shifter cables running outside the frame

## Settled on the Tongsheng TSDZ2 motor. Why?
It really came down to the Bafang BBS02 and Tongsheng TSDZ2. The Bafang seems more powerful, and more hackable, but uses cadence to activate. The Tongsheng has a torque sensor, so the harder you pedal, the more it contributes.
* Thought that the torque sensors would give a more integrated feeling when riding
* Can push it right to the limits of street legal
* Can replace the firmware with an open-source version

## Purchased from Eco Cycles.
* Wanted a US-based company that I could get support from
* Could order everything in one kit that would work together
* Their "build your own" option is super customizable.
* They pre-install the open-source software, and apparently contribute heavily to the source

[Build Your TSDZ2 Kit w/ 850C - Torque Sensing Pedal Assist, E-brakes,  – Eco Cycles](https://www.eco-ebike.com/collections/tongsheng-tsdz2/products/tsdz2-w-850c-torque-sensing-pedal-assist-with-throttle-and-e-brakes-36v-48v-52v-10-18a-250-750w)

# Specs
Mostly their defaults, with a larger battery for some distance rides.

* Motor: 48V
* Cranks: 170mm
* Bottom Bracket: 68-73mm
* Gear: plastic
* Chain Ring: 42T w/guard
* Wiring Harness: 1T4 wiring harness
* Throttle: Universal thumb throttle
* E-brakes: Mechanical e-brake levers
* Gear shifting sensor, w/splitter cable
* Dual front/rear lights, with wiring harness
* 52v 15ah 21700 Cell Hailong Shark Battery
* Open-source firmware, with programming cables

## Battery
More details about the battery.
* 52v 15ah 21700 Cell Hailong Shark Battery - [52v 15ah 21700 Cell Hailong Shark Battery](https://www.eco-ebike.com/collections/52v/products/52v-15ah-21700-cell-hailong-shark-battery)
* Capacity: 52v (58.8v Fully Charged) 15ah
* Cells: Samsung 50E 21700 5000mAh
* Cycle Life: 500-1500+ Cycles @ =/> 80%
* Output: 40a Continuous Discharge (30a Recommended)
* Input: 5a Charging Max
* Low Voltage Cutoff: 42v
* Approx 775 watt hours (average 20-25 watt hours per mile). 35-70 miles range

Apparently, you have to become battery knowledgable to make the most of it. You don't want to keep the battery near 100% or 0% for long periods of time, somewhere between 20-80% is best.

# Installation
## What I should have done
Pull out the motor, battery, display, and control from the box. Connect them on the floor, with a crank arm. Turn it all on and test it.

## What I did
Stripped the bike down to the frame, spending a couple of weeks ordering bike tools I didn't know I needed. Then install it, only to spend an evening thinking I had a defective unit until I figured out how to turn it on.

## Essential tools
I had a decent bike maintenance setup already, with a repair stand and basic tools. I'd never upgraded anything so needed more tools.

* Park Tool CWP-7 crank arm puller
* Hex wrenches going up to 8mm

## Stripping the bike
A mid-engine setup replaces the front derailleur, so removed that, along with the shifter and cable. It also replaces both brake levers, so removed those. Ended up removing the other shifter cable, and the plastic guide running under the bottom bracket. Removed the chain. Gave everything a good cleaning while I was there.

Removing the pedals, crank arms, and bottom bracket was a pain, cause I didn't have the tools. And I didn't know which tool I needed to pull the crank arms off. The Park Tools videos were awesome.

[Bottom Bracket Identification | Park Tool](https://www.parktool.com/blog/repair-help/bottom-bracket-identification)
[Bottom Bracket Removal & Installation: Threaded | Park Tool](https://www.parktool.com/blog/repair-help/bottom-bracket-removal-installation-threaded)

Finally, the kickstand had to go. The motor bolts onto the same middle bracket.

## Motor installation
The installation video was really helpful. And in Chinese. The kit did come with the bracket wrench needed to install.

[PRODUCT DOCUMENTATION – Eco Cycles](https://www.eco-ebike.com/pages/product-documentation)

I found a couple of other install links useful.

[Manuals & Resources - ELECTRIFY BIKE](https://www.electrifybike.com/manuals--resources.html#/)
[Woosh Bikes TSDZ2](https://wooshbikes.co.uk/manuals/TSDZ2.pdf)

## Battery installation
The instructions say to mount the battery in place of the water bottle holder. They lie. With both screws in the battery bracket, the battery wont fit. Luckily, I found an offset bracket that let me mount the battery a bit higher up.

[Wolf Tooth Components B-RAD Mounting Base](https://www.amazon.com/gp/product/B072B5PCBD)

It's not quite rated for the weight of the battery, but seems sturdy enough.

## Wiring Madness
The kit came with a lot of bits, and not much in the way of diagrams to wire them together. Here's what I did.

**Motor**
Has three cables coming out of it.
* to battery
* to rear wheel speed sensor
* to wiring harness

**Wiring harness**
I got the 1T4 cable. The 8-pin male connector goes to the motor. The other end with the 4 connectors go to:
* display (green connector)
* throttle
* brakes (two of them)

**Display**
The display connects to the wiring harness. It has another cable attached to the control buttons. Here are additional instructions for it - [Electrify Bike Co - 860C Color Display.pdf - Google Drive](https://drive.google.com/file/d/1zIkfFbZH36qo_IrlViii-pctT56pYOFj/view)

**Cadence sensor**
This was a Y-splitter as well. The attached wire at one end goes to the cadence sensor magnet on the rear wheel. The connectors go to:
* the motor wire
* long splitter cable powering the front and rear lights

**Gear sensor**
I haven't installed this yet, but it looks like you put a splitter on one of the brake cables, to the brakes, and the gear sensor.

All the connectors have interlocking rubber gaskets that seem water resistant.

## Brake levers
These looked the same as my old ones, but with a sensor built in to turn off the motor when braking. Connected the sensor to the wiring harness. The brake cable attaches the same way. Tested, and the motor turns off when either brake is pressed.

# Riding it
## Powering it on
After installing everything, it did exactly nothing. No sign of life. Cranking the pedals did nothing. Thought I had a bum unit.

No. You have to turn on the display for it to do anything, using the power button on the display controls. In hindsight, *Duh*.

At assist level 0, the motor doesn't activate. But bump it to level 1 or higher, crank the pedals, and the motor hummed to life. Woot!

## Test ride
Upgrading a bike in the dead of winter with days of almost-freezing rain was probably not the smartest move. But who cares. Had to try it anyway.

At level 1 assist, it almost imperceptibly helped out. Basically, it offsets the added weight everything adds, and feels about like riding the bike before I installed anything.

At the max level 20 assist, feel like the [Six Million Dollar Man |YouTube](https://www.youtube.com/watch?v=0CPJ-AbCsT8) with bionic legs. Even on a straight, flat road, could reach speeds I'd only gotten on long downhills before. Pretty incredible.

The motor does add noise, though it's far louder on the repair stand than out actually riding it. More like a low hum than anything annoying. That's one of the reasons I stayed with the plastic gear, reading online that the sturdier metal replacement is louder.

## Tuning
The default settings in the open-source firmware are metric measurements, and very conservative on battery power. I went into the settings on the display to tune these.

[Features and configurations on display · OpenSourceEBike/TSDZ2_wiki Wiki · GitHub](https://github.com/OpenSourceEBike/TSDZ2_wiki/wiki/Features-and-configurations-on-display)

Wheel circumference: 86.5" or 2197.1mm (in 10mm increments so 2200mm)
Units: Imperial
Max current: 16 amp
Motor max current: 16 amp

The TSDZ2 seems to have a maximum 18amp power draw. The battery can provide 40amp max, 30amps recommended. The firmware was set to 10 amps. Bumped it to 16, and might take it to 18 later on.

## Accessories
The motor and battery take away the kickstand and water bottle holder, so I had to order new ones that attached to alternate locations.

[BV Alloy Adjustable Height Rear Side Bicycle Kick Stand](https://www.amazon.com/gp/product/B00LNM79CQ)
[TwoFish Quick Cage Adapter](https://www.amazon.com/gp/product/B003RLJ8L6)

## Riding until battery depleted
I had three beautiful rides, then the battery gave out on the fourth (at the bottom of a massive hill, of course). The display had shown the battery levels going down over the rides, but seemed to hang at 65% on the third and fourth rides. Was still there when it gave out. Guessing the display doesn't have the right settings for the battery somewhere.

I measured the battery at ~43V. Settings cutoff is 42V to protect the battery from over-discharging. Think I had initially charged the battery to 80-90%. That got me 27-28 miles, right inline with the estimated 35 miles. When I recharged, the charger was set to 90%, which translates to 52V. Gonna try going to 100% charge right before the next ride (which should take the battery to 58V).
