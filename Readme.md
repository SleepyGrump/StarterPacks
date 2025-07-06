# Starter Packs Mod

Generates random starter packs for Backpack Hero. To use:

1. Find your mods folder (Steam > Manage > Browse local files > open "Mods")
1. Put the StarterPacks in it: `git clone https://github.com/SleepyGrump/StarterPacks.git` or download and extract it, whatever you've gotta do.
2. Enable debugging in Mods (Mods > check the little checkbox at the top that says "Debugging")
3. Check StarterPacks in the list of mods.
3. Start a game
4. Ctrl-S
5. Select "Starter Packs" from the dropdown
6. Click an item to spawn it.
7. Right-click the spawned item.
8. Click "Alternate Use"

Note: No consideration is given to size currently. You'll have to figure that out yourself!

Extra item: A Random Starter Pack - generates an entirely random starter pack from the list below.

Starter packs:

- Archery
- Berserker
- Cleavers (not available for CR-8)
- Magic
- Melee
- Scratch
- Shuriken
- Spikes
- Structure
- Holy
- Drummer - Satchel-only
- Musician - Satchel-only
- Rancher - requires a "Kin" mod such as Kirby's Pokepack
- Farmer - requires a "Plant" mod such as Chuck's Plants vs Zombies Mod
- Gear - CR8-only
- Mythic Archer
- Mythic Fighter

TODO:

- Mythic Shuriken (Unfinished)
  - Same as regular but with Brutal Bombstone included?
- Iconic Fighter (Unfinished)
  - Iconic weapon from base game - pickaxe, assass dagger
  - Same fighter stuff as usual
  - Is this handled by Mythic Fighter?? Would it be better to make an Iconic pack for each weapon?
- Better art.
- A modpack icon
- Consider redoing the spawn of RPG essences to be done the "correct" way - the "wrong" way works, but does have error messages.

Features I want but can't add:

- There's no way to test whether a modpack exists before trying to spawn items from it. That sucks.
- Spawning items of a specific size doesn't work (unless you make the spawning item exactly that size and replace it only with items of a similar size, which does not do what I want it to).
- The ability to apply a "must keep this item" modifier to whatever spawns. Not sure I want this but it might be a fun puzzle mode.
