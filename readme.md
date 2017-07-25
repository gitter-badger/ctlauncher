# ctlauncher
[![Build Status](https://travis-ci.org/crafting-table/ctlauncher.svg?branch=master)](https://travis-ci.org/crafting-table/ctlauncher)
[![Windows Build](https://img.shields.io/appveyor/ci/crafting-table/ctlauncher.svg)](https://ci.appveyor.com/project/maccelerated/ctlauncher)
[![Dependency Status](https://david-dm.org/crafting-table/ctlauncher.svg?theme=shields.io)](https://david-dm.org/crafting-table/ctlauncher)
[![License](https://img.shields.io/github/license/crafting-table/ctlauncher.svg)](license)
> An unnecessary and exorbitant mod pack launcher for Minecraft and Forge.

# *FIRST PUSH HAS GOTTA WAIT*
I'll upload stuff soon enough. I'm serious.

## Introduction

The Crafting Table Launcher is a Just Because™ project. There are plenty of great mod pack launchers available for Minecraft. There was *no need what-so-ever* to make this. Honestly, I think wrote it as an Electron app just because I'm a bad person.


## Contributing

> Please use GitHub to submit issues and pull requests.

- `npm i`
- `npx rollup -c -w`
- `npx electron .`
- `npm up` when packages update (`ncu` is also nice)
- `rm -rf node_modules` whenever `npm^5` does a dumb


## Features

- [x] Launch mod packs with just their folders
- [ ] Download pack updates in the background
- [x] Save disk space by sharing files between packs
- [x] Validate every file by checksum for safety
- [ ] See server player list and TPS from the launcher
- [ ] Adorable in-game styled interface
- [ ] Optionally show download ad portals for mods that need support

For mod pack managers:

- [x] Simple *CT-style* mod pack JSON files
- [ ] Dead simple drag and drop mod pack editor
- [ ] Host mod packs from a custom API
- [x] Forge support
- [ ] Sponge support
- [ ] Add Sponge plugins from Ore
- [ ] *CrashAssist* bundles crash data *(never explain where log files are again)*
- [ ] *ConfigAssist* tracks cfg files and adds changes to packs
- [ ] Central repository for crash fixes
- [ ] Admins can monitor and control *ctable* hosted servers
- [ ] Import mod packs from Technic Platform
- [ ] Import mods from [Curse](https://mods.curse.com/mc-mods/minecraft)
- [ ] Import mods from [ModList](http://modlist.mcf.li/)

For contributors:

- [x] Imitates vanilla launcher file placement
- [x] Modify install/launch processes with plugins
- [ ] Create bug detail Gists from within launcher
- [ ] Bug report parser to launch app with broken configuration
- [x] Writing in JS makes anyone hate life
- [ ] Appveyor thingy for Windows releases?
- [ ] Travis for linux releases?
