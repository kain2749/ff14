# FFXIV Healer Duty Cheatsheet

Practical healer notes for normal queued PvE duties.

**Scope**

This file is meant for normal/MSQ/roulette healing, especially White Mage. It covers:

- Dungeons
- Normal / Hard trials
- Alliance raids
- Normal raids

It does **not** try to be a full EX/Savage/Ultimate guide.

**Spoiler warning:** Duty names past your current MSQ are inherently spoilers. Future expansion sections are under collapsible `<details>` blocks.

Sources / currentness:

- Official Lodestone Duty database: https://na.finalfantasyxiv.com/lodestone/playguide/db/duty/
- Official Lodestone Patch 7.5 notes: https://na.finalfantasyxiv.com/lodestone/topics/detail/07320affa7e0fcd9685afcbe54fbf55405b6d822
- Official Lodestone Patch 7.4 notes: https://na.finalfantasyxiv.com/lodestone/topics/detail/06944d892fd98cc00b2a28ff77edbafa4f7eef54/
- FFXIV ConsoleGamesWiki duty pages: https://ffxiv.consolegameswiki.com/wiki/Dungeons

---

## Table of contents

**Universal rules**
- [When to DPS vs heal](#when-to-dps-vs-heal) · [Mana management](#mana-management) · [Raise and recovery](#raise-and-recovery) · [Healer utility](#healer-utility) · [Esuna specifics](#esuna-specifics) · [Mechanic language](#common-mechanic-language-healer)

**Expansion duty lists**
- [Current story fast lane — HW content](#current-story-fast-lane-heavensward)
- [A Realm Reborn](#a-realm-reborn): [dungeons](#arr-dungeons) · [dungeon gotchas](#arr-dungeon-gotchas) · [trials](#arr-trials) · [alliance raids](#arr-alliance-raids)
- [Heavensward](#heavensward): [dungeons](#hw-dungeons) · [dungeon gotchas](#hw-dungeon-gotchas) · [trials](#hw-trials) · [alliance raids](#hw-alliance-raids)
- [Stormblood](#stormblood) *(spoilers — collapsed)*: [dungeons](#sb-dungeons) · [dungeon gotchas](#sb-dungeon-gotchas) · [trials](#sb-trials) · [alliance raids](#sb-alliance-raids)
- [Shadowbringers](#shadowbringers) *(spoilers — collapsed)*: [dungeons](#shb-dungeons) · [dungeon gotchas](#shb-dungeon-gotchas) · [trials](#shb-trials) · [alliance raids](#shb-alliance-raids)
- [Endwalker](#endwalker) *(spoilers — collapsed)*: [dungeons](#ew-dungeons) · [dungeon gotchas](#ew-dungeon-gotchas) · [trials](#ew-trials) · [alliance raids](#ew-alliance-raids)
- [Dawntrail](#dawntrail) *(spoilers — collapsed)*: [dungeons](#dt-dungeons) · [dungeon gotchas](#dt-dungeon-gotchas) · [trials](#dt-trials) · [alliance raids](#dt-alliance-raids)

**Other content**
- [Variant / Criterion / Deep Dungeon / Field Operations](#variant--criterion--deep-dungeon--field-operation-notes)
- [Quick roulette checklist](#quick-i-just-loaded-into-roulette-checklist)
- [White Mage notes](#white-mage-notes)

---

## When to DPS vs heal

```text
Nobody dying: DPS.
Tank below ~60% and falling: heal.
Party just took a raidwide: AoE heal, then back to DPS.
Someone is dead: Swiftcast + Raise immediately.
```

Healer DPS is real DPS. A healer who spends every GCD on heals is wasting half their kit. Most roulette content does not need constant healing — it needs smart triage.

Priority order:
1. Keep the tank alive
2. Keep yourself alive
3. Keep DPS alive
4. Deal damage
5. Raise the dead (in practice this beats step 4 if it's a clean death and the content isn't on a timer)

---

## Mana management

```text
Use Lucid Dreaming around 60-70% MP, not when you're already empty.
Thin Air (WHM): use on Raise or emergency back-to-back GCD heal windows.
Avoid chain GCD heals on trash; one Regen then watch. If the tank is stable, DPS.
```

Running dry mid-fight is a healer error. Lucid Dreaming has a 60s cooldown; use it before you need it.

Good MP rhythm:
```text
After a trash pull: check MP; Lucid if below 70%
Before a boss: Regen the tank, apply Medica II regen (WHM) or equivalent
During a raidwide: AoE heal; Lucid if MP dropped
```

---

## Raise and recovery

```text
Someone dies: Swiftcast + Raise. Now. Do not finish the cast bar you were on.
Raised player has Weakness (~100s increased damage taken): top them up right after they accept.
Two people die at once: raise the other healer first if present. Otherwise the most useful survivor.
Near-wipe: keep the tank alive last; you can't raise from death.
```

Swiftcast has a 60s recast. Thin Air makes Raise free (WHM). Do not hoard either of these in a roulette dungeon.

---

## Healer utility

| Ability | When to use |
|---|---|
| Esuna | Any debuff with a white bar through the icon. Doom, Paralysis, Heavy. Do not ignore these. |
| Rescue | Someone about to fall off an edge, walk into a mechanic, or stand in obviously lethal ground. |
| Swiftcast | Raise, first and always. Second use: mobile heal when you can't stand still. |
| Surecast | Before a knockback lands, not during. |
| Lucid Dreaming | ~60-70% MP. Not at 10%. |
| Thin Air (WHM) | Raise. Emergency back-to-back GCD heal window. Don't waste it on Cure I. |

---

## Esuna specifics

The white horizontal line through a debuff icon means Esuna removes it. No line = a different mechanic is required.

**Common cleansable debuffs in normal content:**
- Doom — Esuna it; if the icon has no white line the mechanic requires something else (floor slab, kill the add, etc.)
- Paralysis — Esuna immediately. A paralyzed tank is a dead tank.
- Pollen / Spore (some plant bosses) — cleanse to prevent stack buildup
- Hex (some bosses) — cleanse to prevent damage amp

**Not Esuna-cleansable (common mistakes):**
- Aurum Vale mist stacks — cured by the gleaming rinds on the floor, not Esuna
- Most environmental DoTs — position-based; leave the ground
- Doom triggered by mechanic failure in some specific duties — resolve the mechanic, not a debuff

---

## Common mechanic language (healer)

| Mechanic | Healer answer |
|---|---|
| Tankbuster | Top up tank to full beforehand. Have an oGCD ready. |
| Shared tankbuster | Top both tanks if possible; pre-shield helps. |
| Raidwide | Pre-regen or pre-shield before it lands. AoE heal after. |
| Stack marker on party | Get in the stack. You cannot heal from outside it. |
| Stack marker on you | Position centrally so the party can stack on you. |
| Spread marker on you | Get away from everyone. You cannot cast centrally during spread. |
| Add spawn | Tank grabs them. You heal the resulting chaos. |
| Doom | Esuna (white line = yes), or direct party to the correct mechanic resolution. |
| Paralysis on tank | Esuna immediately. |
| Knockback | Surecast if you cannot afford to lose your cast position. |
| Player dies | Swiftcast + Raise. Now. |
| Charm targets healer | Face away before the charm cast. You cannot heal while charmed. |
| Forced march | Stop pressing movement keys; let it resolve; correct after. |
| Enrage | Raise who you can, keep the tank up last, accept the wipe and discuss DPS. |

---

## Current story fast lane: Heavensward

You are around late base HW. Key healing notes for near-term duties.

### The Limitless Blue (Hard)

- The fight is mostly a setpiece. Heal incidental damage from arena mechanics.
- When the party uses devices to chain Bismarck, expect a brief chaos window; keep everyone above half.
- Don't fall into the sky.

### The Vault

- Ser Charibert (second boss) spreads fire across the floor. You need to move too — don't plant your feet and hard-cast through this one. DoTs and oGCDs are your friends here.
- Keep Regen rolling on the tank throughout.

### The Aery

- Dragon trash hits harder than expected. Pre-regen the tank before pulls.
- Boss breath attacks can clip melee and healers if positioning is sloppy. Stand behind the boss.

---

# A Realm Reborn

## ARR dungeons

| Duty | Boss | Healer note |
|---|---|---|
| **Sastasha** | Denn the Orcatoothed | Standard; regen the tank. |
| | Karlabos | Tail Screw is a hard tankbuster; top up tank to full and have an oGCD staged. |
| | Captain Madison | Adds spike the party when they appear; AoE heal after the tank gathers them. |
| **The Tam-Tara Deepcroft** | First boss | Standard; regen cycling. |
| | Second boss | Adds; top party up when they're pulled in. |
| | Galvanth the Dominator | Heavy slam hits; oGCD ready on each big cast. |
| **Copperbell Mines** | Kottos | Standard. |
| | Ichorous Ire | Standard; dodge slick so you can keep casting. |
| | Gyges the Great | Tank holds him while party handles cages; stay focused on the tank, not the objectives. |
| **Halatali** | Thunderclap Guivre | Standard; dodge circles without dropping heals. |
| | Hetairos | Standard; dodge charges. |
| | Tangata | Add chaos; AoE heal after tank collects them. |
| **The Thousand Maws of Toto-Rak** | Coeurl O' Nine Tails | Standard. |
| | Nantosuelta | Standard; dodge webs. |
| | Goobbue | Standard; regen rolling. |
| **Haukke Manor** | Manor Jester + Manor Steward | Double boss means more incoming on the tank; top up frequently. |
| | Ahbahl | Charm can affect healers; face away during the charm cast. |
| | Lady Amandine | Add chaos; Esuna any paralysis she applies to the tank. |
| **Brayflox's Longstop** | Hellbender | Tank moves constantly through puddles; keep Regen rolling so you're not reacting to spikes. |
| | Inferno Drake | Stand behind the boss; frontal fire cone kills healers who zone out in front. |
| | Great Yellow Pelican | Knockback; Surecast or top everyone up before it lands. |
| **The Sunken Temple of Qarn** | Teratotaur | Standard. |
| | Adjudicator | Doom: Esuna if the icon has a white line. If no line, the mechanic is the floor slab — your Esuna does nothing. |
| | Miser's Mistress | Golem add spawns; AoE heal while tank picks it up. |
| **Cutter's Cry** | Alacran | Standard. |
| | Giant Tunnel Worm | Standard; dodge re-emergence spots. |
| | Chimera | Party takes damage from positioning failures; top up after each Dragon's/Ram's Voice. |
| **The Stone Vigil** | Cuca Fera | Standard. |
| | Isgebind | Icy floor deals DoT to anyone standing in it; regen cycling keeps ahead of it. |
| | Chudo-Yudo | Multiple breath attacks in sequence hit the whole party; pre-regen before the cast sequence. |
| **Dzemael Darkhold** | All-seeing Eye | Boss hits harder outside crystal pillars; top up if tank is ignoring them. |
| | Taulurd | Standard; dodge. |
| | Batraal | Multiple phases; stay near the pillars yourself to reduce your own incoming. |
| **The Aurum Vale** | Coincounter | Mist stacks a lethal debuff on everyone. It is NOT Esuna-cleansable. The cure is the gleaming rinds on the floor. Direct party to pick them up. |
| | Locksmith | Mist continues; keep party topped up between their cleanse cycles. |
| | Miser's Mistress | Add chaos on top of mist management; most healing-intensive boss in the dungeon. |
| **The Wanderer's Palace** | Freeholder | Standard. |
| | Second boss | Standard. |
| | Tonberry King | Fight length causes resentment to build; tank takes a sudden spike late in the fight — be ready. |
| **Castrum Meridianum** | Lictor | Standard. |
| | Rhitatyn sas Arvina | Wildfire-type raidwides; pre-regen. |
| | Nero tol Scaeva | Beam phases; keep regen rolling through movement. |
| **The Praetorium** | Magitek Colossus | Standard. |
| | Gaius van Baelsar | Heavy raidwides; pre-regen / Medica II (WHM) before big casts. |
| | Ultima Weapon | Multi-phase; raidwide damage on each phase shift; pre-regen throughout. |
| **Amdapor Keep** | Zombie Dragon | Standard. |
| | Demon Wall | You must move forward while healing; use DoTs and oGCDs; you cannot plant and hard-cast here. |
| | Forgall | Body Slam is a hard tankbuster; oGCD required. |
| **Pharos Sirius** | Zu | Standard. |
| | Symond the Unsinkable | Standard. |
| | Siren | Charm can affect healers; face away from Siren before the charm cast or you will heal the wrong targets. |
| **Copperbell Mines (Hard)** | First boss | Standard. |
| | Second boss | Add chaos; AoE heal. |
| | Final boss | Tank holds boss through objective phases; maintain heal output. |
| **Haukke Manor (Hard)** | First boss | Standard. |
| | Second boss | Charm; face away. |
| | Lady Amandine (Hard) | More lethal adds; heavier tank hits; oGCD on every buster. |
| **The Lost City of Amdapor** | First boss | Standard. |
| | Second boss | Standard. |
| | Diabolos | Heavy raidwides from nightmare casts; pre-regen before each one. |
| **Halatali (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavier incoming; mitigation from tank helps. |
| **Brayflox's Longstop (Hard)** | First boss | Standard; don't stand on bombs. |
| | Second boss | Standard. |
| | Gobmachine G-VI | Heavy tankbusters and rocket raidwides; oGCD on every buster. |
| **Hullbreaker Isle** | Sasquatch | Standard. |
| | Second boss | Standard. |
| | Kraken | Tentacle adds deal party damage; AoE heal during tentacle phase. |
| **The Tam-Tara Deepcroft (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Edda Pureheart | Heavy raidwides; pre-regen. |
| **The Stone Vigil (Hard)** | First boss | Cannon sections briefly reduce pressure; use the downtime to regen MP. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; Temperance (WHM) or equivalent before big sequences. |
| **Snowcloak** | First boss | Standard. |
| | Second boss | Standard. |
| | Fenrir | Howl is a heavy raidwide; pre-regen / pre-shield before Howl. |
| **Sastasha (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Karlabos (Hard) | Tail Screw hits significantly harder; oGCD is mandatory, not optional. |
| **The Sunken Temple of Qarn (Hard)** | First boss | Standard. |
| | Second boss | Doom returns; Esuna or direct to pad. |
| | Final boss | Standard; heavier. |
| **The Keeper of the Lake** | Einhander | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy breath raidwides; pre-regen before breath sequences. |
| **The Wanderer's Palace (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Tank takes a hard spike at high resentment stacks; Benediction (WHM) or equivalent may be needed. |
| **Amdapor Keep (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy void raidwides; pre-regen. |

### ARR dungeon gotchas

**Aurum Vale** — The mist stacks are NOT Esuna-cleansable. If party members ignore the gleaming rinds on the floor and stack up, they will die and you cannot prevent it. Raise and redirect.

**Pharos Sirius / Haukke Manor** — Siren and Ahbahl can charm the healer. If you get charmed, you will attempt to heal enemies. Face away before their charm casts — every time.

**Sunken Temple of Qarn** — Adjudicator Doom: check the icon. White line = Esuna it. No line = they need to stand on the floor slab. Your Esuna will do nothing for mechanic-triggered Doom.

**Amdapor Keep (Demon Wall)** — You cannot stand still and cast here. Use DoTs, Aero/Dia (WHM), and oGCDs while walking. Planting your feet means falling into the pit with the party.

**Forgall (Amdapor Keep)** — Body Slam casts quickly. Pre-stage your oGCD before the cast bar completes, not after the hit lands.

## ARR trials

| Duty | Healer note |
|---|---|
| **The Bowl of Embers** | Heal through Ifrit's nail phase; party takes chip damage from eruptions. |
| **The Navel** | Titan raidwides hurt; pre-regen. Knocked-off party members cannot be raised mid-air. |
| **The Howling Eye** | Garuda adds deal party damage; AoE heal during add phases. |
| **The Bowl of Embers (Hard)** | Same as normal but harder nail burst; pre-regen before eruptions. |
| **The Navel (Hard)** | Do not get knocked off. Raidwides are heavier; mitigation from tank helps. |
| **The Howling Eye (Hard)** | Heavier adds; pillar LoS can limit your heal range — position thoughtfully. |
| **Thornmarch (Hard)** | Many moogles doing spread damage; AoE heal frequently. |
| **The Whorleater (Hard)** | Leviathan raidwides; pre-regen. If you fall off the boat, you cannot raise yourself. |
| **The Striking Tree (Hard)** | Orb chaos causes unpredictable damage spikes; keep everyone topped up. |
| **Akh Afah Amphitheatre (Hard)** | Shiva raidwides and ice AoEs; pre-regen before big casts. |
| **The Chrysalis** | Add phase and tear phase cause party damage spikes; be ready to AoE heal. |
| **The Steps of Faith** | Setpiece; heal party incidentally; bigger threat is mechanics than healing. |
| **The Porta Decumana** | Ultima raidwides; pre-regen before each big cast. |

## ARR alliance raids

| Duty | Healer note |
|---|---|
| **The Labyrinth of the Ancients** | Each alliance's healer covers their own alliance. Don't cross-heal unless your alliance is stable. |
| **Syrcus Tower** | Heal your alliance. Most wipes are mechanic failures, not healing failures. |
| **The World of Darkness** | Cerberus belly mechanics can cause chaos; be ready for sudden party damage spikes. |

---

# Heavensward

## HW dungeons

| Duty | Boss | Healer note |
|---|---|---|
| **The Dusk Vigil** | First boss | HW damage starts feeling real; regen cycling on the tank. |
| | Second boss | More sustained pressure; use Lucid proactively. |
| | Final boss | Standard; mitigation from tank helps. |
| **Sohm Al** | Raskovnik | Standard; dodge tentacles. |
| | Myath | Lava puddles tick; if tank stands in them, they spike; keep regen rolling. |
| | Tioman | Heavy breath; pre-regen before breath sequences. |
| **The Aery** | Rangda | Standard; stay behind the boss. |
| | Gyascutus | Standard; regen through sustained hits. |
| | Final boss | Standard; face and dodge AoEs. |
| **The Vault** | Ser Adelphel + Ser Grinnaux | Double boss; tank takes more hits; top up often. |
| | Ser Charibert | Fire spreads across the floor and you need to move too; use DoTs and oGCDs while repositioning. |
| | Final knight | Heavy raidwides; pre-regen before Holy-type casts. |
| **The Great Gubal Library** | Demon Tome | Standard; dodge floor tiles. |
| | Evisiscarae | Standard; dodge book tiles without losing cast uptime. |
| | Final boss | Standard; heavy hits. |
| **The Aetherochemical Research Facility** | First boss | Standard. |
| | Igeyorhm | Phase shifts; re-apply regens after each phase change. |
| | Lahabrea + Igeyorhm | Combined raidwides; pre-regen; this is the hardest heal check in the dungeon. |
| **Neverreap** | Canu Vali | Standard. |
| | Sisiutl | Standard. |
| | Khimaira | Knockback sends everyone to the edge; top up the party before the knockback lands. |
| **The Fractal Continuum** | First boss | Standard. |
| | Second boss | Phase raidwides; pre-regen. |
| | Final boss | Add chaos; AoE heal while tank picks them up. |
| **Saint Mocianne's Arboretum** | Veteran Goobbue | Standard. |
| | Belladonna | Pollen debuff; Esuna if cleansable; otherwise top up party as stacks build. |
| | Final boss | Heavy hits; regen cycling. |
| **Pharos Sirius (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Siren (Hard) | Much more lethal charm; face away before every charm cast. This will kill the run if you get charmed. |
| **The Antitower** | Fullflap | Standard. |
| | Calca and Brina | Standard; party takes chip damage from chess pieces. |
| | Calcabrina | If chess pieces converge and enrage, incoming damage spikes hard; be ready for an emergency window. |
| **The Lost City of Amdapor (Hard)** | First boss | Standard; Esuna terror debuffs if cleansable. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; pre-regen. |
| **Sohr Khai** | Cochineal | Standard. |
| | Gyath | Standard; heavy breath. |
| | Nidhogg | Gaze attack applies a debuff — Esuna immediately if possible; heavy breath raidwides throughout. |
| **Hullbreaker Isle (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; pre-regen. |
| **Xelphatol** | Dotoli Ci | Standard. |
| | Nuzal Hueloc | Standard; dodge charges. |
| | Tozol Huatotl | Add chaos; AoE heal while tank collects them. |
| **The Great Gubal Library (Hard)** | First boss | Standard; navigate floor tiles without losing cast uptime. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; pre-regen. |
| **Baelsar's Wall** | The Griffin | Standard; regen tank through sustained hits. |
| | Second boss | Standard. |
| | Final boss | Heavy hits; oGCD on each tankbuster. |
| **Sohm Al (Hard)** | First boss | Standard. |
| | Second boss | Standard; heavier. |
| | Final boss | Heavy breath raidwides; pre-regen. |

### HW dungeon gotchas

**Ser Charibert (The Vault)** — You have to move too. Use Aero/Dia (WHM) and oGCDs while repositioning around the fire. Standing still to cast on a fire-covered floor kills you.

**Khimaira (Neverreap)** — Everyone gets knocked toward the platform edge. Top up the entire party before the knockback, not just the tank.

**Siren (Pharos Sirius Hard)** — This version of Siren's charm is far more lethal than the original. If you get charmed mid-raid, the heals stop. Face away every single time she winds up the cast.

**Calcabrina (The Antitower)** — If the chess piece adds converge and enrage, the incoming damage from that point becomes very difficult to out-heal. Watch the adds; communicate if they're converging.

**Nidhogg (Sohr Khai)** — The gaze debuff he applies is fast. Have Esuna ready immediately after the gaze fires.

## HW trials

| Duty | Healer note |
|---|---|
| **Thok ast Thok (Hard)** | Ravana raidwides; pre-regen. Directional attacks can clip healers who stand in front. |
| **The Limitless Blue (Hard)** | Platform mechanics mean someone always risks falling; keep the party topped up and use Rescue on anyone sliding toward the edge. |
| **The Singularity Reactor** | Heavy raidwides; this is a serious healing check compared to earlier trials. Pre-regen throughout. |
| **The Final Steps of Faith** | Party takes incidental damage from dragon mechanics; regen cycling. |
| **Containment Bay S1T7** | Sephirot raidwides are heavy; pre-regen / Temperance (WHM) before big casts. |
| **Containment Bay P1T6** | Sophia balance/tilt can fling party to edges; top up before tilt mechanics. |
| **Containment Bay Z1T9** | Zurvan raidwides; pre-regen. |
| **Minstrel's Ballad / EX versions** | Use a real guide. |

## HW alliance raids

| Duty | Healer note |
|---|---|
| **The Void Ark** | Heal your alliance. Boss raidwides hit all three alliances; pre-regen before big casts. |
| **The Weeping City of Mhach** | More lethal mechanics; floor hazards can kill party members you cannot reach in time. Keep regens rolling. |
| **Dun Scaith** | Boss raidwides can wipe an alliance that isn't topped up; Temperance (WHM) before big casts. |

---

<details>
<summary>Stormblood duties</summary>

# Stormblood

## SB dungeons

| Duty | Boss | Healer note |
|---|---|---|
| **The Sirensong Sea** | First boss | Standard. |
| | Second boss | Standard. |
| | Lorelei | Charm can affect healers; face away before every charm cast. |
| **Shisui of the Violet Tides** | Amikiri | Standard. |
| | Ruby Princess | Phase shift spike; top up before the transition. |
| | Shisui Yuzuka | Heavy slashes; oGCD on each tankbuster. |
| **Bardam's Mettle** | Galura | Standard. |
| | Aratunaht-ja | This is the horse-herding boss; party takes incidental damage during the mechanic; keep regens rolling. |
| | Magnai the Oathkeeper | Heavy slam tankbusters; oGCD ready. |
| **Doma Castle** | Magitek Rearguard | Standard. |
| | Hypertuned Grynewaht | Heavy hits; regen cycling. |
| | Mark III-B Magitek Colossus | Tankbusters and bomb raidwides; oGCD on each buster. |
| **Castrum Abania** | Inferno Drake | Standard; stay behind. |
| | Magna Roader | Standard. |
| | Aulus mal Asina | Heavy raidwides and beam patterns; pre-regen. |
| **Ala Mhigo** | Dominans | Add chaos; AoE heal. |
| | Zenos (echo) | Standard; heavy hits. |
| | Fordola rem Lupis | Heavy tankbusters; oGCD required. |
| **Kugane Castle** | Tengu | Standard. |
| | Yojimbo | Very slow, very heavy hits; oGCD on every swing. |
| | Gilgamesh | Multi-phase; add chaos in final phase; AoE heal. |
| **The Temple of the Fist** | First boss | Standard. |
| | Second boss | Standard; regen cycling. |
| | Final boss | Heavy tankbusters; oGCD ready. |
| **The Drowned City of Skalla** | Kelpie | Wave knockbacks hit the party; top up before each wave. |
| | Zonure | Standard; stay behind. |
| | Old One | Transform phase spike; top up before and after the transformation. |
| **Hells' Lid** | First boss | Standard. |
| | Second boss | Standard. |
| | Genbu | Spin raidwide; pre-regen before spin. |
| **The Fractal Continuum (Hard)** | First boss | Standard. |
| | Second boss | Add chaos; AoE heal. |
| | Final boss | Heavy raidwides; pre-regen / Temperance. |
| **The Swallow's Compass** | First boss | Knockback; top up before it. |
| | Second boss | Standard. |
| | Qitian Dasheng | Heavy slam combos; oGCD on each tankbuster; regen rolling. |
| **The Burn** | Hedetet | Crystal phase: adds spawn while DPS break the crystal; keep the tank stable through add phase. |
| | Second boss | Standard; heavy movement punish. |
| | Mist Dragon | Clone phase; top up before the breath attack hits. |
| **Saint Mocianne's Arboretum (Hard)** | First boss | Standard. |
| | Belladonna (Hard) | Heavier pollen; top up party after each cloud. |
| | Final boss | Heavy raidwides; Temperance before sequences. |
| **The Ghimlyt Dark** | First boss | Standard. |
| | Second boss | Standard; heavy hits. |
| | Mark III-B Magitek Colossus | Raidwides from rockets; pre-regen; keep tank healed through the duty-action phase. |

### SB dungeon gotchas

**Lorelei (The Sirensong Sea)** — Same problem as Siren: charm can affect healers. Face away before every charm cast. Do not let the ghost lady turn you into a liability.

**Aratunaht-ja (Bardam's Mettle)** — During the horse mechanic the party is running around and taking incidental hits. Keep Regen rolling on everyone, not just the tank.

**Hedetet (The Burn)** — During the crystal phase, the tank holds adds while DPS attack the crystal. Your only job in this window is to keep the tank alive through multiple simultaneous add hits. Focus on the tank; DPS will handle the crystal.

**Yojimbo (Kugane Castle)** — His attacks are slow but each one hits extremely hard. Pre-stage oGCDs before each swing rather than reacting after.

## SB trials

| Duty | Healer note |
|---|---|
| **The Pool of Tribute** | Susano raidwides; pre-regen. |
| **Emanation** | Lakshmi duty-action phase; keep tank stable when action is on cooldown. |
| **The Royal Menagerie** | Shinryu heavy raidwides; pre-regen / Temperance for platform phases. |
| **The Jade Stoa** | Byakko movement phases cause party spread; regen everyone before movement mechanics. |
| **Castrum Fluminis** | Tsukuyomi phase transitions have raidwides; pre-regen before each one. |
| **The Great Hunt** | Monster hunter mechanics; heal incidentally; tells differ from normal bosses. |
| **Hells' Kier** | Suzaku dance/platform phases; keep everyone topped up before platform transitions. |
| **The Wreath of Snakes** | Seiryu add phases; AoE heal while tank manages adds. |
| **Extreme versions** | Use current PF guide. |

## SB alliance raids

| Duty | Healer note |
|---|---|
| **The Royal City of Rabanastre** | Heal your alliance; boss raidwides can wipe an under-topped alliance. |
| **The Ridorana Lighthouse** | Math boss; no amount of healing fixes arithmetic failure. Keep your alliance alive during the math. |
| **The Orbonne Monastery** | Heavy raidwides on several bosses; Temperance / equivalent before big cast sequences. |

</details>

<details>
<summary>Shadowbringers duties</summary>

# Shadowbringers

## ShB dungeons

| Duty | Boss | Healer note |
|---|---|---|
| **Holminster Switch** | Forgiven Dissonance | Adds spike the tank and party when they appear; AoE heal while tank picks them up. If adds reach the boss, the fight goes longer and your MP suffers. |
| | Forgiven Cruelty | Cage traps a party member; while they're caged, you have one less target to keep alive but the remaining three take more. |
| | Forgiven Obscenity | Heavy raidwides; pre-regen before big casts. |
| **Dohn Mheg** | Aenc Thon | Standard; knockback mechanics — top up before. |
| | Griaule | Standard; breath raidwides; pre-regen. |
| | Titania | Add phase; primal-phase raidwides are heavy; Temperance (WHM) here if available. |
| **The Qitana Ravel** | Batsquatch | Standard. |
| | Lozatl | Statue gaze attacks hit the party; top up after each wave. |
| | Eros | Standard; raidwides. |
| **Malikah's Well** | First boss | Standard. |
| | Amphibious Talos | Arena floods; if party stands in water, they take DoT; regen cycling. |
| | Storge | Heavy line attacks; stay behind, keep regen rolling. |
| **Mt. Gulg** | Forgiven Cruelty | Same cage mechanic; keep heals going on everyone else while cage is up. |
| | Forgiven Ignorance | Heavy raidwides; pre-regen. |
| | Forgiven Revelry | Hard raidwides; this is the hardest heal check in the dungeon; Temperance here. |
| **Amaurot** | First boss | Standard. |
| | Second boss | Standard. |
| | Proto-Ultima | Orb collision is near-catastrophic damage; top the party up and stay topped before each orb phase. |
| **The Twinning** | First boss | Standard. |
| | Second boss | Clone raidwides; pre-regen. |
| | Final boss | Add chaos and heavy raidwides; Temperance before raidwide sequences. |
| **Akadaemia Anyder** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; pre-regen. |
| **The Grand Cosmos** | First boss | Standard. |
| | Second boss | Standard. |
| | Seeker of Solitude | Heavy raidwides; Temperance if available. |
| **Anamnesis Anyder** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; pre-regen. |
| **The Heroes' Gauntlet** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides and add chaos; AoE heal and Temperance. |
| **Matoya's Relict** | Funnels + Mudman | Standard; cauldron gimmick distracts party; keep regen rolling. |
| | Second boss | Standard. |
| | Forgiven Foolishness | Standard; heavy raidwides. |
| **Paglth'an** | First boss | Standard; heavy trash means you enter this fight with lower MP than ideal; Lucid immediately. |
| | Second boss | Standard. |
| | Alzadaal | Heavy raidwides; Temperance before big cast sequences. |

### ShB dungeon gotchas

**Holminster Switch (Forgiven Dissonance)** — The adds don't just annoy the tank; they contribute to your MP expenditure. A prolonged fight because the adds healed the boss is a healer MP problem. Kill the adds fast.

**Amaurot (Proto-Ultima)** — Orb collision deals catastrophic raidwide damage. Keep Benediction (WHM) off cooldown going into orb phases. If two orbs collide, immediately AoE heal and use everything.

**Mt. Gulg (Forgiven Revelry)** — This is the hardest heal check in ShB normal dungeons. Temperance (WHM) or equivalent before the first raidwide sequence, not after.

**Forgiven Cruelty cage** — The cage traps a DPS or healer, not necessarily the tank. If you get caged, you cannot heal. Make sure regens are rolling before the cast lands.

## ShB trials

| Duty | Healer note |
|---|---|
| **The Dancing Plague** | Titania adds and platform phase; top up before each platform transition. |
| **The Crown of the Immaculate** | Innocence raidwides hit hard; Temperance before big sequences. |
| **The Dying Gasp** | Hades is a long fight with sustained raidwide pressure; Lucid management is critical. |
| **Cinder Drift** | Ruby Weapon raidwides; pre-regen. Arena phases can separate you from party. |
| **The Seat of Sacrifice** | Heavy raidwides; Temperance for the big cinematic sequences. |
| **Castrum Marinum** | Emerald Weapon raidwides; pre-regen on each phase. |
| **The Cloud Deck** | Platform movement; top up before transitions. |
| **Extreme versions** | Use current PF guide. |

## ShB alliance raids

| Duty | Healer note |
|---|---|
| **The Copied Factory** | Heavy alliance-wide AoEs; pre-regen your alliance. |
| **The Puppets' Bunker** | Separate boss scenarios; keep your alliance healed; don't cross-heal unless your alliance is fully stable. |
| **The Tower at Paradigm's Breach** | Visual busy-ness can cause positioning errors; regen everyone and watch the floor. |

</details>

<details>
<summary>Endwalker duties</summary>

# Endwalker

## EW dungeons

| Duty | Boss | Healer note |
|---|---|---|
| **The Tower of Zot** | Minduruva | Elemental phase raidwides hit the whole party; pre-regen before each phase change. |
| | Sanduruva | Same; pre-regen on each element shift. |
| | Cinduruva | Both mechanics active; sustained raidwide pressure; Temperance here. |
| **The Tower of Babil** | Barnabas | Magnetize flings party members across the room; top up everyone before polarity changes. |
| | Lugae | Add phase; keep tank stable through simultaneous add hits. |
| | Zandor | Standard; heavy hits. |
| **Vanaspati** | First boss | Standard. |
| | Terminus Wrecker | This boss hits harder than any previous dungeon boss; oGCDs on every tankbuster; Benediction (WHM) if needed. |
| | Terminus Snatcher | Add waves; AoE heal between waves; raidwides between add phases. |
| **Ktisis Hyperboreia** | First boss | Standard; animation-based tells. |
| | Lyssa | Reflected AoEs can chunk party; top up after each reflection wave. |
| | Hermes | Heavy raidwides; Temperance before big cast sequences. |
| **The Aitiascope** | Livia | Standard. |
| | Rhitahtyn | Standard. |
| | Amon | Heavy raidwides; pre-regen / Temperance. |
| **The Dead Ends** | Peregrine | Heavy raidwides; pre-regen. |
| | Ma Famfrit | Breathtaker countdown: if a party member misses the air bubble, they die and there is nothing you can do; Raise and continue. |
| | Caustic Grebuloff | Heavy tankbusters and raidwides; Temperance before big sequences. |
| **Smileton** | Face | Puzzle boss; no conventional tanking; heal incidentally. |
| | Second boss | Puzzle; minimal healing. |
| | Final boss | Same; just don't die to the mechanic. |
| **The Stigma Dreamscape** | First boss | Add chaos; AoE heal. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; Temperance. |
| **Alzadaal's Legacy** | First boss | Standard. |
| | Second boss | Standard. |
| | Alzadaal | Heavy raidwides; pre-regen. |
| **The Fell Court of Troia** | First boss | Standard. |
| | Second boss | Add chaos. |
| | Beatrice | Heavy void raidwides; Temperance. |
| **Lapis Manalis** | First boss | Standard. |
| | Albion | Heavy charge raidwides; pre-regen. |
| | Galatea Magna | Heavy raidwides and adds; Temperance. |
| **The Aetherfont** | Lyngbakr | Arena freezes; party takes DoT if they don't stay in safe zones; regen cycling. |
| | Second boss | Standard. |
| | Octomammoth | Tentacle adds hit the party; AoE heal during tentacle phase. |
| **The Lunar Subterrane** | First boss | Standard. |
| | Dark Elf | Mirror reflection; stay behind the real boss; standard healing. |
| | Damcyan Antlion | Floor crumbles; if party falls, they can't be raised mid-fall; heavy tankbusters; oGCD ready. |

### EW dungeon gotchas

**Terminus Wrecker (Vanaspati)** — This is the hardest heal check in EW normal dungeons. Use everything. Benediction (WHM) is not too strong here.

**Ma Famfrit (The Dead Ends)** — Breathtaker countdown kills party members who miss the air bubble. You cannot save them with a heal. Raise them and move on.

**Barnabas (Tower of Babil)** — The party gets scattered by magnetize. Top up everyone before polarity changes, not after the fling.

**Damcyan Antlion (Lunar Subterrane)** — Floor crumbling is also your floor. Don't fall into the pit trying to chase a DPS who's out of position.

## EW trials

| Duty | Healer note |
|---|---|
| **The Dark Inside** | Zodiark rotation; raidwides on every major rotation; pre-regen. |
| **The Mothercrystal** | Hydaelyn movement phases; top up before each weapon/movement sequence. |
| **The Final Day** | Endsinger raidwides hit hard; sustained heal pressure throughout; Lucid management critical. |
| **Storm's Crown** | Barbariccia raidwides and movement; pre-regen before hair mechanics. |
| **Mount Ordeals** | Rubicante raidwides are clean patterns; pre-regen; not a particularly hard heal check. |
| **The Voidcast Dais** | Golbez void mechanics; raidwides before each void burst; Temperance. |
| **The Abyssal Fracture** | Zeromus raidwides escalate; Temperance for later phases. |
| **The Gilded Araya** | Asura multi-arm patterns; raidwides throughout; Temperance. |
| **Extreme versions** | Use current PF guide. |

## EW alliance raids

| Duty | Healer note |
|---|---|
| **Aglaia** | Big readable god attacks; pre-regen your alliance before each major cast. |
| **Euphrosyne** | Element mechanics; raidwides match element; pre-regen accordingly. |
| **Thaleia** | Raidwides throughout; keep your alliance topped; Temperance for big cast sequences. |

</details>

<details>
<summary>Dawntrail duties through Patch 7.5</summary>

# Dawntrail

## DT dungeons

| Duty | Boss | Healer note |
|---|---|---|
| **Ihuykatumu** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; pre-regen. |
| **Worqor Zormor** | First boss | Standard. |
| | Ryoqor Tertius | Ice floor; party takes DoT if standing on ice; regen cycling. |
| | Final boss | Heavy raidwides; Temperance. |
| **The Skydeep Cenote** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy raidwides; pre-regen. |
| **Vanguard** | First boss | Standard. |
| | Vanguard Commander R8 | Heavy tankbusters; oGCD on each. |
| | Final boss | Heavy tankbusters and raidwides; Temperance. |
| **Origenics** | First boss | Standard. |
| | The Deceiver | Standard; clone gimmick doesn't affect healer. |
| | Final boss | Heavy raidwides; Temperance. |
| **Alexandria** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Heavy MSQ-capstone raidwides; Temperance / Benediction ready. |
| **Tender Valley** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Standard; heavier. |
| **The Strayborough Deadwalk** | First boss | Standard. |
| | Necromancer | Forced march; stop pressing movement keys so you don't walk into bad while casting. |
| | Final boss | Heavy raidwides; Temperance. |
| **Yuweyawata Field Station** | First boss | Expert-tier; mechanics are faster; position before casting GCD heals. |
| | Second boss | Heavier; mitigation from tank helps. |
| | Final boss | Heavy expert-tier raidwides; Temperance. |
| **The Underkeep** | First boss | Expert-tier; fast mechanics. |
| | Second boss | Heavy; mitigation. |
| | Final boss | Heavy raidwides; Temperance. |
| **The Meso Terminal** | First boss | Expert-tier. |
| | Second boss | Heavy. |
| | Final boss | Heavy raidwides; Temperance. |
| **Mistwake** | First boss | Expert-tier; fast mechanics. |
| | Second boss | Heavy. |
| | Final boss | Heavy raidwides; Temperance. |
| **The Clyteum** | First boss | Current expert-tier; sharper mechanics; position before every GCD heal. |
| | Second boss | Heavier; sustained pressure. |
| | Final boss | Hardest current dungeon raidwides; full Temperance + Liturgy setup expected. |

### DT dungeon gotchas

**Expert-tier dungeons (Yuweyawata onward)** — Mechanics are faster and more punishing than MSQ content. A healer who plants their feet to cast a Cure II in a bad position will die. Always be in a safe position before starting a GCD heal.

**The Clyteum** — Current highest-demand dungeon. If your MP rhythm is sloppy, you will run dry before the final boss dies. Lucid Dreaming every time it's available from the first pull.

## DT trials

| Duty | Healer note |
|---|---|
| **Worqor Lar Dor** | Heavy raidwides; pre-regen. |
| **Everkeep** | Platform mechanics; top up before transitions. |
| **Sphene's Burden** | Cinematic raidwides; Temperance for big cast sequences. |
| **Recollection** | Modern trial raidwides; pre-regen. |
| **The Ageless Necropolis** | Arena change phases; top up before each arena shift. |
| **The Windward Wilds** | Monster hunter tells; raidwides from big monster attacks; pre-regen. |
| **Hell on Rails** | Train/track positioning; sustained party damage; regen cycling. |
| **The Unmaking** | Current normal trial; heavy raidwides; Temperance for big sequences. |
| **Extreme / Minstrel's Ballads** | Use current PF guide. |

## DT alliance raids

| Duty | Healer note |
|---|---|
| **Jeuno: The First Walk** | Heal your alliance; FFXI boss patterns; pre-regen on big casts. |
| **San d'Oria: The Second Walk** | Current mechanics; keep alliance topped; Temperance for raidwide sequences. |
| **Windurst: The Third Walk** | Strongest punishments for bad positioning; ensure your alliance is above half HP at all times. |

</details>

---

# Variant / Criterion / Deep Dungeon / Field Operation notes

## Variant dungeons

- Healer rules still apply; use self-sustain and manage MP carefully.
- Route choices can change boss mechanics; regens pre-applied going into each room.

## Criterion dungeons

- Harder than normal content; treat it like a mini-raid. Pre-shield/pre-regen before every dangerous cast.
- Interrupt and stun from DPS helps; communicate cooldowns.

## Deep Dungeons

- Your normal gear mostly doesn't matter; the system gear matters.
- MP management is different because Lucid may not restore as much; use it aggressively.
- Bosses are mechanic checks; heal the mechanic resolution, not just the boss.

## Field operations / large-scale instances

- Watch shout chat; coordinated healing matters in critical engagements.
- Use your toolkit (Asylum, Liturgy, etc.) on large stacked groups.

---

# Quick "I just loaded into roulette" checklist

```text
[ ] No tank stance on
[ ] Regen on tank before first pull
[ ] Lucid Dreaming on hotbar and accessible
[ ] Esuna ready for cleansable debuffs
[ ] Swiftcast not on cooldown (save for raises if possible)
[ ] Stand behind the boss, not in the cleave
[ ] DPS when the tank isn't in danger
[ ] Raise immediately when someone dies
[ ] Do not chain GCD heals on trash; one Regen and watch
[ ] If confused: heal the tank, then solve the mechanic
```

---

# White Mage notes

## Core abilities

- **Regen**: apply before pulls and maintain throughout; it's your cheapest sustained healing.
- **Benediction**: full heal on one target. Save it for true emergencies (tank at 10%), not convenience. Using it casually means it's not available when the tank is actually dying.
- **Cure III**: AoE heal requires the party to be stacked; don't use it when the party is spread.
- **Medica II**: party-wide HoT; pre-apply before known raidwides. This is your pre-regen.
- **Asylum**: place it before a known raidwide, not after. Healing in the dome is where it shines.
- **Assize**: damage AND healing on a 45s cooldown. Use it on cooldown; it's free healing and damage simultaneously.
- **Temperance**: 10% damage reduction for the party plus enhanced heals. Use before unavoidable raidwides. Do not forget it exists.
- **Liturgy of the Bell**: place it, then the bell heals when it gets hit. It needs to be placed in advance and it needs to be attacked. Don't use it when the party is spread or mobile.
- **Plenary Indulgence**: use right after an AoE heal (Medica/Medica II/Cure III) for bonus healing.

## Thin Air usage

Thin Air makes your next spell free. Priority:
1. Raise (if someone just died and you have no MP)
2. Cure III or Medica if a burst heal window requires many GCDs
3. Otherwise, early in a fight to restore resources

Do not use it to enable Cure I spam. That's not how this works.

## MP discipline

A WHM who is MP-positive through a boss fight used oGCDs properly and didn't spam GCD heals unnecessarily. A WHM who is OOM at the boss's 60% HP mark healed the DPS through every trash pull using Holy → Cure II → Cure II.

```text
Trash: Regen the tank, Aero, DPS. Stop healing until the tank's HP actually drops.
Bosses: Pre-regen, maintain, oGCDs for spikes, GCD heals only for emergencies.
```
