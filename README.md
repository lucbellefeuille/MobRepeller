**MobRepeller**

MobRepeller is a lightweight Bukkit/Spigot 1.12.2 plugin (CatServer-compatible) that keeps your base peaceful in heavily-modded worlds. Players build small “Totems” (a 2D plus sign made from a single core block) that block natural hostile spawns in a radius and gently push hostiles outward—without disturbing villagers, CustomNPCs, MineColonies citizens, pets, or neutral wildlife.

Starter cores (Clay, Coal, Hay) give 25m, then Iron 50m, Gold 100m, Diamond 150m. A floating hologram shows the tier and range. Totems register when you finish the cross; breaking any arm/center near the core removes it (and its hologram).

Hostiles include vanilla Monsters and creatures from popular packs like Lycanites Mobs, Ice and Fire: Dragons, Advent of Ascension (AoA3), The Twilight Forest, Mowzie’s Mobs, Grimoire of Gaia, Primitive Mobs, DivineRPG, The Betweenlands, The Erebus, AbyssalCraft, Fossils and Archeology Revival, and Tropicraft. Neutral/ambient frameworks—CustomNPCs, Citizens, MineColonies, Animania, Chococraft, Forestry (bees/butterflies), OpenBlocks utilities, Oceanic Expanse, Aquatic Odyssey, Better Animals Plus, Exotic Birds, Aquaculture 2, ZAWA (Zoo & Wild Animals), Mystical Wildlife, MyPet—are whitelisted and never shoved.

Players get a first-join guide book and a one-time tip on their first core block. Admins tune ranges, hostile/whitelist sets, and hologram height in config.yml. Simple.

Server-friendly. New-player proof.


**Features**
- Totem fields
- Core blocks & radii: Clay 25m, Coal 25m, Hay 25m, Iron 50m, Gold 100m, Diamond 150m
- Hologram label shows tier + range (height configurable)
- Removes when any nearby core block is broken (hologram despawns)


**Spawn control**
- Cancels natural-ish hostiles: NATURAL, CHUNK_GEN, REINFORCEMENTS, NETHER_PORTAL
- Does not affect spawners, spawn eggs, commands, or scripted spawns
- Hostiles inside the field are nudged outward; lingerers can be hard-ejected


**New-player onboarding**
- First-join guide book (“MobRepeller”)
- One-time build tip when placing the first core block


**Neutral / NPC whitelist (never pushed)**
- CustomNPCs,
- Citizens,
- MineColonies,
- Animania,
- Chococraft,
- Forestry (bees/butterflies),
- OpenBlocks (utilities like Luggage),
- Oceanic Expanse,
- Aquatic Odyssey,
- Better Animals Plus,
- Exotic Birds,
- Aquaculture 2,
- ZAWA (Zoo & Wild Animals),
- Mystical Wildlife,
- MyPet

**Vanilla types**
- Villager,
- Iron Golem,
- Snow Golem,
- Horses/Donkey/Mule/Llama,
- Wolf,
- Ocelot,
- Parrot,
- Rabbit,
- Chicken,
- Cow,
- Sheep,
- Pig,
- Squid,
- Bat,
- Polar Bear,
- Mooshroom

You can add or remove additional neutral packs in config.yml.


**Hostile recognition**
Anything that is a vanilla Monster, plus well-known mob packs such as:
- Lycanites Mobs,
- Ice and Fire: Dragons,
- Advent of Ascension (AoA3),
- The Twilight Forest,
- Mowzie’s Mobs,
- Grimoire of Gaia,
- Primitive Mobs,
- DivineRPG,
- The Betweenlands,
- The Erebus,
- AbyssalCraft,
- Fossils and Archeology Revival,
- Tropicraft

Extendable through hostile.packages / hostile.types in config.yml.


**Building a Totem**
- Shape: a 2D + cross (6 blocks total) made from one core material.

Clay – 25m
![Clay_Totem](https://github.com/lucbellefeuille/mobrepeller/blob/main/clay.png)
Coal – 25m
![Coal_Totem](https://github.com/lucbellefeuille/mobrepeller/blob/main/coal.png)
Hay – 25m
![Hay_Totem](https://github.com/lucbellefeuille/mobrepeller/blob/main/hay.png)
Iron – 50m
![Iron_Totem](https://github.com/lucbellefeuille/mobrepeller/blob/main/iron.png)
Gold – 100m
![Gold_Totem](https://github.com/lucbellefeuille/mobrepeller/blob/main/gold.png)
Diamond – 150m
![Diamond_Totem](https://github.com/lucbellefeuille/mobrepeller/blob/main/diamond.png)

**Commands**
- /mobrepeller ping
- /mobrepeller count
- /mobrepeller list
- /mobrepeller register
- /mobrepeller save
- /mobrepeller removehere
- /mobrepeller cleanup
- /mobrepeller cleanupall
- /mobrepeller reload
- /mobrepeller debug


**Configuration**
- Hostile/neutral mod sets and vanilla types are editable in config.yml.


**Compatibility**
- Server: Bukkit/Spigot/Paper 1.12.2 (CatServer-compatible)
- Works cleanly alongside Forge mods.


**License & Credit**
- License: BSD 3-Clause (see LICENSE).
- Keep copyright/notice headers and credit: “MobRepeller by Luc Bellefeuille”
- Commercial redistribution is permitted by the license; attribution is required.


**Credits**
- Design & code: Luc Bellefeuille — PRs for additional presets welcome.
