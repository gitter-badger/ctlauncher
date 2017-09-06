# ctlauncher

[![Join the chat at https://gitter.im/crafting-table/ctlauncher](https://badges.gitter.im/crafting-table/ctlauncher.svg)](https://gitter.im/crafting-table/ctlauncher?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)
[![License](https://img.shields.io/github/license/crafting-table/ctlauncher.svg)](license.md)
> An unnecessary and exorbitant mod pack launcher for Minecraft and Forge.

# *FIRST PUSH HAS GOTTA WAIT*
I'll upload stuff soon enough. Tests and refactor is almost done.

## Introduction

The Crafting Table Launcher is a Just Because™ project. There are plenty of great mod pack launchers available for Minecraft. There was *no need what-so-ever* to make this. Honestly, I think wrote it as an Electron app just because I'm a bad person.

**A Mojang account from [Minecraft Java Edition](https://minecraft.net/) is required to play.**

## Contributing

> Please use GitHub to submit issues and pull requests.

- `npm i`
- `npx rollup -c -w`
- `npx electron .`
- `npm up` when packages update (`ncu` is also nice)
- `rm -rf node_modules` whenever `npm^5` does a silly


## Features

- [x] Uses Mojang account for all authentication
- [x] Launch mod packs with just their folders
- [ ] Download pack updates in the background
- [x] Save disk space by sharing files between packs
- [x] Validate every file by checksum for safety
- [ ] See server player list and TPS from the launcher
- [ ] Adorable in-game styled interface
- [ ] Optionally show download ad portals for mods that need support

For mod pack managers:

- [x] Simple *CT-style* mod pack JSON files
- [ ] Super simple drag and drop mod pack editor
- [ ] Serve mod packs from a custom API
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

## License

Please contact <robmac@maccelerated.me> with licensing and legal inquiries.

> This repository is licensed as described in [license.md](license.md).

> This repository is not affiliated with Mojang, Microsoft, or Twitch.

> "Minecraft" is a trademark of Mojang Synergies AB.
