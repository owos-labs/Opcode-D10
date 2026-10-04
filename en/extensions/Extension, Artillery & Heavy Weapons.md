---
by: "\"SuperKitty\" MKKO"
last_updated: 08/26/2026
translated at: 08/26/2026
reviewed at: 09/17/2026
---

# Opcode:// D10 — Heavy Weapons & Artillery Extension

## Overview

### Skill Extensions

This extension introduces 2 new Skills.

**Artillery (INT + Artillery)**, comes with Specialisations such as Rifled Guns, Smoothbores, Unguided Rocket-Propelled Grenades, Recoillesses, and Missiles.

**Heavy Weapons (REF + Heavy Weapons).** Half of any bonus from Marksmanship could be applied to Heavy Weapons rolls. Relevant Specialisations, e.g. Machine Gun Specialisation on autocannon — pretty much offers a full bonus.

### New Specialisations

**Artillery:** Rifled Guns, Smoothbores, Unguided Rocket-Propelled Grenades, Recoillesses, Missiles, Mortars, Counter-Battery, Guided Weapons, Guided Weapons — Specific Type

**Operate:** Artillery, Computers — Guidance Systems, US&V

In case either Skill is used for an attack roll, attacking a target with **Exact Localization** does not incur the usual **−5** penalty since calibers.

# Weapon Types

## Direct-Fire Heavy Weapons

Direct-fire heavy weapons (such as rocket launchers and rifled artillery pieces) use **Artillery** for attack rolls. Failed attack results in a splash offset. For direct-fired grenades with HE payload, use **Marksmanship** instead. On a failure, the impact point deviates towards a random direction.

Rocket-propelled grenades and recoilless rifles are treated separately. They may use 1/2 of the character's Marksmanship (round up), or roll with **Artillery** or **Heavy Weapons**, depending on whether the target is within **0.5× Range**.

You can consult to the tables provided later on in this chapter for dealing with impact points and deviation distances.

## Indirect Fired Heavy Weapons and Artillery

Indirect fire weaponry use **Artillery** for attack checks.

Upon a failure, the impact point deviates in a random direction by an amount equals to: **Margin of Failure × the distance (in metres) specified in the table below** while on a success, the impact point will drift by **2d10 metres**.

Certain kinds of indirect-fire weapons, e.g. large-calibre artillery and mortars, may also be used for direct fire against targets within **0.5× Range**, and uses a different deviation value on failure.

When firing indirectly, even a successful attack will still deviate according to the following range brackets:

| Target Distance | on Success |
| --- | --- |
| Below 0.5× Range | 1d10 metres |
| 1× Range | 1d20 metres |
| 1–1.5× Range | 1d20+3 metres |
| 2× Range | 1d20+10 metres |

For every **2 points in Artillery**, you can reduce the deviation by **1 metre**, to a minimum of **1 metre**.

In case you fancy a direct-fire rifled weapon (such as certain tank guns) for indirect fire, use **Artillery** skill for it.

## Machine Guns and Anti-Materiel Rifles

HMGs, autocannons, and anti-materiel weapons uses the normal weapon rules.

## Guided Weapons

Fire-and-forget guided weapons resolve attacks with **Artillery (Guided Weapons)**, **Operate (Computers)**, or the weapon's **Tracking** statistic as a fixed success number vs. the locked target's relevant Driving Skill (**Operate + Vehicle Type**) or **Reflex Save**. If the attack succeeds, it deals damage. For most FPV systems, whether dropper drones or kamikazes, use **Operate (Rotary Wing Aircraft)**, **Operate (Fixed Wing Aircraft)**, or **Operate (US&V)** for guidance check.

The target may make an opposing **Agility** check against it, or, alternatively, you can just shoot the fucking thing down and call it a day.

For SACLOS, MACLOS, wire guidance, and similar man-in-the-loop guidance systems, attacks may only use **Artillery (Guided Weapons)**.

## Quick Reference

