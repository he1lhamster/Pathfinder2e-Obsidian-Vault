---
ac: '35'
alignment: CE
all_resistance: null
burrow_speed: null
charisma: '+8'
climb_speed: null
constitution: '+4'
creature_ability:
- Burning
- Crushing
- Dislocation
- Drowning
- Endless Suffering
- Impalement
- Scream in Agony
- ''
- Starvation
- Tortured Gaze
creature_family: null
dexterity: '+4'
element: null
fly_speed: '25'
fortitude: '+22'
hardness: null
hp: 250 ( negative healing )
id: '1907'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '-1'
land_speed: '25'
language:
- '[[DATABASE/language/Aklo|Aklo]]'
- '[[DATABASE/language/Common|Common]]'
- '[[DATABASE/language/Necril|Necril]]'
level: '14'
max_speed: '25'
name: Tormented
perception: '+27'
rarity: Common
reflex: '+26'
resistance: null
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
- '[[DATABASE/monsterability/Lifesense|lifesense]] 60 feet'
size: Medium
skill:
- '[[DATABASE/skill/Athletics|Athletics]] +26'
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +24'
- '[[DATABASE/skill/Intimidation|Intimidation]] +28'
- '[[DATABASE/skill/Stealth|Stealth]] +24'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- 25 feet
- fly 25 feet
spell: null
strength: '+6'
strength_req: '6'
strongest_save:
- Will
swim_speed: null
trait:
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Fortitude
weakness:
- endless suffering 10
will: '+27'
wisdom: '+5'

---
# Tormented

Twisted caricatures of living beings, tormented arise from the remains of those who've been tortured to death. They appear as the mortals they were in life, horribly disfigured by acts of cruelty. Unable to rest, they haunt the sites of their deaths, doomed to relive their last moments of agony. The toxic psychic residue of their death is so great it spills over, afflicting anyone who meets the tormented's haunted gaze.
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 32
**Unspecific Lore**: DC 30
**Specific Lore**: DC 27

# Tormented<span class="item-type">Creature 14</span>

<span class="trait-alignment item-trait">CE</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Book of the Dead|Book of the Dead]]
**Perception** +27; [[DATABASE/monsterability/Darkvision|darkvision]], [[DATABASE/monsterability/Lifesense|lifesense]] 60 feet
**Languages** [[DATABASE/language/Aklo|Aklo]], [[DATABASE/language/Common|Common]], [[DATABASE/language/Necril|Necril]]
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +24, [[DATABASE/skill/Athletics|Athletics]] +26, [[DATABASE/skill/Intimidation|Intimidation]] +28, [[DATABASE/skill/Stealth|Stealth]] +24
**Str** +6, **Dex** +4, **Con** +4, **Int** -1, **Wis** +5, **Cha** +8

---
**AC** 35; **Fort** +22, **Ref** +26, **Will** +27
**HP** 250 ([[DATABASE/monsterability/Negative Healing|negative healing]]), regeneration 10 (deactivated by a type listed in endless suffering); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, [[DATABASE/condition/Unconscious|unconscious]]; **Weaknesses** endless suffering 10
<span class="in-box-ability">**Endless Suffering** The type of torture that killed a tormented determines the effect of their Tortured Gaze, as listed below. The damage type listed in parentheses deactivates their regeneration and is their damage weakness. The most common tortured deaths are as follows.

* **Burning** (fire) The tormented perished by fire and brand. The target takes 6d6 fire damage and is wreathed in ghostly flames for 1 minute, negating its [[DATABASE/condition/Concealed|concealed]] condition and rendering it concealed if it would be [[DATABASE/condition/Invisible|invisible]].
* **Crushing** (bludgeoning) The tormented was crushed or broken on the wheel. The target takes 4d8 bludgeoning damage and is knocked [[DATABASE/condition/Prone|prone]].
* **Dislocation** (bludgeoning) The tormented had their limbs repeatedly broken or dislocated. For 1d4 rounds, the target is [[DATABASE/condition/Clumsy|clumsy 2]] and [[DATABASE/condition/Slowed|slowed 1]].
* **Drowning** (cold) The tormented was repeatedly drowned, held underwater and pulled back at the last instant. The target takes 4d6 cold damage and is [[DATABASE/condition/Sickened|sickened 2]].
* **Impalement** (piercing) The tormented was pierced with spears or blades and left to slowly die. The target takes 8d4 [[DATABASE/condition/Persistent Damage|persistent bleed damage]]. (The creature doesn't take the persistent damage this turn, nor does it get its flat check to end the damage.)
* **Starvation** (cold) The tormented starved to death, denied food until the end. For 1 minute, the target is [[DATABASE/condition/Enfeebled|enfeebled 2]] and [[DATABASE/condition/Fatigued|fatigued]].

**Tortured Gaze** (aura, divine, illusion, mental) 30 feet, or 60 feet if the tormented is at 125 HP or lower. The psychic agony of a tormented spills into the world around them, inflicting murderous hallucinations replicating the tormented's last moments. A non-undead creature that ends its turn in the aura must succeed at a DC 32 Will save or take the effect listed under Endless Suffering. While it has a condition from Tortured Gaze, a creature can't gain a new condition from the aura but can take damage from it again.</span>

---
**Speed** 25 feet, fly 25 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> painful touch +28 [+24/+20] (agile, finesse, magical), **Damage** 4d6+14 mental plus 2d6 [[DATABASE/condition/Persistent Damage|persistent mental damage]]</span><span class="in-box-ability">**Scream in Agony** <span class="action-icon">2</span> (auditory, divine, enchantment, mental) Each creature in the tormented's Tortured Gaze aura takes 14d6 mental damage (DC 34 basic Will save). A creature that fails is also [[DATABASE/condition/Sickened|sickened 1]] (or sickened 2 on a critical failure). The tormented can't Scream in Agony again for 1d4 rounds, but recharges the ability whenever they take damage from an attacker's critical hit or their own critical failure on a saving throw</span>

###  Tormented In Golarion

Tormented are most commonly encountered in places where torture and painful execution is a public spectacle, as if the act of witnessing strengthens the psychic horror that creates such entities. They are most common in Cheliax and Nidal, where public torture is considered high art, though the necromancers of Geb are said to use carefully bound tormented as personal torturers.