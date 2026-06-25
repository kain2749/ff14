# FFXIV: SAM + Sirclucks Chocobo XP Test Plan

Goal: test whether a level 50 Samurai can efficiently grind Heavensward trash mobs to feed XP to Sirclucks at rank 10+.

This is not a Samurai leveling guide. Samurai XP is incidental garbage here. The point is chocobo XP per hour.

## Known setup

- Sirclucks is rank 10.
- A Thavnairian Onion has already been used, so he can earn XP toward rank 11.
- Sirclucks needs 1,458,000 XP for rank 11.
- Samurai starts at level 50.
- Samurai is wearing level 50 Augmented Ironworks Striking/Slaying gear, around item level 130.
- Menphina's Earring and Neophyte's Ring can be used for Samurai XP, but they do not matter for chocobo XP.

## Core question

Can SAM kill level-appropriate Heavensward trash fast enough that Sirclucks gets useful XP/hour?

The test is not about the biggest XP per kill. It is about:

**XP per kill x kills per minute**

A lower-level mob that dies fast may beat a higher-level mob that wastes time.

## Test locations

### Test 1: Coerthas Western Highlands, around Falcon's Nest

Use this first.

Target mobs: level 50-52.

Reason:
- This is the safest first test for SAM 50.
- Heavensward mobs may avoid the bad post-rank-10 XP behavior seen from ARR mobs.
- Terrain is tolerable.
- Easy access from Falcon's Nest.

### Test 2: Coerthas Western Highlands, farther from Falcon's Nest

Use this if Test 1 is too easy or the XP is bad.

Target mobs: level 53-55.

Reason:
- Slightly higher mob level.
- Still probably killable in i130 SAM gear.
- Good middle ground before trying level 56+ enemies.

### Test 3: Heavensward level 56-57 mobs

Use this only if SAM has leveled some or the lower tests are trash.

Target mobs: level 56-57.

Reason:
- Player reports suggest rank 10+ chocobos can get around 6k XP per kill from level 56-57 Heavensward mobs when the player is around that level.
- At SAM 50, this may be too slow or too dangerous.
- Test it later if needed.

## Chocobo stance

Start with:

**Healer Stance**

Reason:
- Samurai is not Warrior.
- Sirclucks healing lets you test 2-3 mob pulls without stopping constantly.

Then test:

**Free Stance**

Use if Healer Stance is too conservative and you are not taking meaningful damage.

Avoid initially:

**Attacker Stance**

Reason:
- SAM already kills. The bird's healing is probably more valuable for uptime.
- Attacker may help if mobs are trivial, but test it instead of assuming.

## Test method

For each location/stance/pack size:

1. Summon Sirclucks.
2. Check Sirclucks' current XP.
3. Kill exactly 10 mobs.
4. Check Sirclucks' XP again.
5. Record XP gained.
6. Divide by 10 for XP per kill.
7. Record rough time taken.
8. Decide whether the loop is worth repeating.

## Record format

| Test | Zone | Mob level | Pack size | Chocobo stance | XP before | XP after | XP gained | XP/kill | Time | Notes |
|---|---|---:|---:|---|---:|---:|---:|---:|---|---|
| 1 | Coerthas Western Highlands | 50-52 | 1 | Healer | | | | | | |
| 2 | Coerthas Western Highlands | 50-52 | 2 | Healer | | | | | | |
| 3 | Coerthas Western Highlands | 50-52 | 3 | Healer | | | | | | |
| 4 | Coerthas Western Highlands | 53-55 | 1 | Healer | | | | | | |
| 5 | Coerthas Western Highlands | 53-55 | 2 | Healer | | | | | | |
| 6 | HW higher-level zone/mobs | 56-57 | 1 | Healer | | | | | | |

## Kill-count math for rank 11

Sirclucks needs 1,458,000 XP for rank 11.

| XP per kill | Kills needed |
|---:|---:|
| 10,000 | 146 |
| 7,000 | 209 |
| 6,000 | 243 |
| 5,000 | 292 |
| 3,000 | 486 |
| 1,000 | 1,458 |
| 650 | 2,243 |

If XP is around 5k-7k per kill, brute forcing a rank is annoying but viable.

If XP is around 650-1k per kill, abandon the grind and mostly rely on the weekly Challenge Log.

## SAM level 50 single-target plan

Use this on one mob or beefier targets.

Basic idea:
- Build Sen.
- Spend Sen.
- Do not overthink it.

Fast opener on a beefier mob:

1. Meikyo Shisui
2. Gekko
3. Kasha
4. Yukikaze
5. Midare Setsugekka

Normal loop:

1. Hakaze -> Jinpu -> Gekko
2. Hakaze -> Shifu -> Kasha
3. Hakaze -> Yukikaze
4. Midare Setsugekka

Avoid using Higanbana on weak trash unless the mob lives long enough for the DoT to matter.

## SAM level 50 AoE plan

Use this for 2-4 mobs.

1. Fuga -> Mangetsu
2. Fuga -> Oka
3. Tenka Goken

Start with 2 mobs.

If safe, try 3.

Do not pull like Warrior. Samurai is damage, not tank privilege.

## Decision rules

Good result:

- 5k+ XP per kill
- fast kills
- little downtime
- 2-3 mob packs are safe

Keep grinding if you can tolerate it.

Bad result:

- under 2k XP per kill
- frequent downtime
- Sirclucks cannot keep up
- mobs take forever to die

Stop. Do MSQ, wait for weekly Bosom Buddies reset, or try again after SAM levels.

## Current recommendation

Start with:

**SAM 50 + i130 gear + Sirclucks Healer Stance + level 50-52 Heavensward mobs near Falcon's Nest**

Run a 10-kill test.

If the number looks good, test 2-mob and 3-mob AoE pulls.

If the number is terrible, do not grind ARR mobs. The reports suggest ARR level 49 mobs can give awful rank 10+ chocobo XP.

## Sources

- Official FFXIV UI Guide: Chocobos can rank past 10 only after using Thavnairian Onions.
  https://na.finalfantasyxiv.com/uiguide/faq/faq-chocobo/chocobo_rank.html

- Official FFXIV UI Guide: Chocobo rank 11+ requires raising the max rank with Thavnairian Onion.
  https://na.finalfantasyxiv.com/uiguide/faq/faq-chocobo/chocobe_rank_limit.html

- The Balance Samurai leveling guide: level 50 Samurai rotates through combos and uses Midare; Meikyo helps shortcut combo finishers.
  https://www.thebalanceffxiv.com/jobs/melee/samurai/leveling-guide/

- The Balance Samurai basic guide: Samurai AoE combo structure generates Sen into Tenka Goken.
  https://www.thebalanceffxiv.com/jobs/melee/samurai/basic-guide/

- Reddit player report: rank 10+ chocobo XP can be terrible from ARR mobs but much better from level-appropriate Heavensward mobs.
  https://www.reddit.com/r/ffxiv/comments/s471ow/experience_drop_after_chocobo_has_attained_rank_10/