| Weapon Type | Below 0.5× Range | 0.5–1× Range | 1–1.5× Range | 2× Range |
| --- | --- | --- | --- | --- |
| **Rocket-Propelled Grenade / Recoilless Rifles** | Margin × 1m | Margin × 5m | Miss | Miss |
| **Rifled / Smoothbore Artillery / Tank Gun** | Margin × 0.5m | Margin × 2m | Margin × 5m | Margin × 10m |
| **Mortar** | Margin × 1m (Direct Fire) / Margin × 5m (Indirect Fire) | Margin × 5m | Margin × 10m | Miss |

# Warheads and Projectiles

Apparently once you figured out about launch things towards dudes, the next logical step is making the guess on what exactly you're going to hit them with.

## Anti-Armour

### High-Explosive Anti-Tank (HEAT) and High-Explosive Squash Head (HESH)

> "This is my RPG-7V2 with PG-7VM HEAT warhead. This is my problem solver right here."

HEAT Warheads are warheads that utilizes chemical energy to achieve armor defeat. This includes from the WWII-era Panzerfaust to the good old that they call it PG-7VL.

Upon impact, a HEAT warhead deals fragmentation damage over a radius of **Damage Dice Count × 1 metre**, and an lethal overpressure radius of **Damage Dice Count / 5 metres, no less than 1.5 meters** (consult 1.5 Weapons and Moddings, explosives section) against soft targets. When resolving armour penetration, if the attack did not penetrate, it does not deal any damage against the crew, should the target be a vehicle.

### Armour-Piercing / Kinetic Penetrators (AP)

> "Gunner! Tank! Sabot!"

Traditional Non-chemical kinetic penetrators.

From WW2-era AP, APCBC, API to the beloved APFSDS-T, to your average TC AP railgun slugs, are all treated as AP damage in this concern for the ease of our sanity. Apparently the majority of gun fired AP rounds comes with at least some kind of explosive filler but I don't really think we need to fuck ourselves, well, with all sorts of terminal effect here.

In simple terms, AP can only damage a single target and produces no additional fragmentation damage. For AP payloads, resolve Penetration against Armour and calculate damage as usual, attacks that does not penetrate deal no damage.

## Anti-Personnel

### Flechette and Buckshot

When you want one soft target to have a very bad day, you use buckshots, in case you want to offer a whole lot of soft targets a whole lot of bad days, you use a whole lot of buckshots. Flechette and buckshot round goes with the normal shotgun rules, starting from 40mm calibre, for every damage dice count above 4, reduce the range penalty by one bracket. These warheads also comes with a maximum coverage radius of **Damage Dice Count × 1 metre.** If the warhead comes with a VT or programmable fuse, damage falloff and coverage calculations may start from any distance of choice.

Targets within the affected area that is not already behind any cover may roll a **Luck Save** to determine whether they escaped the spread. On a success, we can treat them as already behind the nearest available cover.

Resolve Flechette and Shot damage normally, Against heavily armoured targets, attacks that did not penetrate deal no damage.

### High-Explosive (HE)

> "...All batteries, fifteen... fifty rounds, FIRE! FIRE!"

People have been blowing shits (and other dudes) up since a couple of centuries ago if you still have shit to give about it, while the majority of the recent developments over the last few decades is pretty much around two questions: how to blow shit up fast, and how to blow up shit up across all sorts of places.

For HE warheads, resolve Penetration first, then their point of impact, then deals damage against soft target within **Damage Dice Count / 3** meters of lethal overpressure range and **Damage Dice Count** metres of fragmentation radius. 

### Cluster and Canister Munitions

Cluster munitions. Canister munitions. Whatever you call the damn thing and however the urge in you to trashtalk my shit out on the differences off Discord, they resolve the damage effect mostly in the same fashion. There's someone who you don't like and don't like you and apparently comes with a gun in that postcode, you fire one of these funny thing there, if nothing happens you fire another round, evenaturally something comes out.

All cluster munitions uses following damage format: **10D10+3, 100m** where `10D10+3` is the damage and `100m` would be the coverage diameter.

Every target within the affected area without any overhead cover must roll a **Luck Save** against **Difficulty 10 + damage modifier**, For the example above, the Difficulty is **13**, then upon a successful Luck Save, the target must then make a **Agility Save vs. 20**:

- If the Agility Save succeeded, the target receives no damage.
- If the Agility Save failed, the target receives the weapon's minimum possible damage as . In this example, **13**.
- If the initial Luck Check fails, resolve damage according to damage type normally.

