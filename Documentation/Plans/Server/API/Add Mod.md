---
created: 2026-04-08 - 19:07:48
modified: 2026-04-10 - 21:31:12
tags: []
---
## Parameters
<sub>(may also require game-id and/or download source (CurseForge, Modrinth, …) if/once more games and/or download sources are added to the launcher)</sub>
### Username
Or user-ID, depending on how this gets implemented.
### Mod-ID
The ID of the mod on the download source.
### Mod-version
The version of the mod on the download source.
### Server- and/or Clientside
Whether the mod is clientside, serverside, or a combination of client- and serverside.

Valid states:
- **Server** : for mods that are only needed serverside (e.g. Bluemap)
- **Client** : for mods that are only needed clientside (e.g. Just Zoom)
- **Both** : for mods that are needed both serverside and clientside to work properly (e.g. Create)
- **OptionalServer** : only needed clientside, but will work better or have extra functionality when also added on the server (e.g. Xaero's World Map)
- **OptionalClient** : only needed serverside, but may improve experience when also present clientside.
- **Unknown** : when the person adding it isn't sure. The default value when not provided. Will always require manual review from someone with access rights to the CollabPack Server.
### Compatibility Level
Valid states:
- **Full** : can be safely added without issues.
  Will require at least a patch update of the game-server for it to be added.
  Structure-generating mods that don't add new blocks, features or advancements, like the majority of YungNickYoung's Minecraft mods, fall under this category.
- **Backward** : existing worlds will be compatible, but new worlds won't be backwards compatible.
  Will require at least a minor update of the game-server for it to be added.
- **Forward** : these mods make such drastic changes that adding them to existing worlds is likely or certain to cause issues, including but not limited to: ugly chunk borders, ugly biome borders, structures being cut off in the middle, …
  Will require at least a major update of the game-server for it to be added.
- **None** : adding these mods makes loading previous worlds impossible
### Safety of Removal
Valid states:
- **Safe** : Can be safely removed without consequences.
  Will require at least a patch update to remove it again.
- **Risky** : Removing may result in issues with existing worlds.
  Will require at least a minor update to remove it again, but likely a major version.
- **Unsafe** : Will likely make it impossible to load existing worlds.
  Will require at least a major update to remove it again, but might require a new release.
