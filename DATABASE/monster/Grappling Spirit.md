---
ac: '27'
alignment: LN
all_resistance: '10'
burrow_speed: null
charisma: '+5'
climb_speed: null
constitution: '+4'
creature_ability:
- Ghostly Grasp
- Submission Lock
- Teleporting Clothesline
- Victory Celebration
- Warrior's Mask
creature_family: null
dexterity: '+6'
element: null
fly_speed: '60'
fortitude: '+19'
hardness: null
hp: 125 ( negative healing )
id: '1868'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- precision
- '[[DATABASE/spell/Sleep|sleep]]'
intelligence: '+0'
land_speed: null
language:
- '[[DATABASE/language/Common|Common]]'
level: '9'
max_speed: '60'
name: Grappling Spirit
perception: '+17'
rarity: Uncommon
reflex: '+19'
resistance:
- all damage 10 (except [[DATABASE/trait/Force|force]]
- '[[DATABASE/equipment/Ghost Touch|ghost touch]]'
- or [[DATABASE/trait/Positive|positive]] ; double resistance vs. non- [[DATABASE/trait/Magical|magical]]
  )
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Medium
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +19'
- '[[DATABASE/skill/Athletics|Athletics]] +21'
- '[[DATABASE/skill/Diplomacy|Diplomacy]] +18'
- '[[DATABASE/skill/Lore|Gladiatorial Lore]] +15'
- '[[DATABASE/skill/Intimidation|Intimidation]] +20'
- '[[DATABASE/skill/Performance|Performance]] +20'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- fly 60 feet
spell: null
strength: '-5'
strength_req: '-5'
strongest_save:
- Fortitude
- Reflex
swim_speed: null
trait:
- '[[DATABASE/trait/Incorporeal|Incorporeal]]'
- '[[DATABASE/trait/Spirit|Spirit]]'
- '[[DATABASE/trait/Uncommon|Uncommon]]'
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Will
weakness: null
will: '+15'
wisdom: '+2'

---
# Grappling Spirit

When a great gladiator or wrestler meets their demise, their soul can sometimes linger out of a love for combat and sport. Every grappling spirit manifests a mask that represents the legacy of the warrior they were during their life.
**Recall Knowledge - Spirit ([[DATABASE/skill/Occultism|Occultism]])**: DC 28
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 28
**Unspecific Lore**: DC 26
**Specific Lore**: DC 23

# Grappling Spirit<span class="item-type">Creature 9</span>

<span class="trait-uncommon item-trait">Uncommon</span><span class="trait-alignment item-trait">LN</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Incorporeal</span><span class="item-trait">Spirit</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Book of the Dead|Book of the Dead]]
**Perception** +17; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Common|Common]]
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +19, [[DATABASE/skill/Athletics|Athletics]] +21, [[DATABASE/skill/Diplomacy|Diplomacy]] +18, [[DATABASE/skill/Lore|Gladiatorial Lore]] +15, [[DATABASE/skill/Intimidation|Intimidation]] +20, [[DATABASE/skill/Performance|Performance]] +20
**Str** -5, **Dex** +6, **Con** +4, **Int** +0, **Wis** +2, **Cha** +5

---
**AC** 27; **Fort** +19, **Ref** +19, **Will** +15
**HP** 125 ([[DATABASE/monsterability/Negative Healing|negative healing]]); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, precision, [[DATABASE/spell/Sleep|sleep]]; **Resistances** all damage 10 (except force, [[DATABASE/equipment/Ghost Touch|ghost touch]], or positive; double resistance vs. non-magical)
<span class="in-box-ability">**Warrior's Mask** A grappling spirit wears a mask that allows them to abandon their original form and become a warrior focused solely on combat. This mask is quasi-corporeal, allowing it to be manipulated by both corporeal and incorporeal creatures. A creature who has the grappling spirit [[DATABASE/condition/Grabbed|grabbed]] or [[DATABASE/condition/Restrained|restrained]] can remove the mask as an Interact action by succeeding at an [[DATABASE/skill/Athletics|Athletics]] check against the grappling spirit's Fortitude DC. Removing a grappling spirit's mask causes the spirit to fly into a frenzy. The grappling spirit becomes [[DATABASE/condition/Quickened|quickened]] and can use their extra action to [[DATABASE/action/Fly|Fly]], [[DATABASE/action/Grapple|Grapple]], or Strike. They also gain a +4 status bonus to damage rolls, and they take a –4 status penalty to AC and Reflex saving throws. If the mask is put back on, the grappling spirit ends their frenzy.</span>