Armoured targets without any cover will automatically fail the Luck Save, therefore resolves the damage as specified as usual.

## Firing and Impact

Generally speaking, there is a delay of **three seconds** between firing a heavy weapon and the round actually arriving. You can calculate the **Time of Flight** using the respective weapon system's projectile velocity, measured in metres per second. Firing and reloading consume Actions as usual during a Combat Round. The actual impact, however, may not be resolved until the following round.

## Ballistic Weapons and Artillery

This is the most common seen type of heavy weapons. Grenade launchers, tank guns, artillery pieces. These weapons have their own Calibre and projectile velocity.

Apparently we're aware that muzzle velocity depends on the ammunition and propellant charge, but or the sake of simplicity, we've decided to abstract it into an average value for the launch platform across its supported ammunition types.

MLRS systems are also included in this category due to the way they operate.

### Example Launch Platforms

Here, Rate of Fire uses different rules as conventional weapons: the maximum number of rounds you can fire per turn. For weapons with autoloaders and ready-to-fire munition racks, we use an averaged value across the curve.
Generally speaking, should a weapon comes with automatic fire mode, it can use all attack actions (e.g. suppressive fire) related to it.

| Launch Platform | Weapon Type | Skill | Calibre | ROF / Reload | Projectile Velocity (m/s) | Range |
| --- | --- | --- | --- | --- | --- | --- |
| **30mm 6G25 AGS-30** | Heavy Weapon, Automatic Grenade Launcher | Artillery | 30x29 | 12 | 180 | 1000m |
| **56-P-542 DshK M1938** | Heavy Weapon, Heavy Machine Gun | Heavy Weapons | 12.7x108 | 20 | 800 | 500m |
| **14.5mm 56-P-562 KPV** | Heavy Weapon, Heavy Machine Gun | Heavy Weapons | 14.5x114 | 20 | 980 | 1500m |
| **25mm M242 Bushmaster 8hp** | Heavy Weapon, Heavy Machine Gun | Heavy Weapons | 25x137 | 3 (Low ROF) / 6 (High ROF) | 1300 | 2000m |
| **88mm KwK 43** | Heavy Weapon, Artillery | Artillery | 88x822 | 0.5 | 1000 | 2000m |
| **76mm Gun M1** | Heavy Weapon, Artillery | Artillery | 76.2x585 | 1 | 1000 | 1500m |
| **155mm M109A1B** | Artillery | Artillery | 155mm | 0.2 | 750 | 5000m |
| **152mm 2A37** | Artillery | Artillery | 125mm | 0.3 | 700 | 4000m |
| **203mm 2A44** | Artillery | Artillery | 203mm | 0.1 | 750 | 6000m |
| **9K51 BM21 "Grad" M21** | MLRS | Artillery | 122mm | 6 (Reload every 15 minutes) | 800 | 15000m |
| **M142 HIMARS MLRS** | MLRS | Artillery | 227mm | 2 (Every 10 minutes) | 1000 | 20000m |

### Example Ammunition

| Ammunition | Calibre | Penetration | Warhead Type | Damage |
| --- | --- | --- | --- | --- |
| **30mm VOG-17A (7P36)** | 30x29 | 20 | HE | 3d10 |
| **12.7x108mm B-32 (57-BZ-542)** | 12.7x108 | 155 | AP | 6D10-4 |
| **25x137mm APFSDS-T M919** | 25x137 | 550 | AP | 8D10-4 |
| **14.5x114mm BZT-44** | 14.5x114 | 250 | AP | 7D10-4 |
| **76mm M79 AP** | 76.2x585 | 1130 | AP | 10D10+2 |
| **88mm PzGr. 39/43** | 88x822 | 1600 | AP | 12D10+4 |
| **88mm Sprgr. 43** | 88x822 | 880 | HE | 6D10+6 |
| **155mm M107** | 155mm | 350 | HE | 15D10+2 |
| **152mm 3VOF41 (3OF30)** | 152mm | 300 | HE | 12D10+2 |
| **152mm 3VOF76/3VOF87 (3OF59)** | 152mm | 300 | HE | 13D10+3 |
| **203mm 3VOF34 (3OF43)** | 203mm | 500 | HE | 21D10+6 |
| **203mm 3VOF35 (3OF44)** | 203mm | 450 | HE | 20D10+6 |
| **122mm 9M22U (9N51)** | 122mm | 200 | HE | 24D4-14 |
| **227mm M26** | 227mm | 1000 | HEAT | 10D10+3, 100m |
| **227mm M31A1** | 227mm | 200 | HE | 30D4-20 |

