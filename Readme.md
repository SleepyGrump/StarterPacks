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

Note: No consideration is given to size currently. You'll have to figure that out yourself! That's why extra items spawn - to give you a choice between them in case they don't fit.

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
- Rancher - requires a "Kin" mod such as Kirby's Pokepack or one of Chuck's creature mods
- Farmer - requires a "Plant" mod such as Chuck's Plants vs Zombies Mod
- Gear - CR8-only
- Mythic Archer
- Mythic Fighter
- Mythic Magician
- Mythic Shuriken
- The Legend - not a "pack" per se, will spawn a single legendary item and a random essence. It's up to you to make it work!

Two extra items, required in order to make the Magic starter packs work:

- Desaturated manastone - just your standard common manastone, reskinned (because the original isn't spawnable by item creator). It's listed as Unfindable, yet still shows up the same way ordinary manastones do, which is mildly annoying.
- Mythic manastone - just a Black Manastone reskinned (again, just to make it be spawnable by item creator). Might show up in game due to manastone specialness.

TODO:

- Better art. Always.
- A modpack icon

Features I want but can't add:

- There's no way to test whether a modpack exists before trying to spawn items from it. That sucks.
- Spawning items of a specific size doesn't work for this. Example: Replacing a Wooden Sword-sized item with any sameSizeItem sometimes results in the Aged Shield because, uh. It's 3 squares... so same exact size, if not same dimensions. :/ Plus, it's not limited by type. You'll get *any* item of that size, even if you specify "byType" and "Melee". So, no joy there. (Yes, I dug into this. Again.)
- I'd love to actually make these items available in the game itself at Matthew. Not currently possible, however, so this is the workaround.
