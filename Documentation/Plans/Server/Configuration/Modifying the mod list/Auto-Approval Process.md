---
created: 2026-04-26
last-opened: 2026-04-26
tags:
  - Plans/Server
---
These are the checks the server will go through when doing an [[Automatic Game Server Updates|automated game server update]].

In the first version, it'll just be a simple "you want to add this? Approved"

But at some point I hope to build in a couple of checks:
- Do the mods comply with mod category configuration of the CollabPack server?
- Can the client boot to menu with the modified modlist?
- Can the client open a singleplayer game with the modified modlist?
- Can the game server boot with the modified modlist?

These are only to check if the modpack still loads at all, not for compatibility.
