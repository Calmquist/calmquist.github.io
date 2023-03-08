---
title: "Fudge Psi-Wars: Vehicle Weapon Scale, Part 1"
date: 2023-03-08
tags:
- psi-wars
- fudge
---

This post contains some mechanically computed values based on stat blocks and formula and a simple weapon vs ship analysis.

Below is a table containing those values:

|Vehicle|Weapon|Size Scale|Mass Scale|GURPS Damage|Fudge ODF (1d = +1 ODF)|Fudge ODF (Fudge THS Conversion)|Fudge THS Armor Penetration|GURPS DR|Fudge DDF (THS)|GURPS Force Screen DR|Fudge Force Screen DDF (THS)|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|
|Trader Combat Drone| |1|6| | | | |15|5| | |
| |Fighter-scale Muonic Cannons|2| |3dx5(10) burn|15|8|-6| | | | |
| |Particle Cannon|2| |6dx15(15) burn|90|13|-8| | | | |
| |Isomeric Warhead|6| |6dx250 cr ex|1500|20|0| | | | |
|Switchback| |1|4| | | | |60|9| | |
| |Semiportable Plasma Gatling|0| |5dx4 (2) burn ex|20|9|-2| | | | |
|Compact Repulsor Car| |2|5| | | | |15|5| | |
|Repulsor Sedan| |2|5| | | | |15|5| | |
|Sports Repulsor Car| |2|5| | | | |10|4| | |
|Utility Repulsorcraft| |2|7| | | | |20|6| | |
|Behemoth| |5|23| | | | |3000/1500|19/17| | |
| |Orbital Cannon| | |6dx60 (5) pi inc|360|17|-4| | | | |
| |Blaster Cannon| | |3dx25 (5) pi inc|75|13|-4| | | | |
| |Gatling Blaster|2| |6dx5 (5) pi inc|30|10|-4| | | | |
|Demolisher| |2|12| | | | |3000/1000|19/16| | |
| |Semiportable Flamer|0| |6dx3 burn|18|9| | | | | |
| |Safilore Blaster Repeater|0| |9d (5) pi inc|9|7|-4| | | | |
| |Quad Repeater Cannon| | |6dx5 (5) pi inc|30|10|-4| | | | |
|Wolfhound| |2|6| | | | |150/60|11/9| | |
| |Semiportable Plasma Gatling|0| |5dx4 (2) burn ex|20|9|-2| | | | |
|Banshee| |1|3| | | | |200/50|12/8| | |
| |Semiportable Blaster Autocannon|0| |6dx2 (5) pi inc|12|8|-4| | | | |
| |64mm Plasma Lance Missile|4| |6dx15 (10) burn|90|13|-6| | | | |
| |64mm Plasma Missile|4| |6dx7 burn ex|42|11|0| | | | |
|Reaver| |3|11| | | | |300/100|13/10| | |
| |Quad Repeater Cannon| | |6dx4 (5) pi inc|24|10|-4| | | | |
| |160mm Plasma Lance Missile| | |6dx30 (10) burn|180|15|-6| | | | |
| |160mm Plasma Missile| | |6dx15 burn ex|90|13| | | | | |
|Drifter| |2|9| | | | |15|5| | |
| |BAN-6 Plasma Cannon|4| |5dx20 (2) burn ex|100|13|-2| | | | |
| |SC4-TR Plasma Gatling|2| |6dx8 (2) burn ex|48|11|-2| | | | |
| |ZIP-3R Light Blaster Gatling|2| |6dx4 (3) burn ex|24|10|-3| | | | |
| |100mm Plasma Lance Missile|4| |6dx20 (10) burn|120|14|-8| | | | |
| |100mm Plasma Missile|4| |6dx10 burn ex|60|12|0| | | | |
|Grappler| |3|12| | | | |100/50|10/8| | |
| |SC4-TR Plasma Gatling| | |6dx8 (2) burn ex|48|11|-2| | | | |
|Flanker| |3|11| | | | |50|8|100|10|
| |Gatling Blaster|2| |6dx5 (5) pi inc|30|10|-4| | | | |
| |160mm Plasma Lance Missile|4| |6dx30 (10) burn|180|15|-6| | | | |
| |160mm Plasma Missile|4| |6dx15 burn ex|90|13| | | | | |
|Hammerhead| |2|11| | | | |500/100|14/10| | |
| |Quad Repeater Cannon|2| |6dx4 (5) pi inc|24|10|-4| | | | |
| |400mm Internal Torpedo|N/A| |5dx200 cr ex|1000|19| | | | | |
|Hornet| |2|10| | | | |10|4|150|11|
| |Fighter-scale Muonic Cannons|2| |3dx5(10) burn|15|8|-6| | | | |
| |Particle Cannon|2| |6dx15(15) burn|90|13|-8| | | | |
|Javelin| |2|9| | | | |15|5| | |
| |Imperial Fighter Blaster|2| |6dx5 (5) burn|30|10|-4| | | | |
|Peltast| |2|9| | | | |15|5| | |
| |Imperial Fighter Blaster|2| |6dx5 (5) burn|30|10|-4| | | | |
| |160mm Plasma Lance Missile|4| |6dx30 (10) burn|180|15|-6| | | | |
| |160mm Plasma Missile|4| |6dx15 burn ex|90|13| | | | | |
| |400mm Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
|Piranha| |2|10| | | | |50/25|8/6| | |
| |Quad Repeater Cannon|2| |6dx4 (5) pi inc|24|10|-4| | | | |
| |160mm Plasma Lance Missile|4| |6dx30 (10) burn|180|15|-6| | | | |
| |160mm Plasma Missile|4| |6dx15 burn ex|90|13| | | | | |
|Raptor| |3|13| | | | |100/50|10/8|300|13|
| |ARC Gatling Blaster|2| |6dx5 (5) burn|30|10|-4| | | | |
| |160mm Plasma Lance Missile|4| |6dx30 (10) burn|180|15|-6| | | | |
| |160mm Plasma Missile|4| |6dx15 burn ex|90|13| | | | | |
| |400mm Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
|Tempest| |2|10| | | | |10|4|100|10|
| |Imperial Fighter Blaster|2| |6dx5 (5) burn|30|10|-4| | | | |
| |100mm Plasma Lance Missile|4| |6dx20 (10) burn|120|14|-8| | | | |
| |100mm Plasma Missile|4| |6dx10 burn ex|60|12|0| | | | |
|Valkyrie| |2|10| | | | |75|9|300|13|
| |ARC Gatling Blaster|2| |6dx5 (5) burn|30|10|-4| | | | |
| |Lightning Cannon|6| |6dx30 (5) burn sur arc|180|15|-4| | | | |
|Valiant| |3|11| | | | |15|5|200|12|
| |ARC Gatling Blaster|2| |6dx5 (5) burn|30|10|-4| | | | |
| |160mm Plasma Lance Missile|4| |6dx30 (10) burn|180|15|-6| | | | |
| |160mm Plasma Missile|4| |6dx15 burn ex|90|13| | | | | |
| |400mm Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
|Vespa| |2|10| | | | |10|4|150|11|
| |Fighter-scale Blaster Cannons|2| |6dx5 (5) burn|30|10| | | | | |
| |Particle Cannon|2| |6dx15 (15) burn|90|13|-8| | | | |
|Wildcat| |3|12| | | | |50/25|8/6| | |
| |NOV-4 Heavy Plasma Cannon|6| |6dx30 (2) burn ex|180|15|-2| | | | |
| |MIN-3R Mining Laser|6| |5dx15 (10) cut inc|75|13|-6| | | | |
| |SP74-TR Heavy Plasma Gatling|2| |6dx15 (2) burn|90|13|-2| | | | |
| |Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
|Fugitive| |3| | | | | |500|14| | |
| |Quad Repeater Cannon|2| |6dx4 (5) pi inc|24|10|-4| | | | |
|Gypsy Moth| |3| | | | | |50|8|500|14|
| |Fighter-scale Muonic Cannons|2| |3dx5(10) burn|15|8|-6| | | | |
|High Roller| |3| | | | | |500|14|300|13|
| |Fighter Cannon|2| |6dx5 (5) burn|30|10|-4| | | | |
| |Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
|Lancer| |5| | | | | |2500/500|18/14|1000|16|
| |Disruptor Cannon|6| |6dx75 (5) sur|450|17|-4| | | | |
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
|Nomad| |4| | | | | |150/75|11/9|500|14|
| |NOV-4 Heavy Plasma Cannon|4| |6dx30 (2) burn ex|180|15|-2| | | | |
| |MIN-3R Mining Laser|4| |5dx15 (10) cut inc|75|13|-6| | | | |
| |SP74-TR Heavy Plasma Gatling|2| |6dx15 (2) burn|90|13|-2| | | | |
| |Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
|Prestige| |4| | | | | |200|12|100|10|
| |Anti-Personnel Blaster Cannon|0| |10d (5) burn|10|7|-4| | | | |
|Ronin| |3| | | | | |200|12|500|14|
| |Ronin Cannon|2| |6dx5 (5) burn|30|10|-4| | | | |
| |160mm Plasma Lance Missile|4| |6dx30 (10) burn|180|15|-6| | | | |
| |160mm Plasma Missile|4| |6dx15 burn ex|90|13| | | | | |
|Scarab| |5| | | | | |500/200|14/12|1000|16|
| |Corvette Scale Muonic Cannon|4| |6dx20 (10) burn|120|14|-6| | | | |
|Skirmisher| |5| | | | | |500/250|14/12| | |
| |Quad Repeater Cannon|2| |6dx4 (5) pi inc|24|10|-4| | | | |
| |Isomeric Heavy Torpedo|6| |5dx300 cr ex|1500|20| | | | | |
|Tigershark| |5| | | | | |1000/400|16/14|750|15|
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |NOV-4 Heavy Plasma Cannon|4| |6dx30 (2) burn ex|180|15|-2| | | | |
| |MIN-3R Mining Laser|4| |5dx15 (10) cut inc|75|13|-6| | | | |
| |SP74-TR Heavy Plasma Gatling|2| |6dx15 (2) burn|90|13|-2| | | | |
| |Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
|Toad| |5| | | | | |1000/500|16/14| | |
| |Quad Repeater Cannon|2| |6dx4 (5) pi inc|24|10|-4| | | | |
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |Isomeric Torpedo|6| |5dx200 cr ex|1000|19| | | | | |
| |Self-Destruct| | |6dx750 cr ex|4500|23| | | | | |
|Wrangler| |4| | | | | |500|14|250|12|
| |MIN-3R Mining Laser|4| |5dx15 (10) cut inc|75|13|-6| | | | |
| |SP74-TR Heavy Plasma Gatling|2| |6dx15 (2) burn|90|13|-2| | | | |
|Arcana| |7| | | | | |2500|18|10000|22|
| |Capital Scale Cannon|6| |6dx75 (5) burn|450|17|-4| | | | |
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Dominion| |6| | | | | |3000|19|5000|20|
| |Capital Scale Cannon|6| |6dx75 (5) burn|450|17|-4| | | | |
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Executioner| |7| | | | | |4000/2500|20/18|7500|21|
| |Pulsar Super Cannon|6| |6dx600 (3) burn ex|3600|22|-3| | | | |
| |Super Heavy Cannon|6| |6dx120 (5) burn ex|720|18|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Imperator| |8| | | | | |5000/3000|20/19|15000|23|
| |Super Heavy Cannon|6| |6dx120 (5) burn ex|720|18|-4| | | | |
| |Capital Scale Cannon|6| |6dx75 (5) burn|450|17|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Kodiak| |6| | | | | |2000|18|2000|18|
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Legion| |8| | | | | |3000|19|10000|22|
| |Capital Scale Cannon|6| |6dx75 (5) burn|450|17|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Mauler| |7| | | | | |6000/2500|21/18| | |
| |Capital Scale Cannon|6| |6dx75 (5) burn|450|17|-4| | | | |
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |Mauler Beam|6| |5dx100 cr|500|17| | | | | |
|Regal| |6| | | | | |25000|18|4000|20|
| |Capital Scale Cannon|6| |6dx75 (5) burn|450|17|-4| | | | |
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Spire| |6| | | | | |5000/3000|20/19| | |
| |Spire Scale Plasma Cannon|6| |6dx200 (2) burn ex|1200|20|-2| | | | |
| |Corvette Scale Cannon|4| |6dx30 (5) burn|180|15|-4| | | | |
| |Quad Repeater Cannon|2| |6dx4 (5) pi inc|24|10|-4| | | | |
| |Isomeric Heavy Torpedo|6| |5dx300 cr ex|1500|20| | | | | |
|Sword| |7| | | | | |5000/2500|20/18|10000|22|
| |Super Heavy Cannon|6| |6dx120 (5) burn ex|720|18|-4| | | | |
| |Capital Scale Cannon|6| |6dx75 (5) burn|450|17|-4| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Trader Ark| |9| | | | | |5000|20|10000|22|
| |Capital Scale Muonic Cannon|6| |6dx40 (10) burn sur|240|16|-6| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |
|Trader Ark Tender| |8| | | | | |10000|22|20000|24|
| |Spinal Pulsar|6| |6dx1200 (3) burn ex|7200|24|-3| | | | |
| |Spinal Blaster|6| |6dx600 (5) burn ex|3600|23|-4| | | | |
| |Sponal Muonic Blaster|6| |6dx300 (10) burn sur|1800|21|-6| | | | |
| |Super Heavy Muonic Cannon|6| |6dx70 (10) burn sur|420|17|-6| | | | |
| |Capital Scale Muonic Cannon|6| |6dx35 (10) burn sur|210|15|-6| | | | |
| |Plasma Flak|2| |6dx10 burn ex|60|12|0| | | | |

