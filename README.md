# ArchValheim

A modpack for Arch Valheim players

## Setup

1. Retrieve the latest `AppImage` at https://github.com/ebkr/r2modmanPlus/releases
2. Run the `AppImage` and update r2modman if prompted
2. `chmod +x /path/to/r2modman-X.X.XX.AppImage`
3. `ln -s r2modman-X.X.XX.AppImage ~/.local/bin/r2modman`

Now, you can launch r2modman via ~/.local/bin/r2modman.

## Usage

1. Open `r2modman`
2. Select the *Game* tab, search for *Valheim*, select it, and choose *Steam*
3. Create a new profile
4. Browse for and install `ArchValheim`
5. Launch Valheim with *Start Modded* in the upper-left corner of r2modman
6. Log in to the server as per usual

NOTE: **DO NOT** follow update prompts in r2modman for outdated mods. The
`ArchValheim` modpack will maintain the correct versions for all mods we
use. Upstreams may update their mods, but we may be using outdated versions
purposefully.

## Required Mods

- denikson-BepInExPack_Valheim-5.4.2202
    - Plugin bootstrapper needed by all mods
- Azumatt-AzuAntiCheat-4.3.2
    - Checks/enforceds mods used by the client
- Advize-PlantEverything-1.16.2
    - Plant more than normal: raspberry bushes, Yggdrasil trees, etc
- Kevver-StayInYourBiome-1.0.2
    - Keep creatures in their own biomes regardless of boss kills

These mods are required by the client because all clients need to be
running them in order for them to be properly used at all.

## Optional Mods

### Part of the pack
- ComfyMods-ComfySigns-1.6.0
    - Makes your signs look better

### Not part of the pack
- Azumatt-AzuClock-1.0.2
    - A clock of in-game time
