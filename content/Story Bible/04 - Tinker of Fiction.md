---
description: "The protagonist's power: a Tinker whose specialty is fiction. How it works, what limits it, and what it touches."
aliases:
  - "Tinker of Fiction"
  - "The Power"
tags:
  - "bible"
---

# 04 - Tinker of Fiction

The protagonist's power. It belongs to [[Leet]]. Source list: **[Tinker of Fiction Settings](https://docs.google.com/document/d/1-uUX6RHE7vQOE7QYT6zt0aLCQ907EYjfMn8G-8zqvhg/edit?usp=sharing)** (Google Doc). Every setting in it has a page on the [[Catalog/index|The Catalog]].

> [!warning] What was left out
> The doc's **first section** (the Gamer System integration, Catalog Points / Tech Tree Points as earned currency, the weekly five-setting rotation, and "request a setting with high system intelligence") belongs to a different story and is **set aside**, as you asked. The settings list and its catalog breakdowns are kept. Points are back, but earned through **conflict**, not the Gamer System, so the point costs next to each catalog are now **real prices**. See [[#How catalogs unlock]].

---

## Origin
✅

The power is **[[Leet]]'s Eden shard**. With Eden dead, the shard was orphaned. When a self-insert woke up in Leet's body (**December 2010, just before Christmas**), the shard was forcibly turned into something else, and what came out is a Tinker of Fiction.

**Canon Leet's limit is gone.** Repeating a design no longer makes it worse.

## The core

A **Tinker** whose specialty is **fiction itself**. The shard understands technology from any fictional setting, and gives the protagonist the knowledge to build it.

- **Settings** are the unit of the power. Each has a page in the [[Catalog/index|The Catalog]].
- A setting can be split into **catalogs**: one faction's, species' or company's technology (Mass Effect *Human*, *Krogan*, *Asari*; Borderlands *Hyperion*, *Maliwan*...). A catalog is narrow and cheaper.
- The **Tech Tree** is the whole setting: every faction's technology together. Broader, and harder to get.
- Unlocked knowledge is **permanent**.

## How it reads through Worm's rules
*(proposed)*

Worm tinkers have a house style, and this power should follow it unless you rule otherwise:

