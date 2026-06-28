# FFXIV Inventory Management for Leveling Many Jobs

Last updated: 2026-06-28

Purpose: practical inventory rules for a player who is MSQ-first now, but expects to level multiple jobs later. This is not an official guide. It is a synthesis of official UI documentation, community wiki reference pages, and practical rules for keeping the game from turning into bag-management hell.

---

## The core idea

Final Fantasy XIV gives you a lot of storage surfaces, but they do different jobs. Treating all of them as generic storage is how inventory turns into sludge.

The clean mental model is:

- **Inventory**: short-term intake, consumables, market-board handling, quest junk, current materials.
- **Armoury Chest**: active gear that can be equipped by current or near-future jobs.
- **Gear Sets**: loadout pointers, not storage.
- **Armoire**: free long-term storage for eligible special gear.
- **Glamour Dresser**: appearance storage for gear you actually want to use as glam.
- **Retainers**: sellables, materials, long-term maybes, and overflow.
- **Chocobo Saddlebag**: field convenience, overflow, or portable special-purpose storage.
- **`/isearch`**: the truth serum for finding where you shoved something.

The goal is not to keep everything. The goal is to have clear deletion rules so you stop re-litigating every pair of boots.

---

## Source-backed mechanics

### Inventory display settings

The official UI guide says you can change how many inventory items are shown at once through **Character Configuration → Item Settings → Inventory Settings**. Selecting **Expanded** shows more items at once, and **Open All** lets you view all inventory items without tabbing between bag pages. There is also a separate setting for retainer inventories.

Source: [Lodestone UI Guide: How can I view more inventory items at once?](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-bag/setting_itemsort.html)

Practical rule: turn on the most expanded inventory display you can tolerate. Inventory cleanup gets much less annoying when you can actually see the pile.

### Armoury Chest

The official UI guide states that weapons and armor are stored in the **Armoury Chest**, and that gear will be placed in regular inventory when the matching Armoury Chest section is full. It also points to **Character Configuration → Item Settings** for choosing where newly acquired items are placed.

Source: [Lodestone UI Guide: Gear Placed in the Armoury Chest](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-chest/equipment_where_is.html)

The community wiki summarizes the Armoury Chest as separate inventory for gear and says it can hold up to 35 items of each gear type.

