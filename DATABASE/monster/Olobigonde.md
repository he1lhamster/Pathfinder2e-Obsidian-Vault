---
ac: '17'
charisma: '-5'
constitution: '+4'
creature_ability:
- Ambush
- Camouflage
- Decomposing Toxin
- Reactive Grab
dexterity: '+1'
element: Water
fortitude: '+10'
hp: '38'
id: '2664'
intelligence: '-4'
land_speed: '5'
level: '2'
max_speed: '30'
name: Olobigonde
perception: '+7'
rarity: Common
reflex: '+7'
sense:
- '[[DATABASE/monsterability/Scent|scent]] (imprecise) 60 feet'
size: Large
skill:
- '[[DATABASE/skill/Athletics|Athletics]] +10'
- '[[DATABASE/skill/Stealth|Stealth]] +9'
- '[[DATABASE/skill/Survival|Survival]] +7'
source: '[[DATABASE/source/Rage of Elements|Rage of Elements]]'
speed:
- 5 feet
- swim 30 feet
strength: '+3'
strength_req: '3'
strongest_save:
- Fortitude
swim_speed: '30'
trait:
- '[[DATABASE/trait/Animal|Animal]]'
- '[[DATABASE/trait/Aquatic|Aquatic]]'
- '[[DATABASE/trait/Elemental|Elemental]]'
- '[[DATABASE/trait/Water|Water]]'
type: Creature
weakest_save:
- Will
will: '+5'
wisdom: '+1'

---
# Olobigonde

Though the [[DATABASE/plane/Plane of Water|Plane of Water]] is mostly liquid, it does contain its share of solid material, whether in the form of free-floating aquatic plants, hunks of coral, or even detritus from lost underwater cities. Flotsam and jetsam collect across the plane, and olobigondes are just one of the many creatures that have evolved to live among and consume this detritus. These flat, round fish are covered in a moss-like skin that makes them exceptionally difficult to spot as they hug the sides of flotsam, feeding off the waste that drifts into their wide, open mouths.
 While olobigondes are primarily detritivores, they've been known to lie in wait within a forest of kelp or against a mossy stone to ambush smaller creatures, such as water scamps or lone passing merfolk. The fish launch themselves from their hiding spot to take large bites out of their surprised prey, then grab the victim as it tries to flee. Despite their size and ungainly shape, olobigondes can move quickly in water, though their bursts of speed are usually short-lived. In addition to maintaining a firm hold on prey, olobigondes' mouths are filled with a unique toxin that weakens and decomposes living flesh. The hungry fish easily gulp down the resulting slurry.
 Ancient olobigondes grow truly immense, and their outward appearance evolves. There seems to be no limit to their size. Their skin even separates into plates with deep channels where water can accumulate, giving them the appearance of an entire patch of detritus rather than one piece.
**Recall Knowledge - Animal ([[DATABASE/skill/Nature|Nature]])**: DC 16
**Recall Knowledge - Elemental ([[DATABASE/skill/Arcana|Arcana]], [[DATABASE/skill/Nature|Nature]])**: DC 16
**Unspecific Lore**: DC 14
**Specific Lore**: DC 11

# Olobigonde<span class="item-type">Creature 2</span>

<span class="trait-size item-trait">Large</span><span class="item-trait">Animal</span><span class="item-trait">Aquatic</span><span class="item-trait">Elemental</span><span class="item-trait">Water</span>
**Source** [[DATABASE/source/Rage of Elements|Rage of Elements]]
**Perception** +7; [[DATABASE/monsterability/Scent|scent]] (imprecise) 60 feet
**Skills** [[DATABASE/skill/Athletics|Athletics]] +10, [[DATABASE/skill/Stealth|Stealth]] +9 (+11 in aquatic terrain), [[DATABASE/skill/Survival|Survival]] +7
**Str** +3, **Dex** +1, **Con** +4, **Int** -4, **Wis** +1, **Cha** -5
**Camouflage** An olobigonde can [[DATABASE/action/Hide|Hide]] in aquatic environments even if it doesn't have cover. However, there must be plants, debris, a seabed, or other objects for it to camouflage itself, not just open water.

---
**AC** 17; **Fort** +10, **Ref** +7, **Will** +5
**HP** 38
<span class="in-box-ability">**Ambush <span class="action-icon">5</span> ** **Trigger** A target creature passes within 20 feet of the olobigonde's hiding place and has not detected the olobigonde; **Effect** The olobigonde lunges out of its hiding place, [[DATABASE/action/Swim|Swims]] directly toward the triggering creature, and makes a jaws Strike against it. The target creature is [[DATABASE/condition/Off-Guard|off-guard]] to this attack.</span><span class="in-box-ability">**Reactive Grab <span class="action-icon">5</span> ** **Trigger** A creature within the olobigonde's reach leaves a square during a move action it's using; **Requirements** The olobigonde doesn't have a creature [[DATABASE/condition/Grabbed|grabbed]]; **Effect** The olobigonde attempts to [[DATABASE/action/Grapple|Grapple]] the triggering creature with its jaws. On a success, the target also takes 3 piercing damage (doubled on a critical success).</span>

---
**Speed** 5 feet, swim 30 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> jaws +11 [+6/+1], **Damage** 1d8+3 piercing plus decomposing toxin</span><span class="in-box-ability">**Decomposing Toxin** (poison) A living creature struck by an olobigonde's jaws Strike must succeed at a DC 15 Fortitude save or become [[DATABASE/condition/Enfeebled|enfeebled 1]] and take 1d6 [[DATABASE/condition/Persistent Damage|persistent poison damage]] (or enfeebled 2 with 2d6 persistent poison damage on a critical failure). The enfeebled condition ends when the persistent damage does. A creature currently affected by decomposing toxin doesn't need to save again.</span>

###  Olobigonde Toxin

Alchemists who travel the planes have discovered how readily an olobigonde's toxin can decompose flesh, and some have discovered ways to incorporate it into their creations. An olobigonde's corpse yields approximately 1 gp worth of raw materials when harvested with a successful DC 16 [[DATABASE/skill/Crafting|Crafting]] or [[DATABASE/skill/Survival|Survival]] check (2 gp worth on a critical success). This material can be used only to craft alchemical bombs with the poison trait.