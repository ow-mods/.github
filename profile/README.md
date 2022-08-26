# [Outer Wilds Mods](https://outerwildsmods.com)

This organization contains all the repos relating to the [Outer Wilds](https://store.steampowered.com/app/753640/Outer_Wilds/) modding ecosystem.

## The ecosystem

- The [mod database](https://github.com/ow-mods/ow-mod-db) is at the center of it all. Modders submit their mods there, and the database updates itself using the repository metadata from each mod. This "database" is just a static file, but it updates itself periodically to get the latest mod versions, download counts, etc.
- The [mods website](https://github.com/ow-mods/outerwildsmods.com) is built based on information fetched from the mod database and the repository readmes from each mod.
- The [mod manager](https://github.com/ow-mods/ow-mod-manager) downloads and installs mods using information from the mod database.
- [OWML](https://github.com/amazingalek/OWML) loads the mods into the game. It is usually downloaded and installed by the mod manager.
