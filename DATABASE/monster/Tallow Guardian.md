﻿---
ac: '23'
alignment: N
charisma: '-5'
constitution: '+2'
creature_ability:
- Encase
- Melt
- Molten Wax
- Slowed by Cold
dexterity: '+0'
fortitude: '+15'
hp: '145'
id: '2184'
immunity:
- bleed
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Doomed|doomed]]'
- '[[DATABASE/condition/Drained|drained]]'
- '[[DATABASE/condition/Fatigued|fatigued]]'
- '[[DATABASE/trait/Healing|healing]]'
- '[[DATABASE/trait/Mental|mental]]'
- '[[DATABASE/trait/Necromancy|necromancy]]'
- '[[DATABASE/trait/Nonlethal|nonlethal]] attacks'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/condition/Sickened|sickened]]'
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '-5'
land_speed: '20'
level: '7'
max_speed: '20'
name: Tallow Guardian
perception: '+13'
rarity: Rare
reflex: '+11'
resistance:
- '[[DATABASE/trait/Fire|fire]] 5'
- physical 5 (except bludgeoning)
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Medium
skill:
- '[[DATABASE/skill/Athletics|Athletics]] +17'
source: '[[DATABASE/source/Crown of the Kobold King|Crown of the Kobold King]]'
speed:
- 20 feet
strength: '+5'
strength_req: '5'
strongest_save:
- Fortitude
trait:
- '[[DATABASE/trait/Construct|Construct]]'
- '[[DATABASE/trait/Mindless|Mindless]]'
- '[[DATABASE/trait/Rare|Rare]]'
type: Creature
vision: Darkvision
weakest_save:
- Reflex
weakness:
- '[[DATABASE/trait/Cold|cold]] 10'
will: '+13'
wisdom: '+0'

---
# Tallow Guardian

A tallow guardian typically appears as a vaguely humanoid-shaped mass of tallow or wax, its surface constantly melting, running down its body, and then hardening only to be reabsorbed into the central mass. The tallow guardian's face seems constantly on the verge of melting into a shapeless blob, yet the unsettling construct can still sense the world around it with ease.
**Recall Knowledge - Construct ([[DATABASE/skill/Arcana|Arcana]], [[DATABASE/skill/Crafting|Crafting]])**: DC 28
**Unspecific Lore**: DC 26
**Specific Lore**: DC 23

# Tallow Guardian<span class="item-type">Creature 7</span>

<span class="trait-rare item-trait">Rare</span><span class="trait-alignment item-trait">N</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Construct</span><span class="item-trait">Mindless</span>
**Source** [[DATABASE/source/Crown of the Kobold King|Crown of the Kobold King]]
**Perception** +13; [[DATABASE/monsterability/Darkvision|darkvision]]
**Skills** [[DATABASE/skill/Athletics|Athletics]] +17
**Str** +5, **Dex** +0, **Con** +2, **Int** -5, **Wis** +0, **Cha** -5

---
**AC** 23; **Fort** +15, **Ref** +11, **Will** +13
**HP** 145; **Immunities** bleed, death effects, disease, [[DATABASE/condition/Doomed|doomed]], [[DATABASE/condition/Drained|drained]], [[DATABASE/condition/Fatigued|fatigued]], healing, mental, necromancy, nonlethal attacks, [[DATABASE/condition/Paralyzed|paralyzed]], poison, [[DATABASE/condition/Sickened|sickened]], [[DATABASE/condition/Unconscious|unconscious]]; **Resistances** fire 5, physical 5 (except bludgeoning); **Weaknesses** cold 10
<span class="in-box-ability">**Melt** If a tallow guardian takes any fire damage, its body melts somewhat and becomes even more difficult to damage. Until the end of its next turn, its resistance to slashing and piercing damage increases to 10, and its resistance to bludgeoning damage increases to 5.</span><span class="in-box-ability">**Slowed by Cold** If a tallow guardian takes any cold damage, it loses the benefits granted by melt and becomes [[DATABASE/condition/Slowed|slowed 1]].</span>

---
**Speed** 20 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> fist +18 [+13/+8] (magical), **Damage** 2d8+8 bludgeoning plus 1d6 [[DATABASE/condition/Persistent Damage|persistent fire]] and [[DATABASE/monsterability/Grab|Grab]]</span><span class="in-box-ability">**Encase** <span class="action-icon">1</span> (attack) The tallow guardian attempts to pull a Medium or smaller creature it has [[DATABASE/condition/Grabbed|grabbed]] into its body. The tallow guardian attempts an [[DATABASE/skill/Athletics|Athletics]] check opposed by the grabbed creature's Reflex DC. If it succeeds, it encases the creature with its body. An encased creature is grabbed, is [[DATABASE/condition/Slowed|slowed 1]], and must hold its breath or start suffocating. It takes 2d6 fire damage from the tallow guardian's molten hot wax when it's first encased, and at the end of each of its turns while it's encased.
 A tallow guardian can only have one encased creature at a time; if a tallow guardian encases a new creature, a previously encased creature is forced out of its body into an adjacent square of the creature's choice.
 An encased creature can break free with a successful DC 22 check to [[DATABASE/action/Escape|Escape]]. An encased creature can attack the tallow guardian, but only with unarmed attacks or with weapons of light Bulk or less. The tallow guardian is [[DATABASE/condition/Flat-Footed|flat-footed]] against the attack. If the tallow guardian takes 7 or more bludgeoning or slashing damage from an encased creature, the creature wrenches itself free. A creature that gets free by either method can immediately breathe and exits the tallow guardian's space, but it continues to take 1d6 [[DATABASE/condition/Persistent Damage|persistent fire damage]] from the molten wax that clings to its body.
 If a tallow guardian is destroyed, any creature it has encased is automatically released as the guardian's body collapses into a shapeless mound of tallow.</span><span class="in-box-ability">**Molten Wax** All [[DATABASE/condition/Persistent Damage|persistent fire damage]] caused by a tallow guardian comes from globs of molten hot tallow that cling to its foes. This tallow cools automatically after 4 rounds, or immediately if the creature takes any cold damage; once the tallow cools, the persistent fire damage ends.</span>

###  From Evil Intent

While a tallow guardian itself isn't intrinsically evil, the traditional methods of creating it involve rendering humanoid corpses to generate the tallow needed to construct its frame. The guardian is then animated by siphoning fragments of souls that linger in the area into a rudimentary but mindless animating force. Other methods of infusing tallow guardians with raw positive energy or voluntary donations could work, but the traditional method persists, giving these constructs an unsettling legacy.