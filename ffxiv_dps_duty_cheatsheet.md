# FFXIV DPS Duty Cheatsheet

Practical DPS notes for normal queued PvE duties.

**Scope**

This file covers DPS responsibilities for normal/MSQ/roulette content:

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
- [Aggro and opening](#aggro-and-opening) · [Kill priority and add phases](#kill-priority-and-add-phases) · [DPS utility](#dps-utility) · [Positionals](#positionals) · [Mechanic language](#common-mechanic-language-dps)

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
- [Sub-role notes](#sub-role-notes)

---

## Aggro and opening

```text
Wait for the tank to establish aggro before going all-out. Two GCDs is usually enough.
If you pull aggro off the tank: stop DPS, use your enmity drop if available, let tank re-establish.
Do not open with your biggest burst before the tank has hit anything.
```

In practice for roulettes: let the tank pull, wait for them to land one or two GCDs, then go. Tanks will generally not lose aggro after that unless they're not using tank stance.

If you keep pulling aggro consistently, use `/assist` to target through the tank, or reduce your opener delay slightly (the tank may be pulling weird).

---

## Kill priority and add phases

```text
When adds spawn: switch to them immediately unless specifically told not to.
Add priority in most dungeons: kill adds → return to boss.
Exception: some adds are designed to be tanked/ignored (dungeon-specific; read the room).
If no marks: use /assist on the tank to match their target.
If marks are present: follow the kill order.
```

An add that kills the healer because DPS tunneled the boss is a DPS problem. Add phases exist for a reason.

---

## DPS utility

| Ability | When to use |
|---|---|
| Interrupt (Head Graze, etc.) | Silver/sparkle cast bars. Use it. Don't save it for a special occasion. |
| Stun (Low Blow equivalent, job-specific) | Trash pulls to pause a scary cast or give the healer a GCD. Short cooldown; use it. |
| Feint (melee) | Boss tankbusters or raidwides to reduce physical damage. Coordinate with healer. |
| Addle (caster) | Boss magic raidwides or tankbusters. Coordinate with healer. |
| Raise (RDM / SMN / BRD / MCH / DNC) | If you can raise and the healer is dead or occupied: raise someone. Now. |
| True North (melee) | Removes positional requirement. Save it for movement-heavy bosses or mechanics, not lazy DPS. |
| Sprint | Use to reposition fast after knockbacks or mechanics that scatter the party. |

### Interrupt priority

Not every silver cast bar is worth interrupting — some are unavoidable even if interrupted (re-cast immediately). But in normal roulette dungeons, most interruptible trash casts deal significant damage to the healer or tank. Use Head Graze/equivalent on trash as freely as possible.

Bosses in older content (ARR, HW) frequently have interruptible casts. Modern bosses (EW, DT) tend to have fewer or none.

---

## Positionals

Melee DPS get bonus potency on rear (behind) and flank (beside) attacks.

```text
Rear: directly behind the boss. The tail is rear. Stay out of tail swipes.
Flank: directly to either side of the boss. Watch for wing/claw cleaves.
True North: removes the positional check for a few seconds. Save it for moments when you cannot get into position.
```

Do not stand in front of the boss. That is the tank's job and the boss's cleave direction.

Physical ranged DPS (BRD/MCH/DNC) have no positionals. Take advantage of free movement by baiting arena AoEs away from the party.

Casters have limited mobility. Use Swiftcast + slidecasting to maintain uptime through movement mechanics. Addle is your contribution to mitigation.

---

## Common mechanic language (DPS)

| Mechanic | DPS answer |
|---|---|
| Tankbuster | Step away from the tank. If it's shared, stack with the tank. |
| Raidwide | Use your personal damage-reduction cooldown. Keep DPSing. |
| Stack marker on you | Call it out; position centrally; party stacks on you. |
| Spread marker on you | Get away from everyone. Don't follow the tank. |
| Add spawn | Switch targets immediately. Kill adds. |
| Silver/sparkle cast bar | Interrupt it. |
| Positional AoE (cone/cleave) | Don't be in the cone. You know where the boss is facing. |
| Enrage cast | Hard DPS check. If you see it going off, the run failed. Discuss rotation. |
| Kill order marks | Follow them. Don't freelance the kill order. |
| Doom on party member | Not your problem directly — watch for mechanic cues (pad, add, etc.) and help if needed. |
| Knockback | Arm's Length/Surecast equivalent if you have one. Otherwise reposition. |
| Forced march | Stop pressing movement keys. Let it resolve. |
| Towers | Stand in them if nobody else does. A dead tower is a wipe. |
| Duty action required | Pick it up and use it. This is not optional. |

---

## Current story fast lane: Heavensward

### The Limitless Blue (Hard)

- Focus adds during the chain phase; the boss itself is largely a setpiece.
- Separate the two serpent adds when they spawn; stand between them.
- When the boss's weak point is exposed, unload burst cooldowns.

### The Vault

- Ser Charibert spreads fire across the floor. Melee DPS need to stay mobile; ranged DPS have it easier here.
- Don't stand in fire and wonder why your HP is gone.

### The Aery

- Dodge breath AoEs. Stand behind the boss where the tail isn't. Standard dungeon.

---

# A Realm Reborn

## ARR dungeons

| Duty | Boss | DPS note |
|---|---|---|
| **Sastasha** | Denn the Orcatoothed | Switch to adds if they spawn from the pools. |
| | Karlabos | Step away from the tank before Tail Screw lands. |
| | Captain Madison | Switch to adds immediately when they appear at low HP. |
| **The Tam-Tara Deepcroft** | First boss | Standard; dodge and DPS. |
| | Second boss | Switch to adds. |
| | Galvanth the Dominator | Standard; stay out of slam AoEs. |
| **Copperbell Mines** | Kottos | Standard. |
| | Ichorous Ire | Don't stand in the ooze. |
| | Gyges the Great | Interact with the prisoner cages when they appear; this is a DPS responsibility too, not just the healer's. |
| **Halatali** | Thunderclap Guivre | Dodge lightning circles; don't stand in front. |
| | Hetairos | Get out of the charge path. |
| | Tangata | Switch to adds immediately. |
| **The Thousand Maws of Toto-Rak** | Coeurl O' Nine Tails | Standard. |
| | Nantosuelta | Don't stand in webs. |
| | Goobbue | Dodge vine AoEs; stay on the flank/rear. |
| **Haukke Manor** | Manor Jester + Manor Steward | Don't stand in overlapping cleaves; pick one and stay on its flank. |
| | Ahbahl | If you get charmed, you'll attack allies; face away during the charm cast. |
| | Lady Amandine | Switch to adds when they spawn. |
| **Brayflox's Longstop** | Hellbender | Don't stand in poison puddles — obvious but easy to miss if you're tunneling. |
| | Inferno Drake | Do not stand in front of this boss. Fire cone will delete you. Stay behind. |
| | Great Yellow Pelican | Standard; dodge dive AoEs. |
| **The Sunken Temple of Qarn** | Teratotaur | Help herd adds onto pressure plates if needed; don't just DPS the boss. |
| | Adjudicator | If you get Doom, stand on the floor slab immediately. It overrides your DPS uptime. |
| | Miser's Mistress | Switch to golem add; kill it fast. |
| **Cutter's Cry** | Alacran | Stay on the flank; the tail sting hits behind. |
| | Giant Tunnel Worm | Don't stand on disturbed sand — it's the re-emergence tell. |
| | Chimera | Dragon's Voice = get in; Ram's Voice = get out. Do not stand still and DPS through it. |
| **The Stone Vigil** | Cuca Fera | Standard; flank/rear. |
| | Isgebind | Don't stand in ice patches. |
| | Chudo-Yudo | Spread during multi-breath; don't be stacked when multiple breaths go out. |
| **Dzemael Darkhold** | All-seeing Eye | Stay near crystal pillars; damage reduction helps everyone, not just the tank. |
| | Taulurd | Dodge before the explosion, not during. |
| | Batraal | Stay near pillars; multiple phases. |
| **The Aurum Vale** | Coincounter | Pick up the gleaming rinds and use them. Dead DPS do 0 damage. |
| | Locksmith | Same; manage your own mist stacks. |
| | Miser's Mistress | Switch to golem add; then return to boss. |
| **The Wanderer's Palace** | Freeholder | Standard. |
| | Second boss | Standard. |
| | Tonberry King | Burn it fast — resentment stacks make this fight snowball. The longer it lives, the worse it gets. |
| **Castrum Meridianum** | Lictor | Standard. |
| | Rhitatyn sas Arvina | Dodge circle AoEs without losing melee uptime. Ranged: easy. |
| | Nero tol Scaeva | Dodge beam phases. |
| **The Praetorium** | Magitek Colossus | Standard. |
| | Gaius van Baelsar | Dodge raidwides and stay in position. |
| | Ultima Weapon | Each phase has a different pattern; adjust. |
| **Amdapor Keep** | Zombie Dragon | Standard; rear/flank on the dragon. |
| | Demon Wall | Move forward while DPSing. Do not stand still. |
| | Forgall | Step away before Body Slam; return immediately after. |
| **Pharos Sirius** | Zu | Dodge dive AoEs. |
| | Symond the Unsinkable | Standard. |
| | Siren | Face away during charm cast; interrupt the charm if your job has an interrupt. |
| **Copperbell Mines (Hard)** | First boss | Standard. |
| | Second boss | Switch to adds. |
| | Final boss | Interact with cage objective when needed; don't tunnel boss. |
| **Haukke Manor (Hard)** | First boss | Standard. |
| | Second boss | Face away during charm. |
| | Lady Amandine (Hard) | Switch to adds immediately; they hit harder than original. |
| **The Lost City of Amdapor** | First boss | Standard; follow door mechanics. |
| | Second boss | Switch to adds. |
| | Diabolos | Dodge nightmare AoEs; stay mobile. |
| **Halatali (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Switch to adds; dodge arena. |
| **Brayflox's Longstop (Hard)** | First boss | Don't stand on bombs. |
| | Second boss | Standard. |
| | Gobmachine G-VI | Stay out of blast zones; switch to adds if any spawn. |
| **Hullbreaker Isle** | Sasquatch | Dodge barrel projectiles. |
| | Second boss | Standard. |
| | Kraken | Kill tentacle adds; they deal most of the incoming damage. |
| **The Tam-Tara Deepcroft (Hard)** | First boss | Switch to undead adds. |
| | Second boss | Standard. |
| | Edda Pureheart | Standard; dodge raidwides. |
| **The Stone Vigil (Hard)** | First boss | Use cannons when available; DPS the boss otherwise. |
| | Second boss | Standard. |
| | Final boss | Standard; dodge and DPS. |
| **Snowcloak** | First boss | Standard. |
| | Second boss | Dodge snowball mechanic. |
| | Fenrir | Get out of Howl AoE; stay on rear/flank. |
| **Sastasha (Hard)** | First boss | Standard. |
| | Second boss | Switch to adds. |
| | Karlabos (Hard) | Step away from the tank before Tail Screw; it hurts DPS too at this tier. |
| **The Sunken Temple of Qarn (Hard)** | First boss | Standard. |
| | Second boss | Stand on pad if you get Doom — DPS uptime does not save you from instant death. |
| | Final boss | Switch to adds. |
| **The Keeper of the Lake** | Einhander | Standard. |
| | Second boss | Standard. |
| | Final boss | Stay behind; face away during breath. |
| **The Wanderer's Palace (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Burn fast; resentment mechanic still applies. |
| **Amdapor Keep (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Dodge void AoEs; stay mobile. |

### ARR dungeon gotchas

**Aurum Vale** — Eat the gleaming rinds. A DPS who ignores mist stacks and dies wastes a raise and contributes nothing to the run. The tank and healer are not responsible for your survival here; pick up the rinds yourself.

**Tonberry King (Wanderer's Palace)** — Resentment stacks accumulate the longer the fight goes. Burn this boss. Every extra second is a potential one-shot.

**Copperbell Mines (Gyges)** — The prisoner cage interaction is a DPS job too. When the cages appear, someone needs to trigger them. Don't wait for the healer to do it.

**Demon Wall (Amdapor Keep)** — You cannot stand still here. Melee: walk forward while DPSing. Ranged/casters: maintain distance while moving toward the wall.

**Siren (Pharos Sirius)** — Face away before the charm cast. A charmed DPS attacking the healer is the fastest way to wipe the group.

## ARR trials

| Duty | DPS note |
|---|---|
| **The Bowl of Embers** | Kill nails as they appear; don't tunnel Ifrit. |
| **The Navel** | Don't get knocked off; it ends your DPS contribution. |
| **The Howling Eye** | Kill plume adds; switch immediately. |
| **The Bowl of Embers (Hard)** | Kill nails faster than normal; they hurt the party if left up. |
| **The Navel (Hard)** | Same as normal; harder version. Stay on the platform. |
| **The Howling Eye (Hard)** | Heavier add phase; kill priority on the plumes. |
| **Thornmarch (Hard)** | Follow the kill order on moogles. |
| **The Whorleater (Hard)** | Stay on the boat; don't fall. Kill adds when they spawn. |
| **The Striking Tree (Hard)** | Kill orb adds on priority; don't pick up orbs you weren't assigned. |
| **Akh Afah Amphitheatre (Hard)** | Standard; dodge ice AoEs. |
| **The Chrysalis** | Switch to meteor/add targets on priority. |
| **The Steps of Faith** | Use cannons/Dragonkillers if assigned; DPS adds otherwise. |
| **The Porta Decumana** | Dodge Ultima telegraphs; don't tunnel during mechanic windows. |

## ARR alliance raids

| Duty | DPS note |
|---|---|
| **The Labyrinth of the Ancients** | Follow your alliance's kill target. Stand on pads when required. |
| **Syrcus Tower** | Tank the kill order. Don't spin the bosses. |
| **The World of Darkness** | Cerberus belly: stay out unless assigned. Kill adds during chains. |

---

# Heavensward

## HW dungeons

| Duty | Boss | DPS note |
|---|---|---|
| **The Dusk Vigil** | First boss | Standard; dodge and DPS. |
| | Second boss | Standard. |
| | Final boss | Standard; heavier hits. |
| **Sohm Al** | Raskovnik | Dodge tentacle AoEs; stay on flank. |
| | Myath | Stay out of lava puddles. |
| | Tioman | Stay behind; dodge breath AoE. |
| **The Aery** | Rangda | Stay behind; dodge frontal attacks. |
| | Gyascutus | Stay behind the dragon; charges and breath both go forward. |
| | Final boss | Standard; flank/rear. |
| **The Vault** | Ser Adelphel + Ser Grinnaux | Stay between the two knights to avoid getting cleaved from behind; melee should pick one and stick to its flank. |
| | Ser Charibert | Fire spreads across the floor; melee must keep moving — use True North if you can't get a positional while moving. |
| | Final knight | Dodge Holy-type AoEs; stay on flank/rear. |
| **The Great Gubal Library** | Demon Tome | Dodge floor tile patterns. |
| | Evisiscarae | Do not step on dark book tiles; navigate around them. Ranged can just stay back. |
| | Final boss | Standard. |
| **The Aetherochemical Research Facility** | First boss | Standard. |
| | Igeyorhm | Phase shift; maintain uptime through transitions. |
| | Lahabrea + Igeyorhm | Both targets; switch if one becomes vulnerable; dodge combined raidwides. |
| **Neverreap** | Canu Vali | Standard. |
| | Sisiutl | Stay behind; tail cleave goes forward. |
| | Khimaira | Knockback toward edge; Arm's Length if available; reposition fast. |
| **The Fractal Continuum** | First boss | Standard. |
| | Second boss | Dodge phase patterns. |
| | Final boss | Switch to adds immediately. |
| **Saint Mocianne's Arboretum** | Veteran Goobbue | Dodge vine slams; stay on flank. |
| | Belladonna | Stay out of pollen clouds. |
| | Final boss | Standard; dodge paralysis-inducing attacks. |
| **Pharos Sirius (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Siren (Hard) | Face away during charm; interrupt charm if your job can. |
| **The Antitower** | Fullflap | Standard. |
| | Calca and Brina | Keep the two chess pieces separated while DPSing; don't drag them together. |
| | Calcabrina | Kill the chess piece adds in priority order; keep them apart; don't cluster them. |
| **The Lost City of Amdapor (Hard)** | First boss | Follow door mechanics; don't trigger wrong paths. |
| | Second boss | Standard. |
| | Final boss | Dodge void AoEs. |
| **Sohr Khai** | Cochineal | Standard. |
| | Gyath | Stay behind; dodge breath. |
| | Nidhogg | Turn away from gaze when it activates; don't tunnel through it. |
| **Hullbreaker Isle (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Switch to adds if any spawn. |
| **Xelphatol** | Dotoli Ci | Dodge arrow AoEs; interrupt wind casts if available. |
| | Nuzal Hueloc | Get out of the charge path. |
| | Tozol Huatotl | Switch to adds immediately. |
| **The Great Gubal Library (Hard)** | First boss | Navigate floor tiles; ranged can stay back and avoid entirely. |
| | Second boss | Standard. |
| | Final boss | Standard. |
| **Baelsar's Wall** | The Griffin | Dodge charge patterns; stay on flank. |
| | Second boss | Standard. |
| | Final boss | Standard; dodge and DPS. |
| **Sohm Al (Hard)** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Stay behind dragon. |

### HW dungeon gotchas

**Ser Charibert (The Vault)** — The fire floor is a melee uptime challenge. Use True North so you can hit the positional while moving. Ranged and casters have less of a problem here but still need to keep moving.

**Calcabrina (The Antitower)** — The chess piece adds must be killed but must also be kept apart. A melee DPS who clusters them together causes them to enrage. Keep them separated while burning them down.

**Eviviscarae (Great Gubal Library)** — Do not step on the open dark book tiles. Ranged DPS can just stay at max range and never worry about this. Melee need to navigate carefully.

**Nidhogg (Sohr Khai)** — The gaze fires fast. Keep your hand on the camera so you can turn away immediately when it activates.

## HW trials

| Duty | DPS note |
|---|---|
| **Thok ast Thok (Hard)** | Dodge Ravana charges; stay on flank/rear. |
| **The Limitless Blue (Hard)** | Kill adds; separate serpent adds; burst exposed boss when chains drop. |
| **The Singularity Reactor** | Kill add phases on priority; this is a proper DPS check. |
| **The Final Steps of Faith** | Kill adds; help with dragon mechanics as assigned. |
| **Containment Bay S1T7** | Switch to Sephirot adds immediately; they hurt if left up. |
| **Containment Bay P1T6** | Don't walk off the tilting platform. Balance mechanic takes priority. |
| **Containment Bay Z1T9** | Dodge Zurvan AoEs; standard DPS otherwise. |
| **Minstrel's Ballad / EX versions** | Use current PF guide. |

## HW alliance raids

| Duty | DPS note |
|---|---|
| **The Void Ark** | Kill your alliance's adds; let the MT hold the boss. |
| **The Weeping City of Mhach** | Follow floor tells; lethal mechanics kill DPS who ignore them. |
| **Dun Scaith** | Respect cleaves; don't stand in obvious death and blame the healer. |

---

<details>
<summary>Stormblood duties</summary>

# Stormblood

## SB dungeons

| Duty | Boss | DPS note |
|---|---|---|
| **The Sirensong Sea** | First boss | Standard. |
| | Second boss | Switch to adds. |
| | Lorelei | Face away during charm; interrupt it if possible. |
| **Shisui of the Violet Tides** | Amikiri | Standard; flank/rear. |
| | Ruby Princess | Phase shift; maintain uptime. |
| | Shisui Yuzuka | Stay behind; dodge charge attacks. |
| **Bardam's Mettle** | Galura | Standard. |
| | Aratunaht-ja | Use the duty action (Mount) to move the horse to the marked position. This is your primary task here, not DPS. |
| | Magnai the Oathkeeper | Standard; flank/rear; dodge slam AoEs. |
| **Doma Castle** | Magitek Rearguard | Standard. |
| | Hypertuned Grynewaht | Dodge line AoEs; stay on flank. |
| | Mark III-B Magitek Colossus | Stay out of bomb zones; switch to adds if any spawn. |
| **Castrum Abania** | Inferno Drake | Stay behind; never in front. |
| | Magna Roader | Dodge charge patterns. |
| | Aulus mal Asina | Dodge beam patterns; stay mobile. |
| **Ala Mhigo** | Dominans | Switch to adds immediately. |
| | Zenos (echo) | Standard; flank/rear. |
| | Fordola rem Lupis | Dodge her AoE combos; stay on flank. |
| **Kugane Castle** | Tengu | Attack the correct copy; clones take/deal no damage. |
| | Yojimbo | Standard; stay on flank; attacks are slow but each swing is deadly. |
| | Gilgamesh | Switch to adds in final phase; burn them down. |
| **The Temple of the Fist** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Standard; dodge combo AoEs. |
| **The Drowned City of Skalla** | Kelpie | Get behind something or use Arm's Length for wave knockback. |
| | Zonure | Stay behind. |
| | Old One | Burn through phase shift quickly; party takes more sustained damage in the transition. |
| **Hells' Lid** | First boss | Standard. |
| | Second boss | Standard. |
| | Genbu | Get behind the shell during spin; after the spin, resume DPS. |
| **The Fractal Continuum (Hard)** | First boss | Standard. |
| | Second boss | Switch to adds fast. |
| | Final boss | Dodge raidwides; stay on flank. |
| **The Swallow's Compass** | First boss | Arm's Length for knockback or reposition fast. |
| | Second boss | Standard. |
| | Qitian Dasheng | Stay on flank/rear; dodge slam patterns. |
| **The Burn** | Hedetet | When it crystallizes: switch to attacking the crystal shell. Do not DPS the boss during this phase — it's untargetable. |
| | Second boss | Standard; stay mobile. |
| | Mist Dragon | Attack the real dragon; clone/mirror reflects damage. |
| **Saint Mocianne's Arboretum (Hard)** | First boss | Standard. |
| | Belladonna (Hard) | Stay out of heavier pollen clouds. |
| | Final boss | Standard; heavier. |
| **The Ghimlyt Dark** | First boss | Standard. |
| | Second boss | Standard. |
| | Mark III-B Magitek Colossus | Pick up and use the ceruleum fuel tank duty action when it becomes available; the boss requires it to damage during that phase. |

### SB dungeon gotchas

**Aratunaht-ja (Bardam's Mettle)** — This boss literally requires you to stop DPSing and use the duty action. Mount the horse and move it to the marks. Your DPS rotation cannot override the mechanic.

**Hedetet (The Burn)** — During the crystal phase, the boss is untargetable. Switch to the crystal shell immediately. DPS who tunnel the boss deal zero damage for this entire phase.

**Ghimlyt Dark final boss** — The ceruleum fuel tank duty action must be used. If nobody picks it up during the duty-action phase, the boss will not take damage. Don't assume the tank or healer will handle it.

**Tengu (Kugane Castle)** — Attacking the wrong copy does nothing or deals reflected damage. Identify the real one before committing your burst cooldowns.

## SB trials

| Duty | DPS note |
|---|---|
| **The Pool of Tribute** | Kill Susano add/sword phases on priority. |
| **Emanation** | Lakshmi duty action matters; DPS handles it if assigned. |
| **The Royal Menagerie** | Shinryu knockbacks and platform phases; stay on platform. |
| **The Jade Stoa** | Byakko movement phases; maintain uptime through movement. |
| **Castrum Fluminis** | Tsukuyomi phase mechanic DPS; maintain uptime through transitions. |
| **The Great Hunt** | Monster hunter tells differ from standard bosses; read the model, not the cast bar. |
| **Hells' Kier** | Suzaku platform; don't fall. Kill adds when assigned. |
| **The Wreath of Snakes** | Kill Seiryu add phases fast. |
| **Extreme versions** | Use current PF guide. |

## SB alliance raids

| Duty | DPS note |
|---|---|
| **The Royal City of Rabanastre** | Kill your alliance's adds. Follow kill order marks. |
| **The Ridorana Lighthouse** | Math boss; do the math. No amount of DPS fixes arithmetic. |
| **The Orbonne Monastery** | Follow mechanics; cleaves kill DPS who stand in them. |

</details>

<details>
<summary>Shadowbringers duties</summary>

# Shadowbringers

## ShB dungeons

| Duty | Boss | DPS note |
|---|---|---|
| **Holminster Switch** | Forgiven Dissonance | Switch to Forgiven Shame adds immediately when they spawn; kill them before they reach the boss. If they heal the boss, the fight drags and eventually the healer runs OOM. |
| | Forgiven Cruelty | Kill the Gibbet Cage immediately to free the trapped party member. |
| | Forgiven Obscenity | Standard; dodge raidwide AoEs. |
| **Dohn Mheg** | Aenc Thon | Standard; dodge forced movement. |
| | Griaule | Stay behind; breath cleave goes forward. |
| | Titania | Kill adds on priority during add phase. |
| **The Qitana Ravel** | Batsquatch | Standard. |
| | Lozatl | Turn away from glowing wall statues; don't tunnel DPS through the gaze. |
| | Eros | Standard. |
| **Malikah's Well** | First boss | Standard. |
| | Amphibious Talos | Stay in the dry zone; standing in the flood stacks a lethal DoT. |
| | Storge | Stay behind; face away from line attacks. |
| **Mt. Gulg** | Forgiven Cruelty | Kill Gibbet Cage fast. |
| | Forgiven Ignorance | Standard; dodge AoEs. |
| | Forgiven Revelry | Standard; heavy raidwides but no special DPS mechanic. |
| **Amaurot** | First boss | Standard. |
| | Second boss | Standard. |
| | Proto-Ultima | Black and white orbs must stay separated; DPS are responsible for orb handling alongside the tank. Do not ignore orbs to maintain uptime. |
| **The Twinning** | First boss | Standard. |
| | Second boss | Clone patterns; attack the real target. |
| | Final boss | Switch to adds; burn them fast. |
| **Akadaemia Anyder** | First boss | Switch to adds. |
| | Second boss | Standard. |
| | Final boss | Switch to adds; dodge raidwides. |
| **The Grand Cosmos** | First boss | Standard. |
| | Second boss | Standard; dodge patterns. |
| | Seeker of Solitude | Standard; furniture mechanic doesn't directly affect DPS uptime. |
| **Anamnesis Anyder** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Standard; dodge ancient AoEs. |
| **The Heroes' Gauntlet** | First boss | Standard; role mechanics. |
| | Second boss | Switch to adds. |
| | Final boss | Switch to adds; burn fast. |
| **Matoya's Relict** | Funnels + Mudman | Solve the cauldron gimmick; DPS the appropriate target when it becomes available. |
| | Second boss | Standard. |
| | Forgiven Foolishness | Standard. |
| **Paglth'an** | First boss | Standard. |
| | Second boss | Dodge busy AoEs. |
| | Alzadaal | Standard; heavier. |

### ShB dungeon gotchas

**Holminster Switch (Forgiven Dissonance adds)** — Do not tunnel the boss while the adds are up. They heal the boss when they reach it. Every second those adds are alive is wasted DPS on the boss's HP bar.

**Amaurot (Proto-Ultima orbs)** — DPS are responsible for orb separation alongside the rest of the party. Do not ignore orbs to maintain boss uptime. An orb collision is a near-wipe.

**Gibbet Cage** — Appears in two fights in Mt. Gulg. Kill it first, every time, no exceptions.

## ShB trials

| Duty | DPS note |
|---|---|
| **The Dancing Plague** | Kill Titania adds on priority; they hit the party. |
| **The Crown of the Immaculate** | Dodge Innocence AoEs; standard DPS. |
| **The Dying Gasp** | Long fight; maintain rotation through phase shifts. |
| **Cinder Drift** | Ruby Weapon movement phases; stay mobile; DPS uptime suffers but survive first. |
| **The Seat of Sacrifice** | Standard; cinematic mechanics don't require DPS deviation. |
| **Castrum Marinum** | Switch to add phases on priority. |
| **The Cloud Deck** | Don't fall off the platform. Survive then DPS. |
| **Extreme versions** | Use current PF guide. |

## ShB alliance raids

| Duty | DPS note |
|---|---|
| **The Copied Factory** | Kill your alliance's adds; dodge the many AoEs. |
| **The Puppets' Bunker** | DPS separate boss targets; kill your alliance's assigned boss. |
| **The Tower at Paradigm's Breach** | Busy visual mechanics; don't stand in obvious bad. |

</details>

<details>
<summary>Endwalker duties</summary>

# Endwalker

## EW dungeons

| Duty | Boss | DPS note |
|---|---|---|
| **The Tower of Zot** | Minduruva | Read the ground glow before she changes element; safe zone flips center/edge. Move first, DPS after. |
| | Sanduruva | Same flip mechanic; maintain uptime but don't die to the phase change. |
| | Cinduruva | Both mechanics combined; read carefully. |
| **The Tower of Babil** | Barnabas | Move to the correct polarity zone before the floor changes; this overrides your DPS uptime. |
| | Lugae | Switch to Magitek adds on priority. |
| | Zandor | Standard. |
| **Vanaspati** | First boss | Standard. |
| | Terminus Wrecker | Standard; this boss hits the tank hard but DPS just dodge and deal damage. |
| | Terminus Snatcher | Switch to adds between raidwides; burn them down. |
| **Ktisis Hyperboreia** | First boss | Standard; animation-based tells. |
| | Lyssa | Don't stand near frozen party-member statues; reflected AoEs hit nearby DPS. |
| | Hermes | Dodge raidwides; standard. |
| **The Aitiascope** | Livia | Attack the real Livia; the clone reflects damage. |
| | Rhitahtyn | Standard; dodge cannon patterns. |
| | Amon | Standard; dodge raidwides. |
| **The Dead Ends** | Peregrine | Standard. |
| | Ma Famfrit | Get in the air bubble when Breathtaker triggers; DPS uptime does not override a drowning countdown. |
| | Caustic Grebuloff | Standard; dodge. |
| **Smileton** | Face | Pure puzzle; no conventional DPS rotation here. Solve the mechanic. |
| | Second boss | Puzzle; minimal direct DPS. |
| | Final boss | Same. |
| **The Stigma Dreamscape** | First boss | Switch to adds; burn them. |
| | Second boss | Standard. |
| | Final boss | Switch to adds; heavy raidwides in between. |
| **Alzadaal's Legacy** | First boss | Standard. |
| | Second boss | Standard. |
| | Alzadaal | Standard; heavier. |
| **The Fell Court of Troia** | First boss | Standard. |
| | Second boss | Switch to adds. |
| | Beatrice | Standard; dodge void AoEs. |
| **Lapis Manalis** | First boss | Standard. |
| | Albion | Get out of charge path; then resume. |
| | Galatea Magna | Switch to adds; dodge raidwides. |
| **The Aetherfont** | Lyngbakr | Stay in the unfrozen safe zone; don't stand on ice for DPS positioning. |
| | Second boss | Standard. |
| | Octomammoth | Kill tentacle adds; they deal most of the party damage. |
| **The Lunar Subterrane** | First boss | Standard. |
| | Dark Elf | Attack the real boss; clone reflects. |
| | Damcyan Antlion | Stay on solid floor; the arena crumbles; DPS uptime does not justify standing on a collapsing tile. |

### EW dungeon gotchas

**Smileton** — These bosses are pure puzzle encounters. There is no DPS rotation to execute here. Solve what the arena is telling you; DPS is a side effect, not the goal.

**Barnabas (Tower of Babil)** — Polarity floor change is the most important mechanic in this fight. Move to the correct zone. A dead DPS does 0 damage.

**Lyssa (Ktisis Hyperboreia)** — Standing near frozen party members causes the reflected AoEs to hit you. Spread out from frozen players.

**Ma Famfrit (The Dead Ends)** — The Breathtaker air bubble is not optional. Get in it or you die. Your DPS uptime is irrelevant if you're a corpse.

**Dark Elf (Lunar Subterrane)** — Attacking the clone either does nothing or reflects damage. Identify the real boss before using burst cooldowns.

## EW trials

| Duty | DPS note |
|---|---|
| **The Dark Inside** | Zodiark rotation; read the arena orientation. |
| **The Mothercrystal** | Hydaelyn weapon phases; maintain uptime through movement. |
| **The Final Day** | Long Endsinger fight; Lucid on casters; maintain rotation through multiple phase shifts. |
| **Storm's Crown** | Barbariccia movement phases; stay mobile; True North for melee uptime through movement. |
| **Mount Ordeals** | Rubicante clean patterns; readable; standard DPS. |
| **The Voidcast Dais** | Golbez void burst phases; dodge and maintain. |
| **The Abyssal Fracture** | Zeromus edge mechanics; do not fall off; DPS second. |
| **The Gilded Araya** | Asura multi-arm telegraphs; read the boss model for safe spots. |
| **Extreme versions** | Use current PF guide. |

## EW alliance raids

| Duty | DPS note |
|---|---|
| **Aglaia** | Kill adds on priority; dodge big god attacks. |
| **Euphrosyne** | Element mechanics; DPS to assigned targets. |
| **Thaleia** | Don't spin bosses; follow kill order. |

</details>

<details>
<summary>Dawntrail duties through Patch 7.5</summary>

# Dawntrail

## DT dungeons

| Duty | Boss | DPS note |
|---|---|---|
| **Ihuykatumu** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Standard; heavy raidwides. |
| **Worqor Zormor** | First boss | Standard. |
| | Ryoqor Tertius | Don't stand near a platform edge when ice activates — sliding off = dead. |
| | Final boss | Standard. |
| **The Skydeep Cenote** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Standard. |
| **Vanguard** | First boss | Standard. |
| | Vanguard Commander R8 | Switch to adds on priority. |
| | Final boss | Standard; heavier. |
| **Origenics** | First boss | Standard. |
| | The Deceiver | Attack the original, not the clone; confirm before using burst cooldowns. |
| | Final boss | Standard. |
| **Alexandria** | First boss | Standard. |
| | Second boss | Standard; layered mechanics. |
| | Final boss | Standard; heavy MSQ-capstone boss. |
| **Tender Valley** | First boss | Standard. |
| | Second boss | Standard. |
| | Final boss | Standard. |
| **The Strayborough Deadwalk** | First boss | Standard. |
| | Necromancer | Stop pressing movement keys during forced march; let it resolve before correcting. |
| | Final boss | Standard. |
| **Yuweyawata Field Station** | First boss | Expert-tier; mechanics are fast; position before DPS, not after. |
| | Second boss | Heavier layered mechanics; stay safe. |
| | Final boss | Full DPS output; expert-tier fight. |
| **The Underkeep** | First boss | Expert-tier; positionals matter; stay on flank/rear. |
| | Second boss | Heavier. |
| | Final boss | Expert-tier; full rotation expected. |
| **The Meso Terminal** | First boss | Expert-tier. |
| | Second boss | Heavier. |
| | Final boss | Expert-tier; full DPS. |
| **Mistwake** | First boss | Expert-tier; fast mechanics. |
| | Second boss | Heavier. |
| | Final boss | Expert-tier; full rotation. |
| **The Clyteum** | First boss | Current expert-tier; mechanics are the fastest in the game currently. |
| | Second boss | Heavier and faster. |
| | Final boss | Hardest current dungeon; full rotation with full mechanic compliance expected. |

### DT dungeon gotchas

**Expert-tier dungeons (Yuweyawata onward)** — Mechanics punish DPS uptime greed more than any previous expansion's normal content. Position first, then DPS. A brief gap in your rotation is recoverable. Death is not.

**Ryoqor Tertius (Worqor Zormor)** — Ice slides send you off the platform. Don't be near an edge when the ice mechanic activates.

**The Deceiver (Origenics)** — Your burst cooldowns deal zero damage to the clone. Confirm the target before using anything significant.

## DT trials

| Duty | DPS note |
|---|---|
| **Worqor Lar Dor** | Standard; dodge large telegraphs. |
| **Everkeep** | Platform mechanics; don't fall. DPS second. |
| **Sphene's Burden** | Cinematic mechanics; maintain uptime through setpiece phases. |
| **Recollection** | Avoid vuln stacks; a vuln-stacked DPS is effectively dead weight. |
| **The Ageless Necropolis** | Arena changes; adapt positioning each phase. |
| **The Windward Wilds** | Read monster tells; different from standard boss cast bars. |
| **Hell on Rails** | Train/track positioning takes priority; don't DPS from a wrong track segment. |
| **The Unmaking** | Current normal trial; modern layered mechanics; survive first. |
| **Extreme / Minstrel's Ballads** | Use current PF guide. |

## DT alliance raids

| Duty | DPS note |
|---|---|
| **Jeuno: The First Walk** | FFXI patterns; DPS your alliance's assigned targets. |
| **San d'Oria: The Second Walk** | Follow kill order; current-ish mechanics. |
| **Windurst: The Third Walk** | Strongest punishments for bad positioning; DPS second, survive first. |

</details>

---

# Variant / Criterion / Deep Dungeon / Field Operation notes

## Variant dungeons

- Free movement DPS (BRD, MCH, DNC) shine here; abuse your mobility.
- Route mechanics determine boss behavior; follow your designated path.
- Interrupt and stun on trash freely.

## Criterion dungeons

- Treat trash like raid encounters; interrupt everything interruptible.
- Add kills are not optional; switch immediately.
- Feint and Addle are expected contributions, not bonuses.

## Deep Dungeons

- Your normal gear doesn't matter; the system gear matters.
- Pull cautiously; overpulling dungeons wipes differently than regular content.
- Boss mechanics matter more than DPS; solve the check.

## Field operations / large-scale instances

- Watch shout chat for kill order and target assignments.
- Your personal rotation matters less; coordinated targeting matters more.

---

# Quick "I just loaded into roulette" checklist

```text
[ ] No tank stance on
[ ] Wait for tank to hit the target before full burst
[ ] /assist the tank if unsure of kill target
[ ] Add spawn = switch targets immediately
[ ] Interrupt silver cast bars on trash
[ ] Don't stand in front of the boss (melee: flank/rear only)
[ ] Move to safe position first, then DPS
[ ] Use Feint / Addle on big hits if available
[ ] Raise dead party members if your job can
[ ] If confused: survive, then ask
```

---

# Sub-role notes

## Melee DPS

- Positionals are real damage; use True North when mechanics force you off position.
- You will always be in cleave range. Know which direction the boss is facing.
- Feint: physical damage reduction for the whole party on one hit. Coordinate with the healer for tankbusters or raidwides.
- Sprint to reposition after knockbacks; you have the hardest time getting back into melee range.

## Physical ranged DPS (BRD / MCH / DNC)

- You have no positionals. Exploit this by standing in positions the melee cannot.
- You can bait arena AoEs away from the party; position to absorb ground-targeted AoEs if it's safe.
- If your job can raise (BRD, MCH, DNC in some contexts): raise dead party members. The healer is not the only one responsible for recovery.
- Your mobility means mechanics that punish standing still barely inconvenience you. Use it.

## Caster DPS (BLM / SMN / RDM / PCT)

- Slidecasting: you can move during the last ~0.5s of a cast without interrupting it. Practice this; it is how casters maintain uptime through mechanics.
- Swiftcast: instant cast. Best uses are movement mechanics and raises (RDM / SMN).
- Addle: magic damage reduction for the whole party. Coordinate with healer for raidwides or magic tankbusters.
- BLM: your movement is the most restricted. True North doesn't help you. Pre-position before mechanics resolve so you can hard-cast immediately after.

## Raising-capable DPS

RDM, SMN, BRD, MCH, DNC have access to Raise or equivalent.

```text
If the healer is dead: raise the healer first.
If both healers are dead (alliance): raise one.
If the healer is alive but occupied: you can raise whoever died.
Swiftcast + Raise is instant. Use it. Don't wait for permission.
```

A raised party member with Weakness still contributes more than a dead one.
