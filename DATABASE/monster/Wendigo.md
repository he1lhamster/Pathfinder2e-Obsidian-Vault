﻿---
ac: '40'
alignment: CE
all_resistance: null
burrow_speed: null
charisma: '+6'
climb_speed: null
constitution: '+9'
creature_ability:
- Dream Haunting
- Heatsight
- Howl
- Ride the Wind
- Wendigo Torment
creature_family: null
description: 'Wendigos are incarnations of the fears of starvation, loneliness, and
  fatal exposure to cold weather. They haunt the frozen expanses of the world.<br/><br/><b><u>Recall
  Knowledge - Beast</u> ( [[DATABASE/skill/Arcana|Arcana]] , [[DATABASE/skill/Nature|Nature]]
  )</b>: DC 38<br/><b><u>Unspecific Lore</u></b>: DC 36<br/><b><u>Specific Lore</u></b>:
  DC 33'
dexterity: '+7'
element: null
fly_speed: '100'
fortitude: '+32'
hardness: null
hp: '315'
id: '409'
immunity:
- cold
- fear
intelligence: '+6'
land_speed: null
language:
- '[[DATABASE/language/Aklo|Aklo]]'
- '[[DATABASE/language/Common|Common]]'
- '[[DATABASE/language/Jotun|Jotun]] ; telepathy 1 mile'
level: '17'
max_speed: '100'
name: Wendigo
perception: '+32'
rarity: Uncommon
reflex: '+30'
resistance: null
rus_type_level: null
school: null
sense:
- darkvision
- heatsight 60 feet
size: Large
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +32'
- '[[DATABASE/skill/Athletics|Athletics]] +33'
- '[[DATABASE/skill/Deception|Deception]] +29'
- '[[DATABASE/skill/Intimidation|Intimidation]] +33'
- '[[DATABASE/skill/Nature|Nature]] +28'
- '[[DATABASE/skill/Occultism|Occultism]] +29'
- '[[DATABASE/skill/Religion|Religion]] +28'
- '[[DATABASE/skill/Stealth|Stealth]] +30'
- '[[DATABASE/skill/Survival|Survival]] +30'
source: '[[DATABASE/source/Bestiary|Bestiary]]'
speed:
- fly 100 feet
spell:
- '[[DATABASE/spell/Nightmare|Nightmare]]'
- '[[DATABASE/spell/Wind Walk|WindWalk]]'
strength: '+8'
strength_req: '8'
strongest_save:
- Fortitude
swim_speed: null
trait:
- '[[DATABASE/trait/Beast|Beast]]'
- '[[DATABASE/trait/Cold|Cold]]'
- '[[DATABASE/trait/Uncommon|Uncommon]]'
type: Creature
vision: Darkvision
weakest_save:
- Will
weakness:
- cold iron 10
- fire 15
will: '+26'
wisdom: '+5'

---
# Wendigo

Wendigos are incarnations of the fears of starvation, loneliness, and fatal exposure to cold weather. They haunt the frozen expanses of the world.
**Recall Knowledge - Beast ([[DATABASE/skill/Arcana|Arcana]], [[DATABASE/skill/Nature|Nature]])**: DC 38
**Unspecific Lore**: DC 36
**Specific Lore**: DC 33

# Wendigo<span class="item-type">Creature 17</span>

<span class="trait-uncommon item-trait">Uncommon</span><span class="trait-alignment item-trait">CE</span><span class="trait-size item-trait">Large</span><span class="item-trait">Beast</span><span class="item-trait">Cold</span>
**Source** [[DATABASE/source/Bestiary|Bestiary]]
**Perception** +32; darkvision, heatsight 60 feet
**Languages** [[DATABASE/language/Aklo|Aklo]], [[DATABASE/language/Common|Common]], [[DATABASE/language/Jotun|Jotun]]; telepathy 1 mile
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +32, [[DATABASE/skill/Athletics|Athletics]] +33, [[DATABASE/skill/Deception|Deception]] +29, [[DATABASE/skill/Intimidation|Intimidation]] +33, [[DATABASE/skill/Nature|Nature]] +28, [[DATABASE/skill/Occultism|Occultism]] +29, [[DATABASE/skill/Religion|Religion]] +28, [[DATABASE/skill/Stealth|Stealth]] +30, [[DATABASE/skill/Survival|Survival]] +30
**Str** +8, **Dex** +7, **Con** +9, **Int** +6, **Wis** +5, **Cha** +6
**Heatsight** (divination, primal); Heatsight is a precise sense that sees heat signatures.

