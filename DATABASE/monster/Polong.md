---
ac: '24'
alignment: NE
all_resistance: '5'
charisma: '+6'
constitution: '+2'
creature_ability:
- Bottle Bound
- Natural Invisibility
- Polong Possession
- Regenerating Bond
- Rend
dexterity: '+6'
fly_speed: '35'
fortitude: '+12'
hp: 100 ( negative healing )
id: '1891'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- precision
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '+1'
language:
- any one language known by the polong's creator
level: '8'
max_speed: '35'
name: Polong
perception: '+17'
rarity: Uncommon
reflex: '+18'
resistance:
- all 5 (except [[DATABASE/trait/Force|force]]
- '[[DATABASE/equipment/Ghost Touch|ghost touch]]'
- or [[DATABASE/trait/Positive|positive]] ;double resistance vs. non- [[DATABASE/trait/Magical|magical]]
  )
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
- '[[DATABASE/monsterability/Lifesense|lifesense]] 30 feet'
size: Medium
skill:
- '[[DATABASE/skill/Deception|Deception]] +18'
- '[[DATABASE/skill/Medicine|Medicine]] +15'
- '[[DATABASE/skill/Occultism|Occultism]] +13'
- '[[DATABASE/skill/Stealth|Stealth]] +18'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- fly 35 feet
strength: '-5'
strength_req: '-5'
strongest_save:
- Will
trait:
- '[[DATABASE/trait/Incorporeal|Incorporeal]]'
- '[[DATABASE/trait/Spirit|Spirit]]'
- '[[DATABASE/trait/Uncommon|Uncommon]]'
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Fortitude
weakness:
- good 5
will: '+19'
wisdom: '+5'

---
# Polong

Polongs exist to serve their creators as loyal familiars, spies, and assassins. Their convenience makes them popular among the wicked, as each resides within a glass bottle which normally seems to contain only a small amount of red liquid. When addressed by their owner, a polong appears within their bottle as a tiny, beautiful humanoid drenched in blood. Forcing one to manifest outside the bottle reveals their true shape: a blood-soaked spirit with a hateful visage and sickle-shaped claws.
 The ritual to create a polong originated in Minata and is known primarily by Tian-Sing spellcasters, but only those willing to practice such evil. The ritualist must collect the blood of a murdered humanoid in a small bottle and perform daily incantations, which can take up to 14 days. Once the polong forms, they drink the blood of their creator every day, most often taken from a finger inserted into their bottle. At the master's order, a polong will travel up to 10 miles away to locate a particular person, possess them, and either slowly whittle them down via possession until they die, or force them to attack anyone nearby until someone slays the victim in self-defense.
**Recall Knowledge - Spirit ([[DATABASE/skill/Occultism|Occultism]])**: DC 26
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 26
**Unspecific Lore**: DC 24
**Specific Lore**: DC 21

# Polong<span class="item-type">Creature 8</span>

<span class="trait-uncommon item-trait">Uncommon</span><span class="trait-alignment item-trait">NE</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Incorporeal</span><span class="item-trait">Spirit</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Book of the Dead|Book of the Dead]]
**Perception** +17; [[DATABASE/monsterability/Darkvision|darkvision]], [[DATABASE/monsterability/Lifesense|lifesense]] 30 feet
**Languages** any one language known by the polong's creator
**Skills** [[DATABASE/skill/Deception|Deception]] +18, [[DATABASE/skill/Medicine|Medicine]] +15, [[DATABASE/skill/Occultism|Occultism]] +13, [[DATABASE/skill/Stealth|Stealth]] +18
**Str** -5, **Dex** +6, **Con** +2, **Int** +1, **Wis** +5, **Cha** +6
**Bottle Bound** A polong is bound to the bottle from which they spawned. They can leave the bottle only at the will of their master and must return to it once every 24 hours to feed on their creator's blood. Otherwise, the polong withers and dies.

---
**AC** 24; **Fort** +12, **Ref** +18, **Will** +19
**HP** 100 ([[DATABASE/monsterability/Negative Healing|negative healing]]); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, precision, [[DATABASE/condition/Unconscious|unconscious]]; **Resistances** all 5 (except force, [[DATABASE/equipment/Ghost Touch|ghost touch]], or positive; double resistance vs. non-magical); **Weaknesses** good 5
<span class="in-box-ability">**Natural Invisibility** A polong is naturally [[DATABASE/condition/Invisible|invisible]] outside of their bottle. They become visible only when forced out of a possessed creature against their will. Shattering the polong's bottle also forces them to assume a visible form.</span><span class="in-box-ability">**Regenerating Bond** (necromancy, occult) When a polong possesses a creature, the polong's master gains temporary Hit Points equal to the victim's level × the victim's [[DATABASE/condition/Drained|drained]] value caused by the possession. These temporary Hit Points last as long as the possession lasts.</span>

---
**Speed** fly 35 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> scythe claw +20 [+15/+10] (finesse, magical), **Damage** 2d4+9 slashing plus 1d6 negative</span><span class="in-box-ability">**Polong Possession** <span class="action-icon">3</span> (incapacitation, mental, necromancy, occult, possession) The polong attempts to possess an adjacent corporeal creature. This has the same effect as the [[DATABASE/spell/Possession|possession]] spell (DC 26 Will), except the duration is 24 hours and, since the polong doesn't have a physical body, they're unaffected by that restriction of the spell. If the target has critically failed its save and become fully possessed by this polong before, it gets a save result one degree of success worse than it rolled.
 A creature possessed by a polong becomes [[DATABASE/condition/Drained|drained 1]] and [[DATABASE/condition/Doomed|doomed 1]]. These conditions don't reduce naturally unless the polong spends an entire day without possessing the creature. For each consecutive day the polong is able to return and possess the creature, the drained and doomed values each increase by 1, to a maximum of 4. If the polong possesses a different creature, the conditions end for any creature it previously possessed.</span><span class="in-box-ability">**[[DATABASE/monsterability/Rend|Rend]]** <span class="action-icon">1</span> scythe claw</span>

###  Are You My Mommy?

A polong considers their creator to be their parent and refers to them as such. Thus, a cleric or exorcist who forces a polong out of their possessed victim often interrogates the spirit for their “parent's” name in order to apprehend the true mastermind.