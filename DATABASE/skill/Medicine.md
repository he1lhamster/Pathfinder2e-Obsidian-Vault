---
ability:
- Wisdom
ability_boost:
- Wisdom
id: '9'
name: Medicine
rarity: Common
rus_type_level: null
skill:
- Medicine
source: '[[DATABASE/source/Core Rulebook|Core Rulebook]]'
trait: null
type: Skill

---
# Medicine (Wis)

**Source** [[DATABASE/source/Core Rulebook|Core Rulebook]] 
You can patch up wounds and help people recover from diseases and poisons. Even if you’re untrained in Medicine, you can use it to Recall Knowledge.

* **[[DATABASE/generalskillaction/Recall Knowledge|Recall Knowledge]]** about diseases, injuries, poisons, and other ailments. You can use this to perform forensic examinations if you spend 10 minutes (or more, as determined by the GM) checking for evidence such as wound patterns. This is most useful when determining how a body was injured or killed.

<span>Item Bonuses for Medicine - Common Items</span>| 0 | 1 | 2 | 3 | 4 | 5 |
|:-------------------------------------------------------------------------|:------|:------|:-------------------|:------------|:--------------------------------------------------------------------------------------|
| Item | Bonus | Level | Category | Consumable? | Note |
| [[Healer's Tools]] | +1 | 3 | Adventuring Gear | No | Medicine checks to Administer First Aid, Treat Disease, Treat Poison, or Treat Wounds |
| [[Battle Medic's Baton]] | +1 | 3 | Held Items | No | — |
| [[Healer's Gloves]] | +1 | 4 | Other Worn Items | No | — |
| [[Serene Mutagen]] | +1 | 1 | Alchemical Elixirs | Yes | — |
| [[Vital Earth]] | +1 | 9 | Other Consumables | Yes | — |
| [[Healer's Gloves]] | +2 | 9 | Other Worn Items | No | — |
| [[Marvelous Medicines]] | +2 | 12 | Held Items | No | — |
| [[Serene Mutagen]] | +2 | 3 | Alchemical Elixirs | Yes | — |
| [[Skinstitch Salve]] | +2 | 7 | Alchemical Tools | Yes | Medicine checks to Administer First Aid, Treat Wounds, or use Battle Medicine |
| [[Possibility Tome]] | +3 | 18 | Held Items | No | checks to Recall Knowledge |
| [[Marvelous Medicines]] | +3 | 18 | Held Items | No | — |
| [[Serene Mutagen]] | +3 | 11 | Alchemical Elixirs | Yes | — |
| [[Serene Mutagen]] | +4 | 17 | Alchemical Elixirs | Yes | — |<span>Item Bonuses for Medicine - Uncommon/Rare/Unique Items</span>| 0 | 1 | 2 | 3 | 4 | 5 |
|:---------------------------------------------------------|:------|:------|:--------------------|:------------|:--------------------------------------------------------------------------------------|
| Item | Bonus | Level | Category | Consumable? | Note |
| [[Violet Ray]] | +2 | 12 | Adventuring Gear | No | Medicine checks to Administer First Aid, Treat Disease, Treat Poison, or Treat Wounds |
| [[The Midwife]] | +2 | 20 | The Deck of Destiny | No | bonus increases to +3 at 17th level. |
| [[Coronet of Stars]] | +3 | 17 | Other Worn Items | No | — |

### Related Feats

To see a list of Feats related to Medicine, click here.

# Medicine Untrained Actions

## [[DATABASE/action/Administer First Aid|Administer First Aid]] <span class="action-icon">2</span>

<span class="item-trait">Manipulate</span>
**Source** [[DATABASE/source/Core Rulebook|Core Rulebook]] 
**Requirements** You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]], or you are wearing them and have a hand free

---
You perform first aid on an adjacent creature that is dying or bleeding. If a creature is both dying and bleeding, choose which ailment you’re trying to treat before you roll. You can Administer First Aid again to attempt to remedy the other effect.

* **Stabilize** Attempt a Medicine check on a creature that has 0 Hit Points and the dying condition. The DC is equal to 5 + that creature’s recovery roll DC (typically 15 + its dying value). 
* **Stop Bleeding** Attempt a Medicine check on a creature that is taking [[DATABASE/condition/Persistent Damage|persistent]] bleed damage, giving them a chance to make another flat check to remove the persistent damage. The DC is usually the DC of the effect that caused the bleed.
**Success** If you’re trying to stabilize, the creature loses the dying condition (but remains unconscious). If you’re trying to stop bleeding, the creature attempts a flat check to end the bleeding.
**Critical Failure** If you were trying to stabilize, the creature’s dying value increases by 1. If you were trying to stop bleeding, it immediately takes an amount of damage equal to its persistent bleed damage.

# Medicine Trained Actions

## [[DATABASE/action/Treat Disease|Treat Disease]]

<span class="item-trait">Downtime</span><span class="item-trait">Manipulate</span>
**Source** [[DATABASE/source/Core Rulebook|Core Rulebook]] 
**Requirements** You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]], or you are wearing them and have a hand free

---
You spend at least 8 hours caring for a diseased creature. Attempt a Medicine check against the disease’s DC. After you attempt to Treat a Disease for a creature, you can’t try again until after that creature’s next save against the disease.
**Critical Success** You grant the creature a +4 circumstance bonus to its next saving throw against the disease.
**Success** You grant the creature a +2 circumstance bonus to its next saving throw against the disease.
**Critical Failure** Your efforts cause the creature to take a –2 circumstance penalty to its next save against the disease.

## [[DATABASE/action/Treat Poison|Treat Poison]] <span class="action-icon">1</span>

<span class="item-trait">Manipulate</span>
**Source** [[DATABASE/source/Core Rulebook|Core Rulebook]] 
**Requirements** You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]], or you are wearing them and have a hand free

---
You treat a patient to prevent the spread of poison. Attempt a Medicine check against the poison’s DC. After you attempt to Treat a Poison for a creature, you can’t try again until after the next time that creature attempts a save against the poison.
**Critical Success** You grant the creature a +4 circumstance bonus to its next saving throw against the poison.
**Success** You grant the creature a +2 circumstance bonus to its next saving throw against the poison.
**Critical Failure** Your efforts cause the creature to take a –2 circumstance penalty to its next save against the poison.

## [[DATABASE/action/Treat Wounds|Treat Wounds]]

<span class="item-trait">Exploration</span><span class="item-trait">Healing</span><span class="item-trait">Manipulate</span>
**Source** [[DATABASE/source/Core Rulebook|Core Rulebook]] 
**Requirements** You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]], or you are wearing them and have a hand free

