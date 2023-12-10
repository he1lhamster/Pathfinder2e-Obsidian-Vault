---
ac: '23'
alignment: N
all_resistance: '5'
charisma: '+4'
constitution: '+0'
creature_ability:
- Feed on the Living
- Living Visage
- Ravenous Undoing
- Rejuvenation
creature_family: '[[DATABASE/monsterfamily/Ghost|Ghost]]'
dexterity: '+5'
fly_speed: '25'
fortitude: '+12'
hp: 60 ( negative healing , rejuvenation)
id: '1863'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- precision
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '+4'
language:
- '[[DATABASE/language/Common|Common]]'
- '[[DATABASE/language/Necril|Necril]] ; one other language'
level: '6'
max_speed: '25'
name: Hungry Ghost
perception: '+13'
rarity: Common
reflex: '+17'
resistance:
- all damage 5 (except [[DATABASE/trait/Force|force]]
- '[[DATABASE/equipment/Ghost Touch|ghost touch]]'
- or [[DATABASE/trait/Positive|positive]] ; double resistance vs. non- [[DATABASE/trait/Magical|magical]]
  )
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Medium
skill:
- '[[DATABASE/skill/Deception|Deception]] +14'
- '[[DATABASE/skill/Diplomacy|Diplomacy]] +14'
- '[[DATABASE/skill/Lore|Ghost Lore]] +18'
- '[[DATABASE/skill/Religion|Religion]] +17'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- fly 25 feet
strength: '-5'
strength_req: '-5'
strongest_save:
- Reflex
trait:
- '[[DATABASE/trait/Ghost|Ghost]]'
- '[[DATABASE/trait/Incorporeal|Incorporeal]]'
- '[[DATABASE/trait/Spirit|Spirit]]'
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Fortitude
will: '+15'
wisdom: '+5'

---
# Hungry Ghost

Hungry ghosts arise from those who didn't receive proper burials or whose graves were neglected. They are not bound to a site or item but are compelled to see opportunities to commit good deeds in hopes of gaining favors that can aid them in achieving a final rest. Their need to feed on living energy often conflicts with this goal, however.
**Recall Knowledge - Spirit ([[DATABASE/skill/Occultism|Occultism]])**: DC 22
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 22
**Unspecific Lore**: DC 20
**Specific Lore**: DC 17

# Hungry Ghost<span class="item-type">Creature 6</span>

<span class="trait-alignment item-trait">N</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Ghost</span><span class="item-trait">Incorporeal</span><span class="item-trait">Spirit</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Book of the Dead|Book of the Dead]]
**Perception** +13; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Common|Common]], [[DATABASE/language/Necril|Necril]]; one other language
**Skills** [[DATABASE/skill/Deception|Deception]] +14, [[DATABASE/skill/Diplomacy|Diplomacy]] +14, [[DATABASE/skill/Lore|Ghost Lore]] +18, [[DATABASE/skill/Religion|Religion]] +17
**Str** -5, **Dex** +5, **Con** +0, **Int** +4, **Wis** +5, **Cha** +4
**Living Visage** While they have more than 30 HP, the hungry ghost appears to be a living creature. They have an automatic result of 34 on [[DATABASE/skill/Deception|Deception]] checks and DCs to conceal their undead status and can Feed on the Living covertly (below).

---
**AC** 23; **Fort** +12, **Ref** +17, **Will** +15
**HP** 60 ([[DATABASE/monsterability/Negative Healing|negative healing]], rejuvenation); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, precision, [[DATABASE/condition/Unconscious|unconscious]]; **Resistances** all damage 5 (except force, [[DATABASE/equipment/Ghost Touch|ghost touch]], or positive; double resistance vs. non-magical)
<span class="in-box-ability">**Ravenous Undoing** In each 24-hour period, the hungry ghost must use Feed on the Living to consume 30 HP (any HP the ghost would gain count toward this total, even if the ghost has enough HP that they don't actually regain the full amount). If the ghost hasn't consumed enough HP, they mindlessly and recklessly feed on any living creature they come across until satiated.</span><span class="in-box-ability">**Rejuvenation** (divine, necromancy) When destroyed, hungry ghosts reform after 2d4 days fully healed at whatever location they were at when last destroyed. They're only permanently destroyed when they have been given a proper burial, have had their grave cleaned and maintained for at least a year, or have been judged to be redeemed by [[DATABASE/deity/Pharasma|Pharasma]].</span>

---
**Speed** fly 25 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> ghostly touch +17 [+13/+9] (agile, finesse, magical), **Damage** 2d8+4 negative</span><span class="in-box-ability">**Feed on the Living** <span class="action-icon">2</span> (divine, necromancy, negative) The hungry ghost touches a creature in reach. If the target is a living creature it takes damage from the ghost's ghostly touch with a DC 24 Fortitude save. If the ghost is in their living visage they can disguise Feed on the Living as a benign touch and delay the effects for 1 minute while keeping the target unaware of the effect. A creature can be affected by only one delayed Feed on the Living at a time and if the ghost loses their living visage during that minute the Feed on the Living is lost.
 **Critical Success** The target's life energy overpowers the ghost. The hungry
ghost takes 5 positive damage, and the target is unaffected.
**Success** The target takes half damage, and the hungry ghost regains HP equal to the damage dealt.
**Failure** The target takes full damage and is [[DATABASE/condition/Enfeebled|enfeebled 1]] for 1 minute and the hungry ghost regains HP equal to the damage dealt.
 **Critical Failure** The target takes double damage and is enfeebled 2 for 1 minute and the hungry ghost regains HP equal to the damage dealt.</span>