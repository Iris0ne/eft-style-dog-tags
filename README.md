# EFT-style Dog Tags

A small S.T.A.L.K.E.R. GAMMA add-on that adds a single EFT-style dog tag item to human NPC corpses.

## Features

- Adds one generic dog tag item.
- Spawns dog tags on NPCs.
- Uses modest rank-weighted spawn chances.
- Dog tags are low-value trade items for now, but are ready for future expansion.

## Requirements

- S.T.A.L.K.E.R. GAMMA.
- Mod Organizer 2 is recommended.

## Install

### GAMMA / MO2

1. Download the repository as a ZIP from GitHub.
2. Extract it.
3. Copy the `EFT-style Dog Tags` folder into your MO2 mods folder.

```text
E:\GAMMA\mods\EFT-style Dog Tags
```

4. Open Mod Organizer 2.
5. Enable `EFT-style Dog Tags`.
6. Place it near the bottom of your load order, below GAMMA's core item and loot mods.
7. Launch the game through MO2.

Recommended load order: below GAMMA's core item and loot mods.

## Testing

Load a save, kill several human NPCs, and check their corpse inventories. Dog tags are common but not guaranteed on every body.

If the game crashes or the item does not appear, check your Anomaly log:

```text
E:\Anomaly\appdata\logs
```

Useful search terms:

```text
eft_dogtag
eft_dogtags
ui_icon_eft_dogtags
```

## Future hooks

The Black Market can later use this section ID as barter currency:

```text
eft_dogtag
```

## Balance

Tarkov dog tags scale by player level, but GAMMA NPCs are far more common than Tarkov PMCs and this add-on uses one generic item. The base cost is intentionally low at `150` rubles so selling stacks of tags does not break early progression.

## Credits

Created by Kyra.

Inspired by Escape from Tarkov's dog tag loot concept. This mod uses original config, script, and icon files made for GAMMA.
