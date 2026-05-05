# Hytale Mod: Custom NPC Spawning (Slime + Feran Merchant)

Companion mod for the [Hytale Modding Manual](https://hytale-moddings.github.io/hytale-modding-docs/) tutorial on **Custom NPC Spawning**.

**Repository:** [hytale-moddings/hytale-mods-custom-npc-spawns](https://github.com/hytale-moddings/hytale-mods-custom-npc-spawns)

## What This Mod Does

Adds **world spawn rules** for two custom NPCs:
- **Slime** in Azure forests
- **Feran Enchanted Merchant** in Feran cities

Demonstrates both world spawns (use `Id`, no prefix) and the difference from marker spawns (which require `Group:Name` prefix for cross-mod NPCs).

## Installation

1. Copy the mod folder to `%APPDATA%/Hytale/UserData/Mods/NPCSpawning/`
2. The folder name **must** be `NPCSpawning`
3. **Requires:** [CreateACustomNPC](https://github.com/hytale-moddings/hytale-mods-custom-npc) and [NPCShopsAndTrading](https://github.com/hytale-moddings/hytale-mods-custom-shop)
4. Start a Hytale server with the mod enabled

## Manifest

- **Group:** HytaleModdingManual
- **Name:** NPCSpawning
- **Version:** 1.0.0
- **Dependencies:** `HytaleModdingManual:CreateACustomNPC@1.0.0`, `HytaleModdingManual:NPCShopsAndTrading@1.0.0`

## Related

- [Tutorial: Custom NPC Spawning](https://hytale-moddings.github.io/hytale-modding-docs/tutorials/intermediate/custom-npc-spawning/)
- [Slime NPC mod](https://github.com/hytale-moddings/hytale-mods-custom-npc)
- [Feran Merchant mod](https://github.com/hytale-moddings/hytale-mods-custom-shop)
- [Hytale Modding Manual](https://hytale-moddings.github.io/hytale-modding-docs/)

## License

MIT