---
**AC** 40; **Fort** +32, **Ref** +30, **Will** +26; +1 status to all saves vs. magic
**HP** 315, regeneration 30 (deactivated by cold iron); **Immunities** cold, fear; **Weaknesses** cold iron 10, fire 15

---
**Speed** fly 100 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> jaws +33 [+28/+23] (cold, magical, reach 10 feet), **Damage** 3d10+12 piercing plus 2d6 cold</span><span class="in-box-ability">**Melee** <span class="action-icon">1</span> claw +33 [+29/+25] (cold, magical, agile, reach 10 feet), **Damage** 3d8+12 slashing plus 2d6 cold and Grab</span>**Primal Innate Spells** DC 38; **8th** _[[DATABASE/spell/Wind Walk|wind walk]]_ (at will); **4th** _[[DATABASE/spell/Nightmare|nightmare]]_ (see dream haunting)
**Primal Rituals** DC 38; **8th** _[[DATABASE/ritual/Control Weather|control weather]]_
<span class="in-box-ability">**Dream Haunting** A target that fails its save against the wendigo’s _nightmare_ is exposed to wendigo torment.</span><span class="in-box-ability">**Howl** <span class="action-icon">3</span> (auditory, concentrate, enchantment, fear, incapacitation, mental, primal) **Frequency** Three times per day; **Effect** The wendigo unleashes a forlorn howl that can be heard up to 1 mile away. Any creature that hears the howl must succeed at a DC 38 Will save or be frightened 1. Any creature that critically fails and is within 120 feet of the wendigo is instead frightened 3, and is also fleeing for 1d4 rounds (or until it’s no longer frightened, whichever comes first). A creature frightened by a wendigo’s howl still naturally recovers from its fright but can’t reduce it below frightened 1 in this way until 1 hour has passed or magic is used. Whether it succeeds or fails its save, a creature is then temporarily immune to that wendigo’s Howl for 24 hours.</span><span class="in-box-ability">**Ride the Wind** <span class="action-icon">5</span> (air, concentrate, primal, transmutation) **Trigger** The wendigo casts _wind walk_ while it has Grabbed a foe. **Effect** The wendigo attempts to turn the grabbed creature into wind and carry it along as part of the action. If the target succeeds at a DC 38 Will save, it prevents itself from being transformed; in this case, the wendigo still transforms, automatically releasing the victim. A creature forced to Ride the Wind along with the wendigo is exposed to wendigo torment. The target can attempt a new Will save each round to return to normal, though it immediately becomes corporeal and begins falling if it succeeds.</span><span class="in-box-ability">**Wendigo Torment** (curse, enchantment, mental, primal) A creature affected by wendigo torment can’t recover beyond stage 1 until it has been restored to full HP. **Saving Throw** Will DC 38; **Stage 1** Stupefied 4 (1 day); **Stage 2** As stage 1 (1 day); **Stage 3** The creature searches for an individual of its own ancestry to kill and devour. It then becomes affected by _wind walk_ and sprints into the sky so fast that its feet burn away into jagged stumps. As the creature wind walks into the sky, it is replaced by a new wendigo over 2d6 minutes. Wish, similar magic, or a 9th-level resurrect ritual can return the victim to life. The new wendigo remains even if the victim is resurrected.</span>

###  Wendigo Worship

Some humanoids who dwell in arctic regions offer tribute to wendigos that hunt near their villages, treating them as gods or spirits of nature that must be appeased. They occasionally perform rites of cannibalism and place fetishes throughout the wilderness to mark the wendigo’s domain.