# Artillery Combat

> "Can we have some artillery duels, GM?" they said. "Otherwise What the fuck am I supposed to play?" they said.

Upon the first artillery salvo splashes, or upon the defender detects an incoming attack from the attackers, both sides may enter a special **Artillery Combat Round**, provided neither side is within the other's direct-fire range, otherwise they use conventional infantry combat round. This special round takes place and is resolved at the **beginning of every second normal (infantry) Combat Round**, which means, each Artillery Combat turn lasts approximately **6.6 seconds**.

For example, if the artillery and infantry begin combat simultaneously:

- **Round 1:** Both artillery crew and infantry take their Actions.
- **Round 2:** Only the infantry take their Actions.
- **Round 3:** Both artillery crew and infantry take their Actions again.

First, all participating sides determine their initial **Localization Difficulty** based on the distance between them.

At the beginning of any artillery engagement, both sides have a base Localization Difficulty of **15** against one another. Add **10 Difficulty for every kilometre of range**, subject to GM discretion depending on the setting's technological era and available sensor systems into a localization tracker.

For example, suppose there are three participants, A, B, and C, A and B are 15km apart, B and C are 13km apart while A and C are 20km apart, their respective Localization Difficulties within the tracker would be:

- **A against B: 155**
- **A against C: 185**
- **B against C: 205**

Each participant comes with a unique Localization Difficulty tracker against every other participant who is not already located. Should the defender is within the direct fire range from the attacker at the beginning of the engagement, both sides may immediately obtain **Exact Localization**.

Should either side has already been located before combat begins, Localization Difficulty against the party starts at **0**,  and for apparently reasons the locating side (defender) comes with **Full Localization** of that target until the source of it can no longer provide further localization.

If the attacker's round splash from the previous shot can be observed by the defenders, the attacker's general direction can be acquired by the defender but this does **not** count as Approximate Localization regardless.

Any unit from the defender who is assigned to locate the attacker may roll **INT + Artillery (Counter-Battery) + applicable bonuses**, reducing the remaining Localization Difficulty tracker by the result rolled, including modifiers. Multiple units could make the same check given they have the knowledge, but only the highest check result can be used.

If the attacker's shot impact from the previous round cannot be observed by defender, or the attacker did not fire in the previous round, the Localization Difficulty tracker recovers by **5 points**, **If the attacker has not moved from their previous firing position when making their next attack, remove all Difficulty recovered in this manner.**

Once the remaining Localization Difficulty against a target reaches **0**, the defender obtains **Exact Localization** against the attacker. An Artillery attack against a target with Exact Localization does **not** suffer from the usual **−5 penalty**, If the attacker does not fire during the current round, or their impact cannot be observed, this localisation expires at the beginning of the next round and 5 difficulty is refilled into the localization tracker as ususal.

**As a rule of thumb, any attempt at direct fire before obtaining at least Exact Localization automatically fails.**

If either side can observe the target being engaged by any means when its rounds land, each consecutive round of fire reduces the count of deviation dice by **half, rounded up**. For example, if the default deviation is **1d10 metres**, the second consecutive round reduces it to **1d5 metres**, and the third consecutive round reduces it to **1d2 metres**.

Deviation cannot be reduced below **1 metre** through this rule.

If the defender moves for at least **1 round**, this bonus must be calculated again from the beginning.


### Counter-Battery Radar

Counter-battery radars vary in how accurately they can locate enemy firing positions. For simplicity, we're dividing them into three generations. To use a counter-battery radar, it must be **switched on**, and the firing unit must be within its detection range.All detection radii below are measured in **km**. Apply the following multipliers depending on the weapon being detected:

| Weapon Type | Detection Radius Multiplier |
| --- | --- |
| Mortars | ×0.5 |
| Conventional Artillery | ×1 |
| MLRS | ×3 |

