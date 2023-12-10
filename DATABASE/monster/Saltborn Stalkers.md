---
ac: '34'
alignment: null
all_resistance: null
burrow_speed: null
charisma: '+3'
climb_speed: null
constitution: '+5'
creature_ability:
- Form Up
- Lightlure
- Saline Crust
- Salty Clutch
- Scour the Bones
- Troop Defenses
- Troop Movement
creature_family: null
dexterity: '+7'
element: Water
fly_speed: null
fortitude: '+22'
hardness: null
hp: 240 (16 squares)
id: '2666'
immunity:
- bleed
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/trait/Sleep|sleep]]'
intelligence: '+3'
land_speed: '10'
language:
- '[[DATABASE/language/Thalassic|Thalassic]]'
level: '13'
max_speed: '60'
name: Saltborn Stalkers
perception: '+24'
rarity: Common
reflex: '+26'
resistance: null
rus_type_level: null
school: null
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Gargantuan
skill:
- '[[DATABASE/skill/Athletics|Athletics]] +27'
- '[[DATABASE/skill/Intimidation|Intimidation]] +22'
- '[[DATABASE/skill/Nature|Nature]] +22'
- '[[DATABASE/skill/Lore|Plane of Water Lore]] +22'
- '[[DATABASE/skill/Stealth|Stealth]] +26'
- '[[DATABASE/skill/Lore|Warfare Lore]] +22'
source: '[[DATABASE/source/Rage of Elements|Rage of Elements]]'
speed:
- 10 feet
- swim 60 feet; troop movement
spell: null
strength: '+6'
strength_req: '6'
strongest_save:
- Reflex
swim_speed: '60'
trait:
- '[[DATABASE/trait/Aquatic|Aquatic]]'
- '[[DATABASE/trait/Elemental|Elemental]]'
- '[[DATABASE/trait/Troop|Troop]]'
- '[[DATABASE/trait/Water|Water]]'
type: Creature
vision: Darkvision
weakest_save:
- Will
weakness:
- area damage 15
- '[[DATABASE/trait/Splash|splash]] damage 8'
will: '+20'
wisdom: '+5'

---
# Saltborn Stalkers

The briny depths of the Boundless Sea sometimes twist large groups of merfolk into swarms with vicious rows of teeth and sharp claws known as saltborn stalkers. Saltborn stalkers hunt in groups, using their drooping, tentacle-like appendages as bioluminescent lures, posing them as wisps or bubbles of planar energy to draw unsuspecting prey into clever ambushes.
**Recall Knowledge - Elemental ([[DATABASE/skill/Arcana|Arcana]], [[DATABASE/skill/Nature|Nature]])**: DC 31
**Unspecific Lore**: DC 29
**Specific Lore**: DC 26

# Saltborn Stalkers<span class="item-type">Creature 13</span>

<span class="trait-size item-trait">Gargantuan</span><span class="item-trait">Aquatic</span><span class="item-trait">Elemental</span><span class="item-trait">Troop</span><span class="item-trait">Water</span>
**Source** [[DATABASE/source/Rage of Elements|Rage of Elements]]
**Perception** +24; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Thalassic|Thalassic]]
**Skills** [[DATABASE/skill/Athletics|Athletics]] +27, [[DATABASE/skill/Intimidation|Intimidation]] +22, [[DATABASE/skill/Nature|Nature]] +22, [[DATABASE/skill/Lore|Plane of Water Lore]] +22, [[DATABASE/skill/Stealth|Stealth]] +26, [[DATABASE/skill/Lore|Warfare Lore]] +22
**Str** +6, **Dex** +7, **Con** +5, **Int** +3, **Wis** +5, **Cha** +3

---
**AC** 34; **Fort** +22, **Ref** +26, **Will** +20
**HP** 240 (16 squares); **Thresholds** 160 (12 squares), 80 (8 squares); **Immunities** bleed, [[DATABASE/condition/Paralyzed|paralyzed]], poison, sleep; **Weaknesses** area damage 15, splash damage 8
<span class="in-box-ability">**Saline Crust** (aura, water) 20 feet; **Requirements** The saltborn stalkers are in a body of water; **Effect** Layers of the saltborn's salty skin flake off to foul the water around them. A creature that ends its turn in the aura takes 2d6 acid damage with a DC 30 basic Reflex save; creatures with the amphibious or aquatic trait are immune.</span><span class="in-box-ability">**[[DATABASE/monsterability/Troop Defenses|Troop Defenses]]** </span>

---
**Speed** 10 feet, swim 60 feet; troop movement
<span class="in-box-ability">**[[DATABASE/monsterability/Form Up|Form Up]]** <span class="action-icon">1</span> </span><span class="in-box-ability">**Lightlure** <span class="action-icon">1</span> (concentrate, incapacitation, mental, primal, visual) **Effect** The saltborn stalkers move their luminescent lures in an entrancing light show, drawing nearby creatures into their grasp. Each creature in a 100-foot emanation must attempt a DC 33 Will save; regardless of the result of its save, the creature is then temporarily immune to Lightlure for 24 hours.
 **Success** The creature is unaffected.
 **Failure** The creature is [[DATABASE/condition/Fascinated|fascinated]] with the lures and must spend all its actions on its next turn to move closer to them as expediently as possible, avoiding obvious dangers along its path.
 **Critical Failure** As failure, but the creature is also [[DATABASE/condition/Dazzled|dazzled]] for 1d4 rounds.</span><span class="in-box-ability">**Salty Clutch** <span class="action-icon">1</span> **Frequency** once per round; **Effect** The stalkers reach out to Grab their foes and drag them underwater. Each enemy in a 5-foot emanation must succeed at a DC 33 Reflex save or be [[DATABASE/condition/Grabbed|grabbed]] by the stalkers (or [[DATABASE/condition/Restrained|restrained]] on a critical success). For the rest of the current turn, the saltborn stalkers can move toward water or in water without ending the grab, carrying any grabbed or restrained creatures along with them.</span><span class="in-box-ability">**Scour the Bones** <span class="action-icon">1</span> to <span class="action-icon">3</span> **Frequency** once per round; **Effect** The saltborn stalkers use their teeth and claws to vivisect each enemy within 5 feet (DC 30 basic Reflex save). The damage depends on the number of actions.
 <span class="action-icon">1</span> 2d10 slashing damage
 <span class="action-icon">2</span> 3d10+8 slashing damage
 <span class="action-icon">3</span> 3d10+16 slashing damage</span><span class="in-box-ability">**Troop Movement** Whenever the saltborn stalkers Stride or Swim, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move. This works just like a Gargantuan creature moving; for instance, if any of the stalkers' squares enter difficult terrain, the extra movement cost applies to the whole troop.</span>

###  The Rite of Salt and Stone

When a [[DATABASE/monsterfamily/Merfolk|merfolk]] joins the ranks of the saltborn, they undergo a secret rite known only to other saltborn and the [[DATABASE/monsterfamily/Dragon, Brine|brine dragons]] of Kelizandrika. The recruits are encased in graves of salt and ice and left at the floor of the Boundless Sea to claw themselves free. Those who overcome the trial are never truly rid of the salt from their tombs, which covers the body of every saltborn stalker.