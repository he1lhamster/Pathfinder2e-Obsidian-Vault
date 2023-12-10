---
ac: '22'
alignment: NE
all_resistance: null
burrow_speed: null
charisma: '+1'
climb_speed: null
constitution: '+1'
creature_ability:
- Bite Back
- Incessant Goading
creature_family: '[[DATABASE/monsterfamily/Beheaded|Beheaded]]'
dexterity: '+5'
element: null
fly_speed: '40'
fortitude: '+10'
hardness: null
hp: 80 ( negative healing )
id: '1840'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '+0'
land_speed: '15'
language:
- '[[DATABASE/language/Common|Common]]'
- '[[DATABASE/language/Necril|Necril]]'
level: '5'
max_speed: '40'
name: Taunting Skull
perception: '+13'
rarity: Common
reflex: '+14'
resistance: null
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Tiny
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +12'
- '[[DATABASE/skill/Intimidation|Intimidation]] +12'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- 15 feet
- fly 40 feet
spell: null
strength: '+1'
strength_req: '1'
strongest_save:
- Reflex
swim_speed: null
trait:
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Fortitude
weakness:
- '[[DATABASE/trait/Positive|positive]] 5'
will: '+11'
wisdom: '+4'

---
# Taunting Skull

Some beheaded are raised with their mental faculties mostly intact. These clever undead often provoke their victims into foolishly giving chase or harming themselves.
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 20
**Unspecific Lore**: DC 18
**Specific Lore**: DC 15

# Taunting Skull<span class="item-type">Creature 5</span>

<span class="trait-alignment item-trait">NE</span><span class="trait-size item-trait">Tiny</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Book of the Dead|Book of the Dead]]
**Perception** +13; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Common|Common]], [[DATABASE/language/Necril|Necril]]
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +12 (+14 to [[DATABASE/action/Maneuver in Flight|Maneuver in Flight]]), [[DATABASE/skill/Intimidation|Intimidation]] +12 (+14 to [[DATABASE/action/Demoralize|Demoralize]])
**Str** +1, **Dex** +5, **Con** +1, **Int** +0, **Wis** +4, **Cha** +1

---
**AC** 22; **Fort** +10, **Ref** +14, **Will** +11
**HP** 80 ([[DATABASE/monsterability/Negative Healing|negative healing]]); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, [[DATABASE/condition/Unconscious|unconscious]]; **Weaknesses** positive 5
<span class="in-box-ability">**Bite Back <span class="action-icon">5</span> ** **Trigger** The taunting skull is attacked by a creature within their reach; **Effect** The taunting skull makes a jaws Strike against that creature.</span>

---
**Speed** 15 feet, fly 40 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> jaws +14 [+10/+6] (agile, finesse, reach 0 feet), **Damage** 2d10+3 piercing</span><span class="in-box-ability">**Incessant Goading** <span class="action-icon">1</span> (auditory, emotion, incapacitation, mental) The skull chooses one creature within 60 feet and antagonizes it mercilessly. The target must attempt a DC 22 Will save to resist the effect.
 **Critical Success** The target is unaffected and is temporarily immune for 1 minute.
 **Success** The target is unaffected.
 **Failure** The target is [[DATABASE/condition/Flat-Footed|flat-footed]] for 1 round. On its next turn, if the taunting skull is within the target's reach, the target wildly attacks the taunting skull as many times as possible.
 **Critical Failure** As failure, but the target also immediately performs a Strike against itself; this Strike doesn't take any actions.</span>