Source: [ConsoleGamesWiki: Armoury Chest](https://ffxiv.consolegameswiki.com/wiki/Armoury_Chest)

Practical rule: the Armoury Chest is for active and near-future equipment, not every dungeon drop you might maybe use someday. If a section is full, gear spills into normal inventory and the whole intake system gets messier.

### Gear Sets

The official UI guide says gear sets save your current equipment so it can be equipped quickly. Gear sets unlock when you gain access to a second class, and each class gained increases the number of gear set slots by one. The gear set subcommand menu can show included items, rename the set, and reorder sets. Gear sets can also be assigned to hotbars.

Source: [Lodestone UI Guide: Saving Current Gear Set](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-gearset/equipment_set.html)

The text command reference also documents `/gearset`, including changing to a gear set, viewing a gear set, saving the current set, deleting a set, and optionally applying a glamour plate number when changing sets.

Source: [ConsoleGamesWiki: Text Commands](https://ffxiv.consolegameswiki.com/wiki/Text_commands)

Practical rule: a gear set is a saved pointer to items. It is **not** storage. If you sell, discard, desynth, or turn in an item that a gear set points to, the gear set can break. Use gear sets to define what is actively protected, but do not pretend the set itself stores the item.

### Recommended Gear

The official UI guide says **Recommended Gear** automatically selects the gear with the highest attributes for your current class or job from your Armoury Chest, then lets you equip those items together. The guide also says this is a good time to update gear sets.

Source: [Lodestone UI Guide: Equipping Your Best Gear](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-saikyo/equipment_best.html)

Practical rule: Recommended Gear is a fast sanity check, especially while leveling. It is not a perfect glamour or optimization tool. Use it to catch obviously better pieces, then update the gear set if the result is correct.

### Item Comparison

The official UI guide says Item Comparison is available from an item subcommand menu, and it can compare an item to currently equipped gear when browsing inventory, vendors, or the market board.

Source: [Lodestone UI Guide: Comparing Gear Side-by-side](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-compare/equipment_compare.html)

Practical rule: before buying market-board gear or taking a quest reward as an upgrade, compare it. If it is not an upgrade, not a glam, not sellable, and not useful for another job, it is probably future trash.

### Obtained / registered checkmarks

The official UI guide says certain obtainable/registerable items, such as mounts, minions, and orchestrion rolls, show a checkmark if already obtained or registered. It also says the market interface can display those checkmarks and filter some categories to show only unobtained/unregistered items.

Source: [Lodestone UI Guide: Checking if Items Have Been Obtained/Registered](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-bag/item_obtain.html)

Practical rule: do not buy duplicate minions, rolls, mounts, or unlock items unless you are intentionally buying one to sell or trade.

### Armoire

The community wiki describes the **Armoire** as infinite-capacity storage for certain eligible gear. It says armoire storage is free, does not keep dye colors, does not allow duplicates, and only works for eligible developer-defined items. Eligibility is indicated by an icon on the item screen. It also says gear that can be stored in the armoire generally should be stored there.

Source: [ConsoleGamesWiki: Armoire](https://ffxiv.consolegameswiki.com/wiki/Armoire)

Common armoire categories include seasonal event gear, preorder/collector/veteran reward gear, achievement rewards, quest-exclusive gear, artifact/class/job gear, and other special cases. The exact list changes over time; check the item itself.

Practical rule: **Armoire first**. If an item goes in the Armoire, put it there unless you are currently wearing it.

### Glamour Dresser

The community wiki says Glamour Dressers transform gear into glamours stored in the dresser, not in inventory or the Armoury Chest. Transforming a piece requires the gear and a glamour prism. Once transformed, the item cannot be used as normal gear until restored. Some gear cannot be transformed. Dresser-stored glamours keep dyes but lose crests and previous glamours. The dresser can hold 800 glamours total. Glamour plates can use dresser glamours and some armoire items, with up to 20 glamour plates.

Source: [ConsoleGamesWiki: Glamour Dresser](https://ffxiv.consolegameswiki.com/wiki/Glamour_Dresser)

Practical rule: if you like an item only for appearance, do not let it rot on a retainer. Put it in the Glamour Dresser unless it can go in the Armoire. The 800-slot cap matters eventually, but if you are under 200, the dresser is not your bottleneck.

### `/isearch`

The text command reference says `/itemsearch` and `/isearch` conduct a complete search of owned items, including inventory, equipped gear, retainer-held and retainer-equipped items, Armoury Chest, saddlebag, armoire, and glamour dresser. It also says the command cannot be used in a macro.

Source: [ConsoleGamesWiki: Text Commands](https://ffxiv.consolegameswiki.com/wiki/Text_commands)

Examples:

```text
/isearch "Potion"
/isearch "Stonewashed"
/isearch "Scaevan"
```

Practical rule: before buying, farming, or panicking, `/isearch` it. This is mandatory for multi-job inventory sanity.

### `/itemsort`

The text command reference documents `/itemsort` / `/isort`, including categories such as inventory, retainer, armoury, main hand, head, body, rings, soul crystals, and conditions such as item level, equip level, spiritbond, stack, HQ, materia, and stats. It also notes that `/itemsort` does not affect the normal Sort function.

Source: [ConsoleGamesWiki: Text Commands](https://ffxiv.consolegameswiki.com/wiki/Text_commands)

Useful examples from the documented command shape:

```text
/itemsort condition armoury ilv des
/itemsort execute armoury

/itemsort condition inventory category asc
/itemsort execute inventory
```

Practical rule: use sorting to expose the mess. Sorting will not decide what to keep, but it makes duplicate level brackets, low-ilvl leftovers, and material piles easier to see.

---

## The storage hierarchy

When an item enters your life, run it through this order.

### 1. Is it actively equipped or part of an active gear set?

Keep it in the Armoury Chest or equipped. Do not vendor it. Do not retainer it unless you are intentionally disabling that gear set.

For safety, equip each important gear set occasionally. If a set complains about missing gear, fix the set or delete it. Do not blindly update a gear set while wearing the wrong items.

### 2. Can it go in the Armoire?

Put it in the Armoire. This is the cleanest answer for eligible special gear.

You lose dyes, so if the dye matters and is expensive, decide whether you care. Most of the time, storage wins.

### 3. Is it glam you actually like?

Put it in the Glamour Dresser.

Not “kinda okay.” Not “maybe one day.” Actual likely-use glam. For Rhela, that means things that support known looks: streetwear, Warrior pieces, boots, jewelry, axes, Lyse/Monk-adjacent pieces, and other real aesthetic targets.

### 4. Is it a current or near-future combat upgrade?

Keep it if a current job or near-future alt job will use it soon. Otherwise, do not warehouse every leveling bracket forever.

For example, if a job is level 50 and you are actively leveling it, level 50/60/70 Poetics sets can be worth keeping by role. If no job will touch that bracket soon, the gear is not sacred.

### 5. Is it sellable with actual sale velocity?

Market-board value is not listing price. Value is whether it sells.

Before keeping gear to sell, check sale history. A piece listed for 80k with no recent sales is not better than a fast materia sale, GC seals, or clean inventory.

### 6. Is it GC Expert Delivery material?

If it is eligible and you need seals, turn it in. This is often cleaner than vendor selling.

Be careful: regular NPC vendor selling is not the same safety model as GC Expert Delivery. Gear-set filtering and sell warnings are not universal. Do not assume every disposal method protects gear-set items.

### 7. Is it a crafting/gathering material you will use soon?

Keep materials only when tied to an active project, a profitable sale, or a known future use. Low-level materials are often cheap to rebuy and expensive to store mentally.

### 8. If none of the above: remove it

Vendor it, list it, GC it, desynth it, discard it, or otherwise get it out of the system.

The goal is not to find the perfect use for every item. The goal is to keep playing the game.

---

## Gear management when leveling many jobs

The all-jobs-at-cap model is not “one full gear set per job forever.” That would be insane. The sane model is shared gear by role and bracket.

### Combat role buckets

Most combat armor is shared by role:

- **Fending**: tanks
- **Maiming**: Dragoon / Reaper-style melee gear
- **Striking**: Monk / Samurai-style melee gear
- **Scouting**: Ninja / Viper-style melee gear
- **Aiming**: physical ranged DPS
- **Casting**: magical ranged DPS
- **Healing**: healers

Weapons are job-specific. Some left-side or right-side exceptions exist by level and job, but the role-bucket model is the starting point.

### Bracket logic

Do not keep every random level. Keep meaningful breakpoints.

Useful leveling brackets are usually:

- 50: Augmented Ironworks
- 60: Augmented Shire
- 70: Augmented Scaevan
- 80: Augmented Cryptlurker
- 90: current level 90 Poetics / expansion gear once unlocked

For jobs below cap, dungeon/quest/vendor gear can bridge gaps, but Poetics sets are clean because they are predictable.

### When to delete a bracket

A bracket can be removed when every job that needs that role has moved past it.

Example: if your only striking jobs are SAM and MNK, and both are past 70 with better gear, the old level 60 striking set is probably dead unless it is glam.

If only one job still needs a bracket, consider whether you are actually leveling that job soon. If not, it may be cheaper to rebuy later than to store for months.

### Role gear beats job gear for storage

For multi-job leveling, one shared casting set is better than separate RDM, BLM, and SMN piles. One shared tank set is better than four tank piles. The exceptions are weapons, job-specific gear, and glam.

---

## Glamour policy

Glamour needs rules or it eats the account.

### Keep glam when it passes one of these tests

- It supports an active look.
- It supports a known future look.
- It is rare, annoying to reacquire, or untradable.
- It is an event/job/achievement piece that belongs in the Armoire.
- It is part of a signature identity.

### Do not keep glam when the answer is only “maybe”

“Might use someday” is how retainers die.

For Rhela, the current glam identity is already clear enough to filter with: casual/streetwear Warrior, visible accessories, boots/shoes, jeans, axes, and occasional Ala Mhigan/Lyse/Monk-adjacent pieces. Gear outside that lane needs a stronger reason.

### Dresser beats retainer

If you like it for appearance, put it in the dresser. A retainer full of clothing is just a worse Glamour Dresser with less useful UI.

### Armoire beats dresser

If it can go in the Armoire, store it there first. Armoire storage is free and uncapped for eligible items. Dresser space is capped.

---

## Retainer policy

Retainers should have jobs.

Suggested retainer roles:

### Selling retainer

Market-board listings, price experiments, gathered maps, and sellable gear/materials. This retainer should not become long-term storage. If something fails to sell repeatedly, either lower the price or remove it.

### Materials / venture retainer

Gathering and crafting materials tied to current or known future uses. Do not keep every ore, hide, log, and fish unless you are actively crafting.

### Maybe box

A limited staging area for items you are not ready to delete. This only works if it has a review rule. If the maybe box never gets cleaned, it is not a system; it is a landfill.

Review rule example: if an item has sat for two weeks and still has no active use, it gets sold, GC'd, dressered, or deleted.

---

## Chocobo Saddlebag policy

The saddlebag is best used for field convenience or overflow categories you want nearby but not in the main inventory.

Good saddlebag candidates:

- Current treasure maps or map-adjacent items.
- Frequently used dyes.
- Current food/medicine.
- Event currencies or tokens you are actively spending.
- Gathering bait or field materials, if relevant.

Bad saddlebag candidates:

- Random old gear.
- Unreviewed crafting materials.
- Glam you should have dressered.
- Anything you forgot existed until `/isearch` exposed you.

---

## Market-board and quest reward policy

Do not confuse “can list” with “will sell.”

### Gear rewards

When an MSQ or sidequest offers gear, use this decision order:

1. Is it an immediate upgrade?
2. Is it a near-future alt-job piece?
3. Is it glam you want?
4. Is it GC Expert Delivery eligible and worth seals?
5. Does it have recent market-board sales?
6. If none apply, take materia or another cleaner reward.

For the current Rhela situation, materia often wins because random quest gear tends to sell slowly and wastes retainer attention.

### Maps

Maps are not instant-liquid. If a map is lowest local but does not sell immediately, that may mean the buyer pool is offline, not that the price is wrong. Let it sit through an active play window before panicking.

For gathered maps, remember the opportunity cost: a guaranteed map sale may be better than gambling the contents if the key drop rate is unknown.

---

## Safe cleanup workflow

Use this when inventory feels bad.

### Step 1: Make the UI less awful

Enable expanded inventory display and Open All if you like it. Do the same for retainers if useful.

### Step 2: Update active gear sets

For each active job:

1. Equip the gear set.
2. Hit Recommended Gear if appropriate.
3. Compare obvious upgrades.
4. Update the gear set only when the equipped gear is correct.

### Step 3: Armoire pass

Go to an inn. Anything eligible for Armoire goes in.

### Step 4: Glamour Dresser pass

Anything that is purely appearance and actually wanted goes into the Glamour Dresser. Anything that is only “maybe” gets judged harder.

### Step 5: `/isearch` expensive or suspicious items

Before buying a replacement or deleting something that feels rare, search it.

```text
/isearch "item name"
```

### Step 6: Role bracket pass

Look at gear by role and level bracket. Remove gear no current or near-future job will use.

### Step 7: Retainer pass

Retainers should contain intentional categories, not archaeological layers. Pull out sellables, list them, and kill stale listings.

### Step 8: Final disposal

Use the appropriate outlet:

- Market board for items with actual sale history.
- GC Expert Delivery for eligible gear if seals matter.
- Vendor for trash with no better use.
- Desynth only if you are actually using desynth/crafting systems.
- Discard when the item is worth less than the attention it demands.

---

## Useful commands

```text
/isearch "Item Name"
```

Finds owned items across inventory, equipped gear, retainers, Armoury Chest, saddlebag, armoire, and glamour dresser. Not macro-usable.

```text
/itemsort condition armoury ilv des
/itemsort execute armoury
```

Sort Armoury Chest by item level descending.

```text
/itemsort condition inventory category asc
/itemsort execute inventory
```

Sort inventory by category.

```text
/gearset change warrior
```

Change to the first gear set whose name starts with `warrior`, according to the documented first-letter matching behavior.

```text
/gearset change 1 1
```

Change to gear set slot 1 and apply glamour plate 1, following the documented command shape.

---

## Rhela-specific operating model

Current context: Rhela is MSQ-first, WAR 82, overgeared for Stormblood, with RDM/SAM as side tools for Sirclucks or random overworld work later.

### Do not optimize WAR gear with old Poetics unless fixing a trash slot

Level 70 Scaevan gear is useful for alt jobs and cleanup, not a major WAR upgrade. WAR should not eat Poetics unless a slot is embarrassingly old and below the current practical floor.

### Save Poetics for alt-job brackets

RDM and SAM both benefit more from clean Poetics brackets than WAR does right now. Casting and striking gear at 50/60/70 are more useful than marginal Scaevan cleanup for an overleveled WAR.

### Keep active combat storage small

Active gear sets:

- WAR main
- Miner
- RDM when actively using it
- SAM when actively using it
- Future MNK/PGL only if actually unlocked and played

Everything else should justify its existence.

### Glamour rules for Rhela

Dresser:

- streetwear pieces
- jeans/trousers
- boots/shoes
- visible jewelry
- axes with actual vibe
- Monk/Lyse-adjacent pieces if that becomes a real side look

Armoire:

- job gear, event gear, achievement gear, and anything else eligible

Delete/sell/GC:

- random dungeon gear that is neither upgrade nor glam
- quest reward gear with no sale history
- low-level gear for jobs not being leveled soon

### Map/economy rules

Maps are selling experiments, not inventory anchors. If a Timeworn Leather or Boarskin Map is lowest local and in the normal price band, let it sit through an active play window. If it gets undercut or sits too long, adjust or move on.

---

## Questions to ask an all-100 FC member

The best veteran answers will be rules, not exact retainer layouts.

Ask:

1. What gear brackets do you keep while leveling every job?
2. When do you delete old role gear?
3. What do you always send to the Glamour Dresser?
4. What do you always Armoire immediately?
5. What do you never bother selling?
6. How do you use `/isearch` day to day?
7. Do you keep separate retainers by category?
8. What do you GC Expert Deliver versus vendor versus desynth?
9. What old materials are actually worth keeping?
10. What did you stop hoarding after leveling everything?

The goal is to steal their deletion rules, not inherit their mess.

---

## Short version

Gear Set is not storage. Armoury Chest is for active gear. Armoire comes before Glamour Dresser. Glamour Dresser comes before retainer clothing piles. Retainers need jobs. `/isearch` before buying or panicking. Keep gear by role and bracket, not by job. Delete things when every job that needed that bracket has moved past it. If an item is not gear, glam, sellable, useful soon, or hard to reacquire, it is probably clutter.

---

## References

- [Lodestone UI Guide: Gear and Inventory](https://na.finalfantasyxiv.com/uiguide/equipment/)
- [Lodestone UI Guide: How can I view more inventory items at once?](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-bag/setting_itemsort.html)
- [Lodestone UI Guide: Gear Placed in the Armoury Chest](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-chest/equipment_where_is.html)
- [Lodestone UI Guide: Saving Current Gear Set](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-gearset/equipment_set.html)
- [Lodestone UI Guide: Equipping Your Best Gear](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-saikyo/equipment_best.html)
- [Lodestone UI Guide: Comparing Gear Side-by-side](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-compare/equipment_compare.html)
- [Lodestone UI Guide: Checking if Items Have Been Obtained/Registered](https://na.finalfantasyxiv.com/uiguide/equipment/equipment-bag/item_obtain.html)
- [ConsoleGamesWiki: Armoire](https://ffxiv.consolegameswiki.com/wiki/Armoire)
- [ConsoleGamesWiki: Armoury Chest](https://ffxiv.consolegameswiki.com/wiki/Armoury_Chest)
- [ConsoleGamesWiki: Glamour Dresser](https://ffxiv.consolegameswiki.com/wiki/Glamour_Dresser)
- [ConsoleGamesWiki: Text Commands](https://ffxiv.consolegameswiki.com/wiki/Text_commands)