Against Shoot-and-Scoot units or other moving targets, the GM should generally let the radar operator know that the target has moved when it happens. Whenever a unit fires within the radar's detection range, its operator may attempt to locate the firing position with a **Difficulty 15** Check, using either:

- **INT + Operate (Artillery)**; or
- **INT + Artillery (Counter-Battery)**.

Each radar generation requires a different number of **consecutive successful Checks** to locate a firing position. Fail a Check, and the count resets to zero. Against **Active-Reactive (rocket-assisted) artillery shells**, double both the **Localization Difficulty** and the **localisation error distance**.

#### First Generation

First-generation counter-battery radar appeared around the 1950s. These systems used vacuum tubes and analog electronics. Examples include the **AN-MPQ4** and **SNAR-1**. A first-generation radar can locate only **one firing position at a time**.

- **Detection Radius:** 10km
- **Shots Required:** 2 shots from the attacker
- **Localisation Error:** 300m
- **Required Successful Checks:** 2 consecutive successes

#### Second Generation

Second-generation counter-battery radar appeared around the 1980s, with early digital electronics and generally PESA-based systems. Examples include the **AN/TPQ-36** and **1L219**. A second-generation radar can locate **any number of firing positions** within its detection range.

- **Detection Radius:** 20km
- **Localisation Error:** 100m
- **Required Successful Checks:** 1

#### Third Generation

Third-generation counter-battery radar represents the modern standard. AESA, solid-state TX/RX modules, advanced algorithms — all the good stuff. Examples include the **AN/TPQ-53** and **1L260**. A third-generation radar can locate **any number of firing positions** within its detection range with noo operator Check required. Whenever a unit fires within range, the radar automatically locates its firing position.

- **Detection Radius:** 50km
- **Localisation Error:** 30m
- **Operator Check:** Not required

### Localization Difficulty Quick Reference

| Condition | Modifier | Description |
| --- | --- | --- |
| Base Difficulty | 15 | Covers the first kilometre, including targets within 1km. |
| Every Additional Kilometre | +10 Difficulty | Add 10 for every kilometre beyond the first. 1.1km counts as exceeding 1km. |
| Target Is Concealed | −3 to each Check's result | The attacker is obscured by mountains, terrain or other forms of concealment that make its position difficult to detect. |
| Target Is in an Obvious Position | +3 to each Check's result | The attacker somehow managed to set up shop in the middle of open field. Kursk was underrated. |
| Friendly Defender Units Within 1/4 of the Attacker's Range | +5 to each Check's result per qualifying group | Each unit must have direct communications with the artillery in team. Multiple units provide separate bonuses only if they are spaced at least 1/4 of the attacker's Range apart. |
| Friendly Defender Units Within 1/2 of the Attacker's Range | +3 to each Check's result per qualifying group | Each unit must have direct communications with the artillery in team. Multiple units provide separate bonuses only if they are spaced at least 1/2 of the attacker's Range apart. This bonus stacks with bonuses from units within 1/4 Range. |
| Friendly Defender Units Within 1× the Attacker's Range | +1 to each Check's result per qualifying group | Each unit must have direct communications with the artillery in team. Multiple units provide separate bonuses only if they are spaced at least 1× the attacker's Range apart. Do not apply this bonus if any friendly unit is within 1/2 Range or closer. |
| Any Number of Friendly Defender Units Within 2× the Attacker's Range | +5 to each Check's result; does not provide bonus should Localization Difficulty falls below 20. | At least one unit must have direct communications with the artillery in team and be able to observe the attacker's entire projectile trajectory. This bonus does not stack, regardless of how many units qualify. |

# Rocket-Assisted Projectiles, Missiles, and Fire-and-Forget Munitions

> "VITAL YOU SON OF A BITCH WORK ON THAT ABRAMS, WE ARE DYING HERE"
> "YEAH SETTING UP THE THING TAKES TIME, WAIT A BIT LONGER"

We decided to merge rocket-assisted projectiles and missiles into the same category (*Active-propelled* would be a better term, since hybrid propulsion systems and other proplusion methods are all things but you get the idea). Since these weapons normally comes with dedicated launch and/or fire control systems, we are treating the munition and its launcher as a fixed pair.

