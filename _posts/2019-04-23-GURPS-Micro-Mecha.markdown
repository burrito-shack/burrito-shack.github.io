---
layout: post
title:  "GURPS Micro-Mecha v0.1"
date:   2019-04-23 23:50:49 -0400
comments: true
categories: gurps
---
There's no reason not to admit that I don't know what I'm doing, since it's on a private blog! Even still, I don't know what I'm doing. That's important to establish off the bat. But let's get on to the content.

# GURPS Mecha Is A Mess
I'm not being very fair, am I? After all, David Pulver worked hard on *GURPS Mecha*! Or did he work hard on *GURPS Spaceships*? Or did he work hard on *GURPS Spaceships 4: Fighters, Carriers and Mecha*? Or did Sean Punch work hard on the *Fourth Edition Basic Set*, and I should build a Mech as a character on a 1000 point budget, giving his main cannons as Innate Attacks and scaling up handheld weapon damage somehow?

Well, the answer is "Yes," and "All of the above." Of course Pulver worked hard. Of course the *Basic Set* is good. And there's a good argument in favor of doing it both ways. But there are five separate systems for designing Mecha in GURPS, between 3rd and 4th editions. And all of them are complicated. Even *GURPS Spaceships* is complicated, to a degree. It takes 28 pages to explain the systems on offer. *GURPS Spaceships 4* has an explanation of Mecha which is drastically undercut, with only SM+4 designs and legs added, but the removal of Medium/Minor weapons for those designs, and no explanation of how to scale handheld weapons.

