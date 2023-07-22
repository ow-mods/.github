# [Outer Wilds Mods](https://outerwildsmods.com)

![Website](https://img.shields.io/website?label=Website&style=flat-square&url=https%3A%2F%2Fouterwildsmods.com%2F)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ow-mods/outerwildsmods.com/auto-deploy.yml?label=Website%20Workflow&style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ow-mods/ow-mod-db/update-releases.yml?label=Mod%20Database&style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ow-mods/ow-mod-download-history/update-download-history.yml?label=Download%20Extractor&style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ow-mods/ow-branch-watcher/main.yml?label=Branch%20Watcher&style=flat-square)

This organization contains all the repos relating to the [Outer Wilds](https://store.steampowered.com/app/753640/Outer_Wilds/) modding ecosystem.

## The Ecosystem
- The [mod database](https://github.com/ow-mods/ow-mod-db) is at the center of it all. Modders submit their mods there, and the database updates itself using the repository metadata from each mod. This "database" is just a static file, but it updates itself periodically to get the latest mod versions, download counts, etc.
- The [mods website](https://github.com/ow-mods/outerwildsmods.com) is built based on information fetched from the mod database and the repository readmes from each mod.
- The [download extractor](https://github.com/ow-mods/OWModDBDownloadCountExtractor) extracts the download counts for every mod over time from the mod database.
- The [mod manager](https://github.com/ow-mods/ow-mod-man) downloads and installs mods using information from the mod database.
- [OWML](https://github.com/ow-mods/owml) loads the mods into the game. It's what actually makes mods work, so kind of a big deal. It is usually downloaded and installed by the mod manager, but can also be used manually (bypassing all this ecosystem bs if you so wish).
- The [mod template](https://github.com/ow-mods/ow-mod-template) is a .NET project template that makes it easier to create mods.
- The [game libraries](https://github.com/ow-mods/OuterWildsGameLibs) stores the stripped, publicized game libraries and pushes them to a Nuget package.
- The [Outer Wilds Alpha mod loader](https://github.com/ow-mods/OWAML) is a Bepinex helper for loading mods into the alpha of Outer Wilds.
- The [alpha game libraries](https://github.com/ow-mods/OuterWildsAlphaGameLibs) stores the stripped, publicized game libraries of the alpha and pushes them to a Nuget package.

## Modding Discord Specific
- The [weekly report generator](https://github.com/ow-mods/ow-weekly-report) generates a report every week the top 10 most downloaded mods, how many times they were downloaded in the past week, and their change in ranking from last week.
- The [branch watcher](https://github.com/ow-mods/ow-branch-watcher) watches the Steam product information for Outer Wilds, and posts a message every time a branch is updated, added, or deleted.
