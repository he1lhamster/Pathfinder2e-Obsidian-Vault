---
ac: '28'
alignment: NE
all_resistance: null
burrow_speed: null
charisma: '+3'
climb_speed: null
constitution: '+5'
creature_ability:
- Agonized Howl
- Awful Approach
- Death Grip
- Meant to Live
- Resurrection Vulnerability
- Rise
- Again
creature_family: null
description: "An unrisen is a mangled conglomeration of splintered bones, decaying\
  \ organs, and rotting flesh, created when a ritual such as [[DATABASE/ritual/Resurrect|resurrect]]\
  \ goes catastrophically wrong. Immense care must be taken, for if the ritual is\
  \ a critical failure, an unrisen can be the result\u2014as many a ritualist has\
  \ learned to their horror. <br/><br/>Unrisen are barely intelligent, aware only\
  \ of the agony constantly inflicted by their flawed creation and their resentment\
  \ for the living. They tend to attack the casters involved in the botched ritual\
  \ first before lashing out at everyone else around them. Though an unrisen's twisted\
  \ form is unrecognizable as the intended target of the resurrection, its wordless\
  \ howls are often disturbingly similar to the deceased's voice. If an unrisen is\
  \ destroyed before it can rise again, it's reduced to a handful of metallic blue-green\
  \ salts referred to as essential salts.<br/><br/><b><u>Recall Knowledge - Undead</u>\
  \ ( [[DATABASE/skill/Religion|Religion]] )</b>: DC 28<br/><b><u>Unspecific Lore</u></b>:\
  \ DC 26<br/><b><u>Specific Lore</u></b>: DC 23"
dexterity: '+4'
element: null
fly_speed: null
fortitude: '+22'
hardness: null
hp: 220 (meant to live, negative healing )
id: '1908'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '-2'
land_speed: '30'
language:
- '[[DATABASE/language/Common|Common]] ; (can''t speak any language)'
level: '11'
max_speed: '30'
name: Unrisen
perception: '+21'
rarity: Common
reflex: '+17'
resistance: null
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
- '[[DATABASE/monsterability/Lifesense|lifesense]] 30 feet'
size: Medium
skill:
- '[[DATABASE/skill/Athletics|Athletics]] +24'
- '[[DATABASE/skill/Stealth|Stealth]] +19'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- 30 feet
spell: null
strength: '+7'
strength_req: '7'
strongest_save:
- Fortitude
swim_speed: null
trait:
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Reflex
weakness:
- resurrection vulnerability
will: '+21'
wisdom: '+6'

---
# Unrisen

An unrisen is a mangled conglomeration of splintered bones, decaying organs, and rotting flesh, created when a ritual such as [[Resurrect]] goes catastrophically wrong. Immense care must be taken, for if the ritual is a critical failure, an unrisen can be the result—as many a ritualist has learned to their horror. 
Unrisen are barely intelligent, aware only of the agony constantly inflicted by their flawed creation and their resentment for the living. They tend to attack the casters involved in the botched ritual first before lashing out at everyone else around them. Though an unrisen's twisted form is unrecognizable as the intended target of the resurrection, its wordless howls are often disturbingly similar to the deceased's voice. If an unrisen is destroyed before it can rise again, it's reduced to a handful of metallic blue-green salts referred to as essential salts.
**Recall Knowledge - Undead ([[Religion]])**: DC 28
**Unspecific Lore**: DC 26
**Specific Lore**: DC 23

# Unrisen<span class="item-type">Creature 11</span>

<span class="trait-alignment item-trait">NE</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Undead</span>
**Source** [[Book of the Dead]]
**Perception** +21; [[Darkvision]], [[Lifesense]] 30 feet
**Languages** [[Common]]; (can't speak any language)
**Skills** [[Athletics]] +24, [[Stealth]] +19
**Str** +7, **Dex** +4, **Con** +5, **Int** -2, **Wis** +6, **Cha** +3

---
**AC** 28; **Fort** +22, **Ref** +17, **Will** +21
**HP** 220 (meant to live, [[Negative Healing]]); **Immunities** death effects, disease, [[Paralyzed]], poison, [[Unconscious]]; **Weaknesses** resurrection vulnerability
<span class="in-box-ability">**Meant to Live** (occult, necromancy) Whenever an unrisen would take damage from positive energy, it instead heals half that number of Hit Points.</span><span class="in-box-ability">**Resurrection Vulnerability** A creature with a prepared or spontaneous spell that can restore the dead to life (such as [[Breath of Life]] or [[Raise Dead]]) can expend an appropriate spell slot as a 2-action activity to destroy an unrisen within 30 feet. The attempt fails if the unrisen succeeds at a Will save against the creature's spell DC.</span><span class="in-box-ability">**Rise Again** (necromancy, occult) If the unrisen is reduced to 0 Hit Points by means other than fire damage, disintegration, or its resurrection vulnerability, it returns to unlife at the start of its next turn. It has 100 Hit Points and is [[Prone]] in the space in which it was destroyed. The unrisen can't be returned by this ability again for 1 hour.</span>

---
**Speed** 30 feet
<span class="in-box-ability">**Melee**jaws +24 [+19/+14] (deadly d10, magical), **Damage** 3d8+13 piercing plus [[Grab]]</span><span class="in-box-ability">**Melee**claw +24 [+20/+16] (agile, magical), **Damage** 2d8+13 slashing plus [[Grab]]</span><span class="in-box-ability">**Agonized Howl** <span class="action-icon">2</span> (auditory, enchantment, mental, occult) The unrisen howls in pain at its cursed existence. Creatures within a 30-foot emanation take 9d8 mental damage (DC 30 basic Will save). The unrisen can't use Agonized Howl again for 1d4 rounds.</span><span class="in-box-ability">**Awful Approach** <span class="action-icon">1</span> The unrisen reshapes its grotesque form to move swiftly. It Strides twice. Any living creature that can see the unrisen during this movement must succeed at a DC 28 Fortitude save or be [[Sickened]] (sickened 2 on a critical failure). This is a mental and visual effect. The unrisen can't use Awful Approach again for 1d4 rounds.</span><span class="in-box-ability">**Death Grip** <span class="action-icon">1</span> (curse, necromancy, occult) **Requirements** The unrisen has a living creature [[Grabbed]] or [[Restrained]]; **Effect** The unrisen attempts to destroy its victim's life force to share the unrisen's fate. The creature must succeed at a DC 30 Fortitude save or become [[Doomed]]. While the curse lasts, the creature regains only half as many HP from positive healing effects; if it dies, any attempt to raise it from the dead causes it to return as an unrisen. The curse ends automatically if the creature's doomed value is reduced to 0.</span>

###  Unrisen Salts

An unrisen's essential salts, formed from its remaining distilled life essence, can be used for spells and rituals such as [[Raise Dead]] or [[Resurrect]], replacing 600 gp worth of diamonds. The existence of these essential salts doesn't damage the soul of the unrisen's source creature, but devout [[Pharasma]] still frown on its use.