So, in this mixture of 6 separate systems (Mecha as Allies, 3e *GURPS Mecha*, 3e *GURPS Vehicles 2nd Edition*, 4e *GURPS Spaceships 4*, *Pyramid #3/40*'s *Mecha Operations* and *Pyramid #3/51*'s *Modular Mecha*), and with the hopes of running an Ultra-Lite Mecha game via Play-by-Post, I came up with a way to make things worse: I made another one, and I made my best effort to fit it onto a single page.

<!-- more -->

# Micro Mecha
## Mecha At War
The default setting assumed here uses futuristic, laser-firing ‘Mechs of roughly 7 yards in height. For ‘Mechs at different levels of technology, increase Loaded Weight by 1 rank (with the matching decrease in Move) and decrease all other traits by 1 (do not double-tax Move) for every major technological leap backwards, or the opposite (decrease LWt and increase everything else) for the product of improved technology.
For ‘Mechs of lesser size, reduce all ranks including LWt by 1 per major size jump; of greater, increase all ranks including LWt by 1.

To build a mech, you spend 20 Hard Points. Each of these represents a piece of equipment or mechanical feature of your mech. These fall into roughly five categories:
Armor, Movement, Power, Weapons and Support.

## Armor
Each Hard Point assigned to armor grants 6 dDR, and increases the Tonnage by 1 rank on the table (the default is 20 tons), along with a matching decrease in Move by 1 rank.
When a Mech takes damage, each die of dDamage dealt reduces the overall armor by 1 dDR; Sundering weapons deal 2 dDR worth of damage per die.

## Damage
When taking damage that penetrates DR, roll a 20-sided die and compare to the Hard Point list. The Mech makes an HT roll to avoid the system being disabled. If the system is already disabled, then it is destroyed on a failed HT roll. If the system is already destroyed, then roll HT to avoid the entire Mech being blown up. If more than 5 dDamage penetrates DR, continue rolling HT after a failure to see how badly the attack penetrates.

## Movement
Each Hard Point assigned to additional legs ascends Move by 1 rank, with a default (for two legs) of 10. Regardless of the number of legs, movement costs 1 Power Point.
This requirement may be increased, with each Power Point further increasing Move by 1 rank per point. This must be decided when creating the Mech.

## Power
Each Hardpoint assigned to power generation grants 2 Power Points. These Power Points must be assigned during combat situations to allow movement, fire powerful weapons, and power support equipment.
Assigning and re-assigning Power Points occurs during the combat round.
## Weapons
Each Hardpoint assigned to weapons can be grouped together into a single weapon or separated into multiple weapons, depending on preference, though this choice must be made at the time of generation (not in real-time).
Adding a Hardpoint ascends the damage scale by 1 rung, beginning with 1D. Up to 2 modifications can be added per Hard Point, which each add a 1-Power-Point requirement to fire (the default is 0). The modifications are chosen from the following:
1. **Heavy Damage** ascends 1 rank.
2. **Sundering** Deals extra damage when destroying armor; overall damage is reduced by 1 rank.1
3. **Armor Piercing** Divides dDR by two.1
Multi-Hardpoint weapons systems may take Heavy up to twice per Hard Point, each instance costing 1 Power Point as normal.

### Handheld Weapons
One-Handed Ranged deals Weapon Damage of 1 rank lower, and can take up to 1 Power Point upgrade if limited to 10 shots.
Two-Handed Ranged deals Weapon Damage, and can take up to 1 Power Point upgrade if limited to 10 shots.
Handheld Melee weapons deal Weapon Damage, and automatically choose between being Armor Piercing or Sundering. They then choose 1 further Power Point upgrade, which may be additional Sundering or Armor Piercing, or extra damage. Handheld Melee still cannot have both AP and Sundering.

## Support
Additional equipment may be assigned to Hard Points, each of which is listed below, along with any Power Point requirements.

1. **Weapons Jammer** *(1 Power)* Attacks made against the Mech are made with a –2 penalty.
2. **Targeting System** *(1 Power)* Attacks made by the Mech are made at +1.
3. **Arm** *(1 Power for all Arms)* Either holds handheld weapons, or can be used for striking in melee (Weapon damage +1 Rank).
4. **Radar** Allows an IQ-based Electronics Operation (Sensors)/TL check to locate other nearby Mecha.
5. **Stealth Countermeasures** Attempts to use Radar to detect the Mech are made with a –2 penalty.

## Mecha Combat
Each turn, choose one action from those below, and move up to your Move in yards:

1. **Attack** *Gunnery (Mecha)/TL* check to deal  damage to one target per weapons battery. Each target past the first assesses a –1 penalty to all attacks that round.
4. **Evade** *Driving (Mecha)/TL* check to give enemy Mechs –2 penalty to attack you for 1 turn.
2. **Lock-On** *Electronics Operation (Sensors)/TL* to grant a +2 to attacking a specified target on the next turn.
3. **Power Allocation** Decide whether to act *quickly* or *carefully*. Careful allocation takes the full turn. If done quickly, test Repair (Mecha)/TL. On failure, your Power pool shrinks by 1 until you reallocate. On a critical success, your Power pool expands by 1, until combat ends. On a critical failure, your Power pool shrinks by 1 until combat ends.

| Rank | LWt | Move | Damage |
|------|-----|------|--------|
| -14 |150 lbs | 2/3” | |
| -13 |200 lbs | 1” | |
| -12 |300 lbs | 1.5” | |
| -11 |500 lbs | 2” | |
| -10 |700 lbs | 3” | 1 |
| -9 |1,000 lbs | 5” | 1D-2 |
| -8 |1 ton | 8” | 1D-1 |
| -7 |1.5 ton | 1 ft | 1D |
| -6 |2 ton | 1.5 ft | 1D+2 |
| -5 |3 ton | 2 ft | 2D |
| -4 |5 ton | 1 | 3D |
| -3 |7 ton | 1.5 | 5D |
| -2 |10 ton | 3 | 7D |
| -1 |15 ton | 5 | 1D dDMG |
| +0 |20 ton | 7 | 1D+2 dDMG |
| +1 |30 ton | 10 | 2D dDMG |
| +2 |50 ton | 15 | 3D dDMG |
| +3 |70 ton | 20 | 5D dDMG |
| +4 |100 ton | 30 | 7D dDMG |
| +5 |150 ton | 50 | 5D dDMG |
| +6 |200 ton | 70 | 7D dDMG |
| +7 |300 ton | 100 | 1D cDMG |
| +8 |500 ton | 150 | 1D+2 cDMG |