| Worm tinker rule | Applied to the Tinker of Fiction |
|---|---|
| Knowledge arrives in **flashes and fugue states**, not as a manual | A catalog "opens" as a rush of schematics, usually during or after stress |
| A tinker has a **specialty** | The specialty is *fiction*: the widest specialty on Earth, and also the weirdest |
| Tinkertech is **non-transferable, non-replicable, dies with its maker** *(world rule, [[02 - Power Systems]])* | Applies in full. Nobody else can maintain what the MC builds. |
| **Maintenance** burden grows with output | The MC's arsenal is capped by their hours, not by the catalog |
| Tinkers need **materials** | Fictional tech often runs on fictional physics. See [[#Materials]] |

## How catalogs unlock
✅

**Conflict earns points, and points buy catalogs.** Shards want [[02 - Power Systems#Understood|data]], and fighting is how the shard gets paid.

- **What counts as conflict:** anything that could escalate into an **incident**.
- **How much it pays:** the bigger the conflict, the more points. **Parahumans involved pay more.**
- **The System:** shows **only his balance and the Catalog**. Nothing else: no stats, no quests, no notifications.
- **Prices:** every [[Catalog/index|The Catalog]] page lists them. **Catalog Points** buy one catalog (Mass Effect *Human*, Borderlands *Hyperion*...); **Tech Tree Points** buy a whole setting. Where the doc left a price blank, Claude set one (marked †). See [[#Price tiers]].
- **Powers are bought separately.** A setting's magic or native power costs points on top of its technology: Chakra, Aura and Semblance, the Force, and so on. They're listed under **Powers** on the setting's page.
- Nothing else from the doc's first section comes back: no Gamer System stats or quests, no weekly rotation, no requests.

- **Two currencies:** every incident pays **Catalog Points**. Only big ones, with parahumans or worse, also pay **Tech Tree Points**. ✅

**Combining settings** ✅: allowed, **with varying degrees of success, if any**. FTL from one world with materials from another, biotics with neural interfaces: some hybrids work, some half-work, some don't.

### Price tiers

Anchored on the doc's own numbers: catalogs cost 5–30 Catalog Points, and the Mass Effect and Lancer trees cost 100 Tech Tree Points. Unpriced settings got a Tech Tree price by tier:

| Tier | Tech Tree Points | What's in it | Examples |
|---|---|---|---|
| 1 | 25 | Gadgets, grounded engineering | Archer, Totally Spies, Frostpunk, Barotrauma |
| 2 | 50 | Near-future | Cyberpunk 2077, Metal Gear, Naruto, RWBY, The Boys |
| 3 | 100 | Advanced sci-fi | Mass Effect, Lancer, Portal & Half-Life, Pacific Rim |
| 4 | 200 | Exotic, far-future | Halo, Star Wars, Dragonball, Macross, Evangelion |
| 5 | 400 | Reality-bending | Warhammer 40k, The Culture, Stellaris, Xeelee, Three Body |

Powers run 20–80 Catalog Points (Arts 20, Chakra 30, the Force 50, the Light 60, 40k psyker powers 80). The prices are in `.tools/generators/prices.py`; change a number there and re-run it, and it rewrites only the price lines.

## Materials
✅

Plenty of fictional tech runs on something Earth doesn't have: element zero, mako, Dust, Tiberium, Originium, Australium, Eridium, kyber. This world has new substances coming online on a schedule, and every one of them works as a substitute:

| Material | Where | Available |
|---|---|---|
| Endbringer tissue and attack-site debris | Every Endbringer site | **Now** (legally grey; Vought wants the licence) |
| Labyrinthos ore, gems and cursed loot | [[The Labyrinthos]] | Entrances exist now; Winslow falls in **2 May 2011** |
| Gate salvage (*"some of it from settings people would recognize"*) | [[The Gate-Realms]] | First public Gate **2 May 2011** (the Powder Keg) |
| Shard Dungeon elements (Tinkertech-grade, power-enhancing) | [[Dungeon Breaks\|Shard Dungeons]] | *(TBD)* |
| Lost Island flora (toxic, medicinal, some aware) | [[The Lost Island]] | Being noticed now |
| Nemesis spore deposits (anti-parahuman) | Her attack sites | After **2012-Q1** |

This turns the story's escalation ladder into the MC's **tech ladder**: every catastrophe opens a new material, and every material unlocks new catalogs.

## The thematic engine
*(proposed)*

This world's central failure is that **everyone already has a working explanation**, and it's wrong. The PRT has its taxonomy, PHO has "Void_Cowboy is full of shit", and the cults say powers are gifts.

The Tinker of Fiction is the one person whose power runs on **the actual sources**. Several of the "anomalies" on Earth Bet come straight out of settings on the Catalog:

| On Earth Bet | On the Catalog |
|---|---|
| [[Vought International]]'s Compound V | [[The Boys]] |
| [[All Might]], [[All For One]], [[UA]] and the Quirk lineages | [[My Hero Academia]] |
| [[Kessler]], the Ray Sphere, [[The Beast]] | [[Infamous]] |
| [[The Saiyan Army]], [[The Frieza Force]] | [[Dragonball]] |
| [[Automatons]], [[The Illuminate]], [[Terminids]] | [[Helldivers 2]] |
| [[The Plumbers]], [[Ben Tennyson]], [[The Highbreed]], [[Vilgax]] | [[Ben 10]] |

Where everyone else sees an unexplained cape, the MC may see a **franchise**. That could make them the only person on Earth Bet whose explanation is *right*. It makes them a second [[Tattletale]], an antibody to the classification trap. Leet **knows**: he's a self-insert who knows Worm canon and the fiction behind the expies. What he doesn't know is *why* they're here, and that confuses him badly.

## How the PRT will rate it

The PRT will file it the way it files everything: as a **versatile Tinker with an unusually broad specialty**, probably Tinker 6+ once the range shows. Nobody will guess *fiction*. The word never comes up, because "it's a cape" explains everything. *(proposed)*

## Rulings on the power

- **Power-granting tech: allowed.** Compound V, esper development ([[Raildex]]), the Titan serum ([[Attack on Titan]]), [[Geneforge]] canisters and the Ray Sphere are all buildable. He has to be **very careful** with them: it makes him a rival to [[Cauldron]], and [[All For One]]'s breaking point is *"another entity that can grant powers."* ✅
- **Hazardous catalogs: allowed.** Markers ([[Dead Space]]), the protomolecule ([[The Expanse]]), Blacklight ([[Prototype]]), the [[Event Horizon]] drive. He's smart enough **not to**. ✅
- **Magic-adjacent settings: allowed**, magic included, but a setting's magic or power is **bought separately**, like its technology. ✅
- **Homecoming.** If Leet has it, he doesn't know, and he doesn't care about his homeworld enough to go back. ✅
- **Scale.** [[Factorio]] and [[Satisfactory]] are automation catalogs, and Tinkertech "doesn't scale" is a world rule (the reason [[The Merchants]] matter). Automation from fiction **might** break it. Leet doesn't care, and he isn't going to advertise it either. ✅

---

**See also:** [[Catalog/index|The Catalog]] · [[Leet]] · Open Questions
