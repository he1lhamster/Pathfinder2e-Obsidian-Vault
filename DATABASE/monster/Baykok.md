---
ac: '27'
alignment: CE
all_resistance: null
burrow_speed: null
charisma: '+1'
climb_speed: null
constitution: '+5'
creature_ability:
- Arrow of Despair
- Banished from the Ground
- Devour Life
- Frightful Presence
- Wasting Curse
creature_family: null
dexterity: '+4'
element: null
fly_speed: '40'
fortitude: '+20'
hardness: null
hp: 200 ( negative healing )
id: '1076'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '+0'
land_speed: '30'
language:
- '[[DATABASE/language/Common|Common]]'
level: '9'
max_speed: '40'
name: Baykok
perception: '+19'
rarity: Common
reflex: '+19'
resistance: null
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Medium
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +17'
- '[[DATABASE/skill/Athletics|Athletics]] +19'
- '[[DATABASE/skill/Stealth|Stealth]] +17'
source: '[[DATABASE/source/Bestiary 3|Bestiary 3]]'
speed:
- 30 feet
- fly 40 feet
spell: null
strength: '+6'
strength_req: '6'
strongest_save:
- Fortitude
swim_speed: null
trait:
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Will
weakness:
- air 10
- bludgeoning 10
- earth 10
will: '+15'
wisdom: '+4'

---
# Baykok

A baykok is the restless remnant of a warrior or hunter, cast out for evil acts and cursed to forever soar through the sky far from its home, unable to ever set foot on the ground again. The creature's despairing, lonely cries at night are audible for miles across the wilderness it haunts. Jealous rage drives it to hunt isolated humanoids, especially warriors and hunters who remind it of the life it once had and squandered. A baykok's invisible arrows carry its soul-freezing loneliness, and its envious touch can steal a helpless victim's vitality.
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 26
**Unspecific Lore**: DC 24
**Specific Lore**: DC 21

# Baykok<span class="item-type">Creature 9</span>

<span class="trait-alignment item-trait">CE</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Bestiary 3|Bestiary 3]]
**Perception** +19; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Common|Common]]
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +17, [[DATABASE/skill/Athletics|Athletics]] +19, [[DATABASE/skill/Stealth|Stealth]] +17
**Str** +6, **Dex** +4, **Con** +5, **Int** +0, **Wis** +4, **Cha** +1
**Banished from the Ground** A baykok can't willingly touch earth or rock surfaces. If forced into contact with such a surface, it becomes [[DATABASE/condition/Enfeebled|enfeebled 2]] for as long as it remains in contact.
**Items** _+1 [[DATABASE/weapon/Longbow|longbow]]_, _+1 [[DATABASE/equipment/Striking|striking]] [[DATABASE/weapon/Greatclub|greatclub]]_

---
**AC** 27; **Fort** +20, **Ref** +19, **Will** +15
**HP** 200 ([[DATABASE/monsterability/Negative Healing|negative healing]]); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, [[DATABASE/condition/Unconscious|unconscious]]; **Weaknesses** air 10, bludgeoning 10, earth 10
<span class="in-box-ability">**[[DATABASE/monsterability/Frightful Presence|Frightful Presence]]** (aura, emotion, fear, mental) 120 feet, DC 25</span>

---
**Speed** 30 feet, fly 40 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> _greatclub_ +21 [+16/+11] (backswing, magical, shove), **Damage** 2d10+9 bludgeoning</span><span class="in-box-ability">**Ranged** <span class="action-icon">1</span> _longbow_ +21 [+16/+11] (deadly d10, magical, volley 30 feet), **Damage** 1d8+6 piercing plus 1d8 mental and arrow of despair</span><span class="in-box-ability">**Arrow of Despair** (emotion, enchantment, fear, incapacitation, mental, occult) A baykok creates an invisible arrow of bone as it draws its bow. A [[DATABASE/condition/Frightened|frightened]] creature hit by the arrow is stricken with loneliness and despair and must attempt a DC 26 Will save; if the Strike was a critical hit, the target uses the outcome one degree of success worse than the result of its save. 
**Critical Success** The creature is unaffected. 
**Success** The creature is [[DATABASE/condition/Slowed|slowed 1]] for 1 round. 
**Failure** The creature's frightened value increases by 1 (to a maximum of 4), and it is slowed 1 until its frightened condition ends. 
**Critical Failure** As failure, but the creature is [[DATABASE/condition/Paralyzed|paralyzed]] until its frightened condition ends. At the start of each of its turns, it can end the paralyzed condition early with a successful DC 26 Will save.</span><span class="in-box-ability">**Devour Life** <span class="action-icon">1</span> (curse, necromancy, occult) **Requirements** The baykok is adjacent to a [[DATABASE/condition/Paralyzed|paralyzed]], [[DATABASE/condition/Restrained|restrained]], or [[DATABASE/condition/Unconscious|unconscious]] living humanoid; **Effect** The baykok touches the target and devours part of its life force. The target must succeed at a DC 26 Fortitude save or be afflicted with the baykok's wasting curse. If the target fails and wasn't already affected by the wasting curse, the baykok gains 20 temporary Hit Points that last for 1 hour.</span><span class="in-box-ability">**Wasting Curse** (curse, necromancy, occult) The baykok steals life from its victim and leaves listless dread in its place. If a target fails its save against Devour Life, it becomes [[DATABASE/condition/Drained|drained 1]]. Each time the target gets a full night's rest, it must succeed at a DC 26 Fortitude save or its drained value increases rather than decreasing. The curse ends if the creature recovers from the drained condition, but if the creature would reach drained 5 from this effect, it dies.</span>

###  Endless Exile

The wind that lets a baykok fly is also its prison, as it is cursed to be blown around forever without rest. The curse holds a baykok even after it's destroyed, as the wind tears away its bones except its skull, which falls to the ground. Its soul is trapped within until the skull is destroyed, the creature is restored to life, or the bones are reassembled to recreate the baykok. If trapped long enough, the soul can call out to sensitive individuals to beg for help.