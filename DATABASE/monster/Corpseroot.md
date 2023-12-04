---
ac: '30'
alignment: NE
all_resistance: null
burrow_speed: null
charisma: '+2'
climb_speed: null
constitution: '+5'
creature_ability:
- Axe Vulnerability
- Blight
- Plant
- Take Root
creature_family: null
description: 'Corpseroots are rotten, undead trees that grow bright-red poisonous
  fruit and spread blight to surrounding plants, transforming healthy trees into new
  corpseroots. These cunning killers drain the life from creatures through their root
  systems, posing as dead trees until their victims come within reach. <br/><br/>Corpseroots
  most commonly form from rotten husks of trees that died from supernatural blights,
  making them common threats in the Fangwood and Fierani forests. The most powerful
  are ancient trees used as shrines and sacrificial altars, their roots absorbing
  the blood, flesh, and terror of those condemned under their boughs. Some of these
  ancient corpseroots still command the respect and devotion of the cults that inadvertently
  created them.<br/><br/><b><u>Recall Knowledge - Undead</u> ( [[DATABASE/skill/Religion|Religion]]
  )</b>: DC 28<br/><b><u>Unspecific Lore</u></b>: DC 26<br/><b><u>Specific Lore</u></b>:
  DC 23'
dexterity: '+3'
element: null
fly_speed: null
fortitude: '+24'
hardness: null
hp: 225 ( negative healing )
id: '1847'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '-2'
land_speed: '20'
language:
- '[[DATABASE/language/Arboreal|Arboreal]]'
- '[[DATABASE/language/Necril|Necril]]'
- '[[DATABASE/language/Sylvan|Sylvan]] ; (can''t speak anylanguage)'
level: '11'
max_speed: '20'
name: Corpseroot
perception: '+18'
rarity: Common
reflex: '+18'
resistance:
- bludgeoning 10
- piercing 10
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Huge
skill:
- '[[DATABASE/skill/Athletics|Athletics]] +24'
- '[[DATABASE/skill/Stealth|Stealth]] +18'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- 20 feet
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
- Will
weakness:
- axe vulnerability
- '[[DATABASE/trait/Fire|fire]] 10'
will: '+18'
wisdom: '+3'

---
# Corpseroot

Corpseroots are rotten, undead trees that grow bright-red poisonous fruit and spread blight to surrounding plants, transforming healthy trees into new corpseroots. These cunning killers drain the life from creatures through their root systems, posing as dead trees until their victims come within reach. 
Corpseroots most commonly form from rotten husks of trees that died from supernatural blights, making them common threats in the Fangwood and Fierani forests. The most powerful are ancient trees used as shrines and sacrificial altars, their roots absorbing the blood, flesh, and terror of those condemned under their boughs. Some of these ancient corpseroots still command the respect and devotion of the cults that inadvertently created them.
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 28
**Unspecific Lore**: DC 26
**Specific Lore**: DC 23

# Corpseroot<span class="item-type">Creature 11</span>

<span class="trait-alignment item-trait">NE</span><span class="trait-size item-trait">Huge</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Book of the Dead|Book of the Dead]]
**Perception** +18; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Arboreal|Arboreal]], [[DATABASE/language/Necril|Necril]], [[DATABASE/language/Sylvan|Sylvan]]; (can't speak any language)
**Skills** [[DATABASE/skill/Athletics|Athletics]] +24, [[DATABASE/skill/Stealth|Stealth]] +18
**Str** +7, **Dex** +3, **Con** +5, **Int** -2, **Wis** +3, **Cha** +2
**Plant** When it isn't in danger, the corpseroot spends 1 minute rooting to the earth, becoming planted in place. While the corpseroot is planted and immobile, creatures must actively [[DATABASE/action/Seek|Seek]] and succeed at a DC 36 Perception check (DC 40 in forests) to detect the corpseroot's true nature.

---
**AC** 30; **Fort** +24, **Ref** +18, **Will** +18
**HP** 225 ([[DATABASE/monsterability/Negative Healing|negative healing]]); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, [[DATABASE/condition/Unconscious|unconscious]]; **Resistances** bludgeoning 10, piercing 10; **Weaknesses** axe vulnerability, fire 10
<span class="in-box-ability">**Axe Vulnerability** The corpseroot takes 10 additional damage from [[DATABASE/weapongroup/Axe|axes]].</span><span class="in-box-ability">**Blight** (aura, necromancy, poison, primal) 30 feet. A plant entering or starting its turn in the corpseroot's aura begins to wither and must succeed at a DC 27 Fortitude save or become [[DATABASE/condition/Sickened|sickened 2]] (sickened 4 on a critical failure). A plant that succeeds is temporarily immune for 1 minute.</span><span class="in-box-ability"> A plant that stays in the aura for 7 consecutive days must succeed at a DC 27 Fortitude save or die. If the plant was a creature or tree, it rises as a corpseroot. The newly risen corpseroot can't create more corpseroots but has all other corpseroot abilities. Plants that are neither magical nor creatures automatically fail saves against blight.</span>

---
**Speed** 20 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> branch +24 [+19/+14] (reach 15 feet), **Damage** 3d12+10 bludgeoning</span><span class="in-box-ability">**Melee** <span class="action-icon">1</span> root +24 [+20/+16] (agile, reach 20 feet, trip), **Damage** 3d8+10 bludgeoning plus [[DATABASE/monsterability/Grab|Grab]]</span><span class="in-box-ability">**Ranged** <span class="action-icon">1</span> rotten fruit +20 [+15/+10] (range increment 20 feet, splash), **Damage** 3d4+7 bludgeoning plus 2d6 poison splash damage</span><span class="in-box-ability">**Take Root** <span class="action-icon">1</span> (necromancy, primal) **Frequency** once per round; **Requirements** The corpseroot has a creature [[DATABASE/condition/Grabbed|grabbed]] or [[DATABASE/condition/Restrained|restrained]]; **Effect** The corpseroot buries its roots into the creature, dealing 1d6+11 piercing damage and draining the target's life force (DC 30 basic Fortitude save). On a failure, the creature is [[DATABASE/condition/Drained|drained 1]] (or increases the value by 1 if already drained), and the corpseroot regains 10 HP. If this would make a creature drained 5, the creature dies.</span>

###  Fearsome Foes

Although they lack the intelligence of most humanoids, corpseroots are cunning and understand the languages of their two most hated foes, [[DATABASE/monsterfamily/Arboreal|arboreals]] and fey, both of whom strike against corpseroots upon discovering them. Most corpseroots strive to avoid the notice of these enemies by blending in among other dead plants and remaining immobile whenever arboreal or fey hunters pass by.