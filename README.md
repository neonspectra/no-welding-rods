# No Welding Rods for Crafting and Repair

This is a mod for [Cataclysm: Dark Days Ahead](https://github.com/CleverRaven/Cataclysm-DDA).

Recently, welding rods were added as a requirement for vehicle crafting and repair. While this is more realistic, I'm of the opinion that welding rods aren't really balanced for gameplay purposes at this time. So much of my personal playstyle and enjoyment of this game comes from building giant Mad Max deathmobiles, and the introduction of welding rods makes it significantly more expensive to do vehicle crafting in a way that I personally don't find enjoyable.

As such, I made a simple mod to remove welding rods from crafting and repair recipes outright. Maybe welding rods will eventually get rebalanced in a way that makes it less tedious to build and repair large vehicles, but for now I've reverted the change entirely.


## Installation

This repository includes three flavours for this mod:
- `no-welding-rods`: Removes welding rods from both crafting, skill practice, and repair recipes
- `no-welding-rods-for-repair`: Removes welding rods from ONLY repair recipes. Welding rods are still required for crafting and skill practice.
- `no-welding-rods-for-crafting`: Removes welding rods from ONLY crafting and skill practice recipes. Welding rods are still required for repairs.

Each of the flavours has its own `modinfo.json` and should be treated as its own individual mod. Select *only one* of the three available flavours and copy it to your `/data/mods/` folder and activate it in a new game.

Congrats, you're back to being Mad Max!

## Compatibility

This mod is written for **0.F Experimental** builds. As of this writing, there is no stable build of the game that includes welding rods yet, so this mod is not necessary and should not be used on **0.F Stable**.

## Issues

- Welding rods will still display as a requirement for destroyed (`XX` condition) vehicle parts if you select them for repair. This is a weird quirk in the base game, but since destroyed components require a full replacement anyway, this shouldn't give you problems beyond being visually confusing.
- This mod does **NOT** prevent welding rods from spawning in the world. I'd have to edit drop lists and potentially open up the door for random mod conflicts and extra maintenance to this mod in order to do that. For a rebalance mod as simple as this, I think it's easier and less intrusive toward other mods for me to just advise you to ignore welding rods in the world as a useless item when you make use of this mod.