Some of the numbers from the table are computed using a conversion table found at [https://fudge.ouvaton.org/fths.html](https://fudge.ouvaton.org/fths.html).


# Spot Checking Weapon Damage vs Vehicle Defenses
Below, I do simple "spot checking" of weapon damage against vehicles of different classes.

Fudge has an anti-instadeath rule, so any **Clearly Destroyed** type results could be treated as **Nearly Destroyed**. Also, I took creative liberty with naming some of the wound levels. Deal with it!

## Fighters
Let's start with our typical "fighter scale" blaster such as the Valiant’s Gatling Blaster which does 6dx5 (5) burn in GURPS or ODF +30 using +1/GURPS die or +10 using the THS conversion.

Now, let's see what sort of damage that does to some fighters:
* Drifter has Size Scale: 2; Mass Scale: 9; THS Damage Capacity: 9; Armor Value 5 (1 after "divisor")
  * Using Size Scale and armor, the total DF is +27 or +7 giving an average wound of **Vaporized** or **Immobilized**
  * Using Mass Scale and armor, the total DF is +20 or +0 giving an average wound of **Still Nothing Left** or **It Will Buff Out**
  * Using THS DC and armor give the same results as above
  * Using Size Scale + THS Damage Capacity and armor, the total DF is +18 and -2 giving an average wound of **Not There** and *Scratched Paint*
* Wildcat has Size Scale: 3; Mass Scale: 12; THS Damage Capacity: 10; Armor Value: 8/6 (4/2 after "divisor)
  * Using Size Scale and armor, the total DF is +23/+25 or +3/+5 for an average wound of **Space Dust** or **Damaged/Very Damaged**
  * Using Mass Scale and armor, the total DF is +14/+16 or -6/-4 for an average wound of **Space Debris** or **Tickles**
  * Using THS DC and armor, the total DF is +16/+18 or -4/-2 for an average wound of **Not Much Left** or **Nothing Really**
  * Using Size Scale + THS DC and armor, the total DF is +13/+15 or -7/-4 for an average wound of **Salvage?** or **Did You Attack Yet?**
* Tempest has Size Scale: 2; Mass Scale: 10; THS Damage Capacity: 10; Armor Value: 4; Force Screen: 10
  * Using Size Scale and armor, the total DF is +26 or +6 reduced to +16 or 0 after force screens for an average wound of **Not Much Left** or **Shields Are Down**.
  * Using Mass Scale or THS DC and armor, the total DF is +19 or +1 reduced to +9 or 0 after force screens for an average wound of **Nearly Destroyed** or **Shields Are Down**.
  * Using Size Scale + THS DC and armor, the total DF is +17 or -1 reduced to +7 or 0 after force screens for an average wound of **Immobilized** or **Shields Are Down**.
  
Now, let's take a typical "corvette scale" blaster such as a Lancer's Corvette Scale Cannon which does 6dx30 (5) burn in GURPS or ODF +180 using +1/GURPS die or +15 using the THS conversion. At this level, there is no need to mention the +1 ODF/GURPS die since all results are **Utter Annihilation**.

Now, let's see what sort of damage that does to those same fighters; in all cases, the DF is +5 higher:
* For the Drifter, the average wounds are **Salvage**, **Very Damaged**, **Very Damaged** and **Damaged** using Size Scale + armor, Mass Scale + armor, THS DC + armor and Size Scale + THS DC + armor respectively
* For the Wildcat, the average wounds are **Immobilized/Nearly Destroyed**, **It Will Buff Out/Scratched**, **Scratched/Damaged** and **Nothing Really/Scratched**
* For the Tempest, the average wounds are all **Shields Are Down**

Finally, let's throw a typical "capital scale" blaster such as an Imperator's Capital Scale Cannon which does 6dx75 (5) burn in GURPS or +450 or +17 ODF. Similar to with the "corvette scale" weapons, the +1 ODF/GURPS die option will always result in *Revalis White is not Coming Back From This**.

Now, let's see what sort of damage that does to those same fighters; in all cases, the DF is +7 above "fighter scale" and +2 above "corvette scale":
* For the Drifter, the average wounds are **Salvage?**, **Salvage**, **Salvage** and **Immobilized**
* For the Wildcat, the average wounds are **Nearly Destroyed**, **Scratched/Damaged**, **Damaged/Very Damaged** and **Scratched Paint/Damaged**
* For the Tempest, the average wounds are all **Shields Are Down**

## Corvettes and Capital Ships
A detailed analysis is not necessary. Mass Scale scales faster than damage except for +1 ODF/GURPS die option, but that is totally unworkable. THS DC scaling may not vastly outpace THS damage, but it doesn't work for fighters, so the effort would be wasted.

# Final Thoughts
There may be some formula to convert GURPS damage to use with Fudge for these vehicles, but is it worth the effort? My current proposed solution is to use Mass Scale for  Damage Capacity, make armor an attribute that adds to DDF and make the weapons do whatever damage is necessary to achieve the desired effect against the target ships. It is simple and still takes advantage of Scale, so it is compatible with regular characters.

Size Scale should still be useful for determining attack penalties, so it is good to keep around.

That still leaves rapid fire as a rugger in the room. I should probably address force screens too at some point.
