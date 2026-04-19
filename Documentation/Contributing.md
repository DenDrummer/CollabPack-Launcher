---
created: 2026-04-08
modified: 2026-04-19
tags: []
---
## No AI
If you wish to contribute to this version of the project, no AI-generated anything is allowed to be included. No AI-generated code, images, etc. Using AI as a search engine is condoned, but should be done with caution as it makes mistakes.

If a fork wishes to remove this clause, they may do so as long as it is clearly mentioned what type of AI-content is included.
## Document what You've Changed
Please always update that status of what's implemented by updating the contents of the [[Implemented]] folder. You can look at the [[Plans]] folder for a rough outline.
### Adding Folders
Please always add a folder overview in the folder note, which should automatically be generated and opened upon creating a folder.

The easiest way to do this is by right-clicking in the folder note and selecting "Insert folder overview", which should be at the bottom (see screenshot below).
![[Insert Folder Overview.png]]
## Versioning
Both the CollabPack software, and by default the collaborative modpacks as well, will follow a slightly altered semantic versioning. More specifically, we'll be adding an extra number at the front representing the release.

Which means our versioning looks as follows:
```
<release>.<major>.<minor>.<patch>
```

- **Release** : Zero guarantee of compatibilities between release versions, even when going to a newer release version.
- **Major** : Going to a newer major version should have compatibility, but may contain breaking changes.
- **Minor** : Going to a newer version should have full compatibility, but going down in minor version could cause issues.
- **Patch** : going to a different patch version should have full compatibility as long as the other version numbers stay unchanged.

Versions are decided by released versions
