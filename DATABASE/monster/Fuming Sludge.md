﻿---
ac: '16'
alignment: N
charisma: '-5'
climb_speed: '20'
constitution: '+5'
creature_ability:
- Attack of Opportunity
- Chemical Sense
- Constrict
- Cooling Glob
- Smoldering Haze
dexterity: '-3'
fortitude: '+18'
hp: '160'
id: '984'
immunity:
- critical hits
- fire
- mental
- piercing
- precision
- slashing
- '[[DATABASE/condition/Unconscious|unconscious]]'
- '[[DATABASE/trait/Visual|visual]]'
intelligence: '-5'
land_speed: '20'
level: '7'
max_speed: '20'
name: Fuming Sludge
perception: '+11'
rarity: Uncommon
reflex: '+8'
sense:
- chemical sense 60 feet
- no vision
size: Medium
skill:
- '[[DATABASE/skill/Athletics|Athletics]] +19'
source: '[[DATABASE/source/The Slithering|The Slithering]]'
speed:
- 20 feet
- climb 20 feet
strength: '+6'
strength_req: '6'
strongest_save:
- Fortitude
trait:
- '[[DATABASE/trait/Mindless|Mindless]]'
- '[[DATABASE/trait/Ooze|Ooze]]'
- '[[DATABASE/trait/Uncommon|Uncommon]]'
type: Creature
weakest_save:
- Reflex
weakness:
- cold 5
will: '+11'
wisdom: '+0'

---
# Fuming Sludge

The slurry from alchemical experiments is often as flammable as it is toxic. In especially volatile cases, a fuming sludge can form from ignited pools of unstable alchemical runoff. It resembles a charcoal-colored slurry studded with tiny embers, and it continually emits a thin haze of accelerant that amplifies the fires it starts.
 A fuming sludge must consume the base chemicals of living creatures to survive and can instinctively identify the complex molecules found in most animate creatures. The first meal of many a fuming sludge is its accidental creator, but it soon moves on to hunt in lush forests or densely populated settlements. A fuming sludge can extrude a powerful pseudopod to strike its victims, but it can also eject portions of its body with peristaltic contractions. These rapidly-cooling globs of goo slow down fleeing prey, but the cold, crusty residue can also alert canny explorers to their presence.
**Recall Knowledge - Ooze ([[DATABASE/skill/Occultism|Occultism]])**: DC 25
**Unspecific Lore**: DC 23
**Specific Lore**: DC 20

# Fuming Sludge<span class="item-type">Creature 7</span>

<span class="trait-uncommon item-trait">Uncommon</span><span class="trait-alignment item-trait">N</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Mindless</span><span class="item-trait">Ooze</span>
**Source** [[DATABASE/source/The Slithering|The Slithering]]
**Perception** +11; chemical sense 60 feet, no vision
**Skills** [[DATABASE/skill/Athletics|Athletics]] +19
**Str** +6, **Dex** -3, **Con** +5, **Int** -5, **Wis** +0, **Cha** -5
**Chemical Sense** A fuming sludge detects nearby living and undead creatures by their complex chemical compositions, but it can't detect elementals or other creatures composed of a single element.
**Smoldering Haze** (aura, fire) 15 feet. The fuming sludge constantly emits incendiary smoke that creates [[DATABASE/condition/Concealed|concealment]] around it. The smoke doesn't impair the fuming sludge's chemical sense. A creature that enters the aura or begins its turn in the aura becomes [[DATABASE/condition/Sickened|sickened 1]] (DC 25 Fortitude negates) and cannot recover from [[DATABASE/condition/Persistent Damage|persistent fire damage]] for 1 round. It is then temporarily immune to the sickening effect of the smoldering haze for 1 minute. A creature that is currently holding its breath, that doesn't need to breathe, or that's immune to poison is immune to the aura's sickened effect but not the concealment or inability to recover from persistent fire damage.

---
**AC** 16; **Fort** +18, **Ref** +8, **Will** +11
**HP** 160; **Immunities** critical hits, fire, mental, piercing, precision, slashing, [[DATABASE/condition/Unconscious|unconscious]], visual; **Weaknesses** cold 5
<span class="in-box-ability">**[[DATABASE/monsterability/Attack of Opportunity|Attack of Opportunity]] <span class="action-icon">5</span> ** </span>

---
**Speed** 20 feet, climb 20 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> pseudopod +17 [+12/+7], **Damage** 2d10+6 bludgeoning plus 1d8 [[DATABASE/condition/Persistent Damage|persistent fire]] and [[DATABASE/monsterability/Grab|Grab]]</span><span class="in-box-ability">**Ranged** <span class="action-icon">1</span> ejected glob +17 [+12/+7] (brutal, range increment 20 feet), **Damage** 3d6+6 bludgeoning plus 1d8 [[DATABASE/condition/Persistent Damage|persistent fire]] and cooling glob</span><span class="in-box-ability">**[[DATABASE/monsterability/Constrict|Constrict]]** <span class="action-icon">1</span> 1d8+6 bludgeoning plus 1d8 persistent fire, DC 24</span><span class="in-box-ability">**Cooling Glob** A fuming sludge's ejected globs cling to targets. A creature hit by an ejected glob Strike is [[DATABASE/condition/Encumbered|encumbered]] for 1 round. If the attack was a critical hit, the creature is instead [[DATABASE/condition/Restrained|restrained]] for 1 round ([[DATABASE/action/Escape|Escape]] DC 24).</span>

###  The Fires of Malice

Some fuming sludges are not created alchemically but arise spontaneously when the exceptionally spiteful die and are buried in swampy ground. Residual bits of ire from the spiteful soul remain within the decomposing corpse, eventually igniting into a fuming sludge. A fuming sludge that originates this way loses the mindless trait and immunity to mental damage, but its Strikes deal an additional 1d6 mental damage to creatures that injured it within the last minute.