These munitions usually employs **HEAT** warheads and may feature at least some kind of guidance. Examples include the **TOW**, **RPG-7**, and **9K111 Fagot**.

## Unguided Launch

Unguided munitions does exactly what it says on the tin, there could either no guidance system for it or it's not being launched with the guidance being used, regardless of whether it supports guided flight or not.

For unguided launches, roll attacks through any appropriate Skill, such as **Artillery** or **Heavy Weapons**, then resolve the attack through normal heavy weapon rules.

## Semi-Automatic Guidance and Third-Party Guided Munitions

Semi-automatic guidance generally requires the operator to maintain guidance from launch until impact. In Opcode:// D10, both **CLOS** systems (such as SACLOS and MCLOS) and **COLOS** systems (such as your average SARH guidance munitions in your average neighbors house) require:

- One Check upon the munition launch.
- One separate guidance Check during each subsequent round during the munition travel.

Each subsequent round of guiding the same munition after the first round the Check's Difficulty is reduced by **one level**, from the second round onwards, should the Difficulty of a subsequent guidance Check falls below **10 or 15**, no further Checks are required in general. A **Standard Action** is still spent each round in order to maintain guidance until the munition impacts.

### COLOS Guidance

For a COLOS munition, you may perform one **Movement Action**, or an equivalent Action such as driving or manoeuvring for free if you are drving a vehicle, and as long as a successful guidance Check is made in the round before impact, the shot is counted as a hit.

The guidance can be interrupted during flight, the target can leave your LOS during guidance, but as long as you have a success on the guidance Check before impact, it is treated as a hit.

### CLOS Guidance

You cannot perform **Movement Actions** or any equivalent guiding a CLOS munition, otherwise it interrupts the guidance and the shot is treated as a miss, unless:

- The specific weapon model supports guidance on the move; or
- The weapon is not wire guided and you're moving across relatively flat ground or water.

If the target leaves your LOS during guidance, the hit Difficulty is increased by **two levels** per round.

You must succeed on **every guidance round before impact** for the munition to hit. 
Standard **TV guidance** is always treated as **MCLOS**, except you can move while guiding the munition.

### Third-Party Guidance

Third-party guidance rule is employed whenever the unit guiding the warhead and the warhead itself are separated, e.g. with third-party beam-riding guidance. Any friendly or hostile unit may provide guidance, provided it has **LOS** to the target and any guidance equipment  necessary.

All units providing guidance must designate the **same target point**, otherwise the munition hits a random target across all designated target within range.

Third-party guidance is treated as **COLOS** guidance.

## Active Guidance and Fire-and-Forget

> The missile knows where it is at all times. It knows this because it knows where it isn't by subtracting where it is from where it isn't, or where it isn't from where it is, whichever is greater, it obtains a difference, or deviation.

This is the good shit from modern warfare, you pick a point on the map, you launch whatever the fuck you've got at it, you watch it fly off into the sky, and you pray to god that it hits.

