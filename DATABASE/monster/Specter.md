---
ac: '25'
alignment: LE
all_resistance: '5'
burrow_speed: null
charisma: '+4'
climb_speed: null
constitution: '+4'
creature_ability:
- Frightful Presence
- Pain Starvation
- Spectral Corruption
- Sunlight Powerlessness
creature_family: null
dexterity: '+6'
element: null
fly_speed: '40'
fortitude: '+13'
hardness: null
hp: 95 ( negative healing )
id: '812'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- precision
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '+0'
land_speed: null
language:
- '[[DATABASE/language/Common|Common]]'
- '[[DATABASE/language/Necril|Necril]] ; [[DATABASE/monsterability/Telepathy|telepathy
  100 feet]] (with spectral thralls only)'
level: '7'
max_speed: '40'
name: Specter
perception: '+15'
rarity: Common
reflex: '+17'
resistance:
- all 5 (except force
- '[[DATABASE/equipment/Ghost Touch|ghost touch]]'
- or positive;double resistance vs. non-magical)
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Medium
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +17'
- '[[DATABASE/skill/Intimidation|Intimidation]] +15'
- '[[DATABASE/skill/Stealth|Stealth]] +17'
source: '[[DATABASE/source/Bestiary 2|Bestiary 2]]'
speed:
- fly 40 feet
spell: null
strength: '-5'
strength_req: '-5'
strongest_save:
- Reflex
swim_speed: null
trait:
- '[[DATABASE/trait/Incorporeal|Incorporeal]]'
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Fortitude
weakness: null
will: '+15'
wisdom: '+4'

---
# Specter

When an evil mortal creature dies, it sometimes returns to haunt the area of its death as a specter, a hateful remnant, always seeking to slay others—particularly humanoids—in an attempt to distribute its pain among as many souls as it can. A specter maintains a strange semblance of its prior identity, but with a corrupted sense of purpose. It cannot be reasoned with.
 A specter denied the opportunity to harm living humanoids grows increasingly agonized and irrational, akin to the mindset of a starving person forever denied a release from agony through death.
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 23
**Unspecific Lore**: DC 21
**Specific Lore**: DC 18

# Specter<span class="item-type">Creature 7</span>

<span class="trait-alignment item-trait">LE</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Incorporeal</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Bestiary 2|Bestiary 2]] 
**Perception** +15; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Common|Common]], [[DATABASE/language/Necril|Necril]]; [[DATABASE/monsterability/Telepathy|telepathy 100 feet]] (with spectral thralls only)
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +17, [[DATABASE/skill/Intimidation|Intimidation]] +15, [[DATABASE/skill/Stealth|Stealth]] +17
**Str** -5, **Dex** +6, **Con** +4, **Int** +0, **Wis** +4, **Cha** +4

---
**AC** 25; **Fort** +13, **Ref** +17, **Will** +15
**HP** 95 ([[DATABASE/monsterability/Negative Healing|negative healing]]); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, precision, [[DATABASE/condition/Unconscious|unconscious]]; **Resistances** all 5 (except force, [[DATABASE/equipment/Ghost Touch|ghost touch]], or positive; double resistance vs. non-magical)
<span class="in-box-ability">**[[DATABASE/monsterability/Frightful Presence|Frightful Presence]]** (aura, emotion, fear, mental) 30 feet, DC 22</span><span class="in-box-ability">**Pain Starvation** A specter that goes for more than a month without dealing negative damage to a living humanoid becomes desperate and almost feral. It changes alignment from lawful evil to chaotic evil, loses control of any corrupted thralls it might have, and becomes [[DATABASE/condition/Quickened|quickened]]. It can use its additional action only to make vile touch Strikes against humanoid targets. At the end of any turn in which it deals any amount of negative damage to a living humanoid, it reverts to lawful evil and is no longer quickened, but any thralls it lost control of remain free.</span><span class="in-box-ability">**Sunlight Powerlessness** A specter caught in sunlight is [[DATABASE/condition/Clumsy|clumsy 2]] and [[DATABASE/condition/Slowed|slowed 2]] for as long as it remains in the sunlight.</span>

---
**Speed** fly 40 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> vile touch +16 [+11/+6] (finesse), **Damage** 2d8+8 negative</span><span class="in-box-ability">**Spectral Corruption** <span class="action-icon">2</span> (curse, divine, enchantment, incapacitation, mental) The specter makes a vile touch Strike. If it damages a living creature, the specter gains 5 temporary Hit Points and the target creature must attempt a DC 24 Will save to avoid becoming corrupted. 
**Critical Success** The creature is unaffected and is temporarily immune to spectral corruption for 1 minute. 
**Success** The creature is [[DATABASE/condition/Stupefied|stupefied 2]] for 1 hour. 
**Failure** The creature succumbs to the corruption and becomes a spectral thrall temporarily. The creature is [[DATABASE/condition/Controlled|controlled]] by the specter, obeying the specter's telepathic or spoken orders, though a spectral thrall does not obey obviously self-destructive orders. This lasts until the end of the thrall's next turn, at which point it is no longer controlled but becomes stupefied 2 for 1 hour. 
**Critical Failure** As failure, but the duration is unlimited. The thrall can attempt a new Will save at the end of each of its turns; on a success, it is no longer controlled by the specter but becomes stupefied 2 for 1 hour.</span>

###  Spectral Thralls

Specters often keep a few humanoid thralls to torment, preventing the agony of pain starvation, but since they can't minimize the negative damage they inflict with their vile touch, humanoid thralls who are too low level generally don't last long.