---
**Speed** fly 60 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> ghostly hand +21 [+17/+13] (agile, finesse, magical, nonlethal), **Damage** 2d10+12 negative plus [[DATABASE/monsterability/Improved Grab|Improved Grab]]</span><span class="in-box-ability">**Ghostly Grasp** A grappling spirit can [[DATABASE/action/Grapple|Grapple]] corporeal creatures despite being incorporeal. The grappling spirit uses their [[DATABASE/skill/Athletics|Athletics]] check to Grapple as normal but can't use Athletics for other actions that require corporeal contact, like [[DATABASE/action/Force Open|Force Open]] or [[DATABASE/action/Trip|Trip]].</span><span class="in-box-ability">**Submission Lock** <span class="action-icon">2</span> (nonlethal) **Requirements** The grappling spirit has a creature [[DATABASE/condition/Grabbed|grabbed]] or [[DATABASE/condition/Restrained|restrained]]; **Effect** The spirit saps their opponent's strength with a supernatural grip. The grappling spirit attempts an [[DATABASE/skill/Athletics|Athletics]] check to [[DATABASE/action/Grapple|Grapple]] a creature they have grabbed or restrained, also adding 4d10+12 negative damage, depending on the result.
 **Critical Success** The creature takes double damage. If it's already [[DATABASE/condition/Enfeebled|enfeebled]], it falls [[DATABASE/condition/Unconscious|unconscious]]. If not, it is enfeebled 2 until the end of its next turn and enfeebled 1 for 1 minute.
 **Success** The creature takes full damage and is enfeebled 1 until the end of its next turn.</span><span class="in-box-ability">**Teleporting Clothesline** <span class="action-icon">2</span> (conjuration, occult, teleportation) **Requirements** The grappling spirit has a creature [[DATABASE/condition/Grabbed|grabbed]] or [[DATABASE/condition/Restrained|restrained]]; Effect The grappling spirit pushes the creature 15 feet in a straight line. The spirit immediately teleports 20 feet to intercept. They make a ghostly hand Strike against the creature. On a hit, the creature is knocked [[DATABASE/condition/Prone|prone]], and on a critical hit, it also takes an additional 2d6 bludgeoning damage as it's driven to the ground.</span><span class="in-box-ability">**Victory Celebration** If a spirit knocks a creature [[DATABASE/condition/Unconscious|unconscious]], each creature within 60 feet that witnesses the victory is targeted with a DC 26 [[DATABASE/spell/Roaring Applause|roaring applause]] spell. The spirit must spend all their actions until the end of the turn celebrating, and a new medal or belt appears on the spirit.</span>

###  Lands of Champions

While a grappling spirit can be found almost anywhere notable combats are held, a few regions on Golarion are known for their prominence. The Hold of Belkzen is home to orc grapplers who become grappling spirits, while the wrestlers of Arcadia and Iblydos tend to return for one last glorious match. Grappling spirits are particularly common in the Lands of Second Souls in southern Arcadia.

###  Retiring a Grappling Spirit

The means of appeasing each grappling spirit, allowing it to pass on, vary. Some seek one last match worthy of their skill, while others wish to win a major bout in front of an adoring crowd or even suffer an epic defeat at the hands of a worthy successor. They tend not to be malicious, just entirely dedicated to competition.