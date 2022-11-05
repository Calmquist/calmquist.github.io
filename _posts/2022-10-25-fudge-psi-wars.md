---
title: "Fudge Psi-Wars Part 1"
date: 2022-10-25
---

This is part 1 of my thoughts on converting Psi-Wars to Fudge.

For more information about Psi-Wars, visit the [wiki](http://psi-wars.wikidot.com/) and the [Mailanka's Musing blog](https://mailanka.wordpress.com/).

# Traits

Converting Psi-Wars to Fudge should be possible and may even be feasible. GURPS traits consist of attributes, skills, advantages and disadvantages. Fudge traits consist of attributes, skills, gifts and faults. Besides the slight vocabulary difference between advantage/gift and disadvantage/fault, the traits are basically the same, right?
Well, there are some differences that could be important, but using a GURPS to Fudge conversion is a good place to start.

Skills are very similar between the two systems, but there are two important differences. One is that GURPS skill levels are based on underlying base attributes while Fudge skills and attributes are decoupled. The other is that the Fudge adjective ladder is much coarser than GURPS skill levels. Fudge is also a "roll over" system, but that difference is minor.
Omar has some skill and difficulty conversion tables that seem reasonable: <http://www.sonic.net/~rknop/php/Omar/fudge/gurpsconv.php/gurpsconv.html>
Obviously, there is room to play with the specific numbers, but skill conversion is fairly simple.

Five-Point Fudge is a simple system for handling skills: <https://www.panix.com/~sos/rpg/fudfive8.html>. It may be useful to modify the default list for the setting, but it is a useful starting point.

Advantage/gift and disadvantage/fault conversions are a bit more work than skills. The mechanics of the two systems are different, so some traits may require effort to convert, and some may not be applicable. Additionally, Fudge gifts/faults usually all have the same "point value" while GURPS advantages/disadvantages have individual point values.

Attributes are a special case. It is possible to use the GURPS attributes in Fudge, but what do they do? Fudge suggests using attributes a general, catch all skills, or even as skill defaults but that seems to couple attributes and skills.
Fate allegedly eschewed attributes in favor of skills. In reality, it combined attributes and skills and called them "skills." It also based some "hidden attributes" such as Damage Capacity and Strength on some of the skills.
I am not sure how I would handle attributes yet, but I think simple copying from GURPS and the Fate option are both unsatisfying.

I don't have much more to say about skills at the general level other than to note that they may either need to be more broad than GURPS skills, or characters may need to have more "skill points" than the default Fudge suggestions.

I will need to revisit attributes and will probably revisit gifts and faults.

# Psionics

Default Fudge psionics are too expensive and harsh for Psi-Wars. Default Fudge treats all Supernormal Powers such as psionics as two gifts (or more). It suggests giving psionic characters "free levels" in psi heavy games to offset the high cost.
A sample system can be found in the SRD: <http://www.sonic.net/~rknop/php/Omar/fudge/FudgeSRD/node12.html#SECTION001230000000000000000>

Psi-Punk probably has some decent ideas for psionic powers in Fudge: <https://www.accessiblegames.biz/our-games/psi-punk/>

For Psi-Wars, I would suggest using some combination of gifs and skills. I have even had thoughts about attributes for determining the strength of individual abilities.
I want to revisit this later, but that is a high level overview of Fudge psionic power.

# Communion

The base Communion gift is much easier to handle. Simply use Fudge Divine Favor. The mechanics cover general and specific prayers very similar to the GURPS versions.
<http://www.sonic.net/~rknop/php/Omar/fudge/FudgeSRD/node12.html#SECTION001220000000000000000>
I am not sure of the earliest GURPS version of Divine Favor, but this predates GURPS Religion for 3e by a decade.
Fudge doesn't have alternative ability mechanics, so Learned Prayers would at least require different treatment.

# Cybernetics

Cybernetics are simply enhanced attributes or gifts (or possibly skills) at the same cost as regular bonuses. Take a fault to represent the drawbacks.

# General Gameplay

In GURPS, skill checks are 3d6 vs TN where TN is skill level + modifiers. A skill check is successful if the roll is less than or equal to the TN. Attribute, self control, appearance and other similar checks are similar.
GURPS effect rolls (e.g. reaction and fright) are usually 3d6 + modifiers. The result is evaluated against some table or other guideline to determine the outcome. Some effect rolls use more or less than 3 dice.
In Fudge, skill and attribute checks are skill/attribute level + 4dF vs target. The check is successful if the result meets or exceeds the target.

Converting Psi-Wars general gameplay to Fudge is as simple as converting target numbers and converting from roll under to roll under ... except that simple mechanical conversions won't be satisfying and won't always work.

Reaction rolls are simple. Use the default rules from the SRD. <http://www.sonic.net/~rknop/php/Omar/fudge/FudgeSRD/node8.html#SECTION00870000000000000000>
Opposed rolls work fine in Fudge. Fudge has a bell curve.

One important thing to keep in mind is that GURPS uses real world weights, lengths, etc. while Fudge tends to use adjectives such as poor, fair and superb. Psi-Wars tends to ignore the specific details, so using Fudge should normally require unit conversions.

The GM will need to make some arbitrary decisions when necessary. The GM must either codify units in advance or make ad hoc decisions on the spot. Either case should work without too much trouble.

If you want an Impulse Buy type option, simply use Fudge Points: <http://www.sonic.net/~rknop/php/Omar/fudge/FudgeSRD/node6.html#SECTION00636000000000000000>

# Combat

A story element is an arbitrary and variable amount of time in which something interesting happens. The GM describes the scene and asks the players for their characters actions during the scene and one or more die rolls to determine what happened. The GM (possibly with player input) interprets the results and describes what happens during that particular element.
Story elements seem like they would work well for chases, and Psi-Wars should do a significant part of its combat as "chases," so story elements seems like a good option for Psi-Wars combat.
In simultaneous combat rounds, each round is of some unspecified length and is handled like a quick contest of combat skills.
This is quite simple, but there are combat options available if you would lime more variety. The victor of a given combat round must exceed his opponent's roll and achieve a minimum result (usually poor) to land a "hit." Without special combat options such as one or both characters making especially offensive attacks, only one combatant can be injured each round.
In alternating combat turns, combatants take turns and make both attack and defense actions. In melee combat, the defense is usually the same combat skill as with offense but could be a separate parry, block or dodge skill or anything else reasonable.
In any combat mode, NPCs (particularly moons or other unimportant NPCs) can be treated as "passive" opposition by assuming they roll equal to their skill level. It can make less important combat go faster.
See the combat section of the SRD for details: <http://www.sonic.net/~rknop/php/Omar/fudge/FudgeSRD/node9.html>

I suggest using story elements for most Psi-Wars combat and chases and using another mode if it ever feels appropriate for a given situation.
Note that story elements can be modified to use both attack and defense if desired. Since many chases involve ranged combat, splitting using both is often useful.

By default, Fudge uses "wound levels" rather than "hit points." As an aside, Steel Roses and Mecha Aces do have hit point rules for their mecha for some reason. As far as I am aware, Heart Quest doesn't use HP for regular characters, only the mecha.

Injury is handled as the attackers Offensive Damage Factor (ODF) vs the targets Defensive Damage Factor (DDF). These values can be combined to the Total Damage Factor or Damage Factor. This Damage Factor may optionally be modified by the attackers margin of success or an optional damage roll.
ODF is determined by Strength (or equivalent attribute for muscle powered weapons), weapon damage modifier, scale, applicable gifts/faults and other modifiers.
DDF is determined by Armor, optionally Damage Capacity (or similar attribute), scale, applicable gifts/faults and any other applicable modifiers.
The total damage is checked against the wound threshold table, and the applicable box is checked off. If no available boxes are available. check off the next highest available box and note the actual severity of the wound.
If you are familiar with Fate's stress  and complications, you will notice that Fate uses modified Fudge wound levels.

# Scale

Fudge was designed to work with characters of various sizes. To accomplish this, it uses a concept called scale. It is summarized in the SRD: <http://www.sonic.net/~rknop/php/Omar/fudge/FudgeSRD/node5.html#SECTION00530000000000000000>

Scale in combat is also described here: <http://www.sonic.net/~rknop/php/Omar/fudge/FudgeSRD/node9.html#SECTION00958000000000000000>

Note that any attribute can be scaled. For vehicles, strength/mass scale is important, but speed and weapon damage scales are also important. Even technology level can be used as a type of scale.

# Vehicles

Fudge will never have a vehicle design system as detailed as GURPS Vehicles. Normally, it is best to create vehicles as characters with vehicle attributes.
Fudge vehicles can be bicycles, cars, spaceships and even horses or exotic flying alien mounts.
The Fudge 10th Anniversary Edition has Fudge Vehicles. It is a subsystem for describing vehicles as characters.

It uses the attributes: durability, size, speed and maneuverability. These are represented as numbers rather than adjectives on the trait ladder.

It doesn't mention this explicitly, but you can treat these "attributes" as scale values of the given attributes with the base vehicles of a given type having a level of average in each attribute. Then, custom mods can keep the scale of the base vehicle and modify the attribute level.
For example, consider a car with speed scale 12. Since it is default, it has average speed. A special fast car can have fair or good speed for a car and would still have speed scale 12.
Vehicular weapons have attributes too (in this case, weapons are characters!). Fudge Vehicles gives weapons damage, range and target size attributes (really attribute scales). The range can be subjective using the trait ladder or objective using real world measurements (or both if you want).
The damage and target size scales means you can have capital ships with anti fighter turrets doing fighter scale damage while fighters can have anti capital ship missiles that a fighter can avoid easily. Ships can also have anti missile point defense weapons.
Any trait the vehicle has besides an attribute is a gift or a fault (or perhaps a feature).
Fudge Vehicles lists example gifts/faults and vehicles. It also gives a sample combat system you can uses if you want a detailed combat (or part of a combat). If you don't need the specific mechanical details, you can use Story Elements (or even use some of the Fudge Vehicles combat system in Story Element combat).

In summary, Fudge doesn't have a highly detailed system for designing "realistic" vehicles. Instead, it has a simple system for describing vehicles of various scales interacting together. Fudge can use the same rules for vehicular adventuring and combat as with regular characters with relatively minor modifications.

# Rank, Status and Wealth

Rank, Status and Wealth are leveled traits, so making them attributes seems like a natural choice. Psi-Wars already uses Pulling Rank and an abstract wealth system. Using a Rank attribute gives us Pulling Rank "for free" with no need for an AR table.
Giving Status difference as a straight bonus to influence checks is not likely a good idea. Remember that even +1 is a major bonus in Fudge.
Remember that high Status gives other benefits such as servants, access or special access to fancy events, etc. Pulling Rank with Status is still an option too.
The Title perk may be below the resolution of Fudge (it would otherwise be a full gift), so consider letting Status give appropriate titles and other niche benefits "for free."
Don't give free Status from Rank and Wealth like with GURPS. Fudge doesn't typically do that sort of thing.
That is about it.