---
You spend 10 minutes treating one injured living creature (targeting yourself, if you so choose). The target is then temporarily immune to Treat Wounds actions for 1 hour, but this interval overlaps with the time you spent treating (so a patient can be treated once per hour, not once per 70 minutes).
 The Medicine check DC is usually 15, though the GM might adjust it based on the circumstances, such as treating a patient outside in a storm, or treating magically cursed wounds. If you’re an expert in Medicine, you can instead attempt a DC 20 check to increase the Hit Points regained by 10; if you’re a master of Medicine, you can instead attempt a DC 30 check to increase the Hit Points regained by 30; and if you’re legendary, you can instead attempt a DC 40 check to increase the Hit Points regained by 50. The damage dealt on a critical failure remains the same.
 If you succeed at your check, you can continue treating the target to grant additional healing. If you treat them for a total of 1 hour, double the Hit Points they regain from Treat Wounds.
 The result of your Medicine check determines how many Hit Points the target regains.

## Treat Wounds

| 0 | 1 | 2 | 3 |
|:------------|:----|:----------------|:-----------------|
| Proficiency | DC | Success Healing | Critical Healing |
| Trained | 15 | 2d8 | 4d8 |
| Expert* | 20 | 2d8+10 | 4d8+10 |
| Master* | 30 | 2d8+30 | 4d8+30 |
| Legendary* | 40 | 2d8+50 | 4d8+50 | * Rolling against a higher DC is optional.
**Critical Success** The target regains 4d8 Hit Points, and its wounded condition is removed.
**Success** The target regains 2d8 Hit Points, and its wounded condition is removed.
**Critical Failure** The target takes 1d8 damage.