These munitions normally comes with **RF (radar)** or conventional optical seekers, and may support **TVM** or inertial guidance, some newer models can determine their own position through GPS, transmit information through satellite datalink, or use teh interweb (In modern times the thing you're arguing with online could a missile, you never know). I shit you not.

These munitions normally comes with an independent **Tracking** stat, and is treated as a fixed check outcome during guidance rounds. You may use either the munition's Tracking statistic or your own guidance roll to guide it.

Tracking may suffer penalties from ECM, EW systems, or whatever countermeasures that works. These weapons also have designated **Target Type**, in that case, you may only attack units belonging to those Target Types.

Guidance is usually resolved through one of:

- **Operate (Computers — Guidance Systems) + Tracking**;
- **Artillery (Guided Weapons — Specific Type) + Tracking**; or
- The munition's **Tracking** statistic alone, used as the roll result.

No further guidance Checks are required if your first check succeeds.

The defender must make appropriate Checks or take evasive measures during the impact round and throughout flight. The munition is treated as a **miss** only when the defender's evasion successes in the final round **exceed** the guidance success count.

Once launched, you cannot and don't need to make any further rolls, unless the weapon supports to be manually overrided mid-guidance.

> In the event that the position that it is in is not the position that it wasn't, the system has acquired a variation, the variation being the difference between where the missile is, and where it wasn't. If variation is considered to be a significant factor, it too may be corrected by the GEA. However, the missile must also know where it was.
> 
> The missile guidance computer scenario works as follows because a variation has modified some of the information the missile has obtained, it is not sure just where it is. However, it is sure where it isn't, within reason, and it knows where it was.


For most guidance systems in this category, use either **Operate (Computers — Guidance Systems) + Tracking** or **Artillery (Guided Weapons — Specific Type) + Tracking**.

> What the fuck did you just fucking say about the missile you little bitch? I'll have you know the missile knows where it is at all times, and the missile has been involved in obtaining numerous differences, or deviations, and has over 300 confirmed corrective commands. The missile is trained in driving the missile from a position where it is, and is the top of arriving at a position where it wasn't. You are nothing to the missile but just another position. The missile will arrive at your position with precision the likes of which has never been seen before on this earth, mark my fucking words. You think you can get away with saying that shit about the missile over the internet? Think again, fucker. As we speak the GEA is correcting any variation considered to be a significant factor, and it knows where it was, so you better prepare for the storm, maggot, the storm that wipes out the pathetic little thing you call your life.


Guided munitions based on **CV**, **AI**, **GPS**, or other modern network-based technologies, such as those used by the **Shahed-136/Geran** types comes with a fixed guidance value. You cannot make further adjustments or guidance Checks unless the weapon supports **Manual Override**.

You may use **Operate (Computers — Guidance Systems)** for guidance, replacing the munition's fixed guidance value with your roll. These munitions have **no Target Type restrictions**, but they are generally limited to using specific coordinate as a guidance target or designated targets type within a certain area within their operational Range.

### Example Launch Platforms and Ammunition

| Launch Platform | Seeker / Guidance Type | Skill | AP | Tracking | Damage Type | Damage | ROF / Reload | Projectile Velocity (m/s) | Range |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **6G3-2 RPG-7V2(PG-7VM)** | Manual | Heavy Weapons | 2150 | — | HEAT | 4D10+2 | 0.5 | 180 | 300 |
| **6G19 RPG-27 (7P47)** | Manual | Heavy Weapons | 4300 | — | HEAT | 5D10+2 | — (Disposable) | 180 | 300 |
| **9P111(9M14)** | MCLOS | Guided Weapons | 3500 | — | HEAT | 4D10+4 | 0.2 | 180 | 2500 |
| **9P135M(9M111 Fagot)** | SACLOS | Guided Weapons | 3500 | — | HEAT | 5D10+4 | 0.2 | 200 | 2500 |
| **9P135M(9M113M Konkurs-M)** | SACLOS | Guided Weapons | 4550 | — | HEAT | 6D10+3 | 0.2 | 200 | 2500 |
| **BGM-71 TOW** | SACLOS | Guided Weapons | 5000 | — | HEAT | 5D10+6 | 0.1 | 250 | 3000 |
| **FGM-148 Javelin** | TVM(IR) | Guided Weapons, Heavy Weapons | 5000 | 10 | HEAT | 6D10+3 | — (Disposable) | 200 | 3000 |
| **HN-5(9K32 Strela-2)** | TVM(IR) | Guided Weapons, Heavy Weapons | 350 | 15 | HE | 3D10+2 | 0.2 | 650 | 2000 |
| **9K135 (9M133 Kornet)** | SACLOS | Guided Weapons | 13500 | — | HEAT(Tandem) | 5D10 | 0.4 | 300 | 4500 |
| **Spike** | TVM(VIS) | Guided Weapons, Heavy Weapons | 7000 | 10 | HEAT | 5D10+3 | 0.1 | 180 | 5000 |
| **One way attack FPV(HE)** | CV(VIS/IR) | Operate (Rotary Wing Aircraft), Guided Weapons, Operate (US&V) | 15 | 15 | HE | 2D6+3 | — | 10 | 2000 (From Starting Point) |
| **LR one way attack UAV(HE)** | GNSS/CV/TVM | Guided Weapons, Operate (Computers), Operate (US&V), Operate (Fixed Wing Aircraft) | 100 | 15 | HE | 10D10 | — | 100 | 50000 |