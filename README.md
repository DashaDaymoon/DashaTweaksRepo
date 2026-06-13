# DashaTweaks — Dalamud plugin repository

This is the install repository for **DashaTweaks**, a Dalamud (FFXIV) plugin
with a growing collection of quality-of-life tweaks (hotbar audit, submarine
route planning, craft-leve hand-ins).

## How to install in-game

1. Make sure you have [XIVLauncher / Dalamud](https://goatcorp.github.io/) set up.
2. In-game, open the Dalamud settings with `/xlsettings`.
3. Go to the **Experimental** tab.
4. Under **Custom Plugin Repositories**, paste this URL into an empty row:

   ```
   https://raw.githubusercontent.com/DashaDaymoon/DashaTweaksRepo/main/pluginmaster.json
   ```

5. Click the **+** to add it, then click **Save and Close** (the floppy-disk icon).
6. Open the plugin installer with `/xlplugins`, search for **DashaTweaks**, and
   click **Install**.

Updates show up in `/xlplugins` automatically whenever a new version is released here.

## Features

See the in-game plugin description, or the [Punchline](pluginmaster.json) in the manifest.

## Notes

This repository hosts only the installable build and its manifest. Each release
on this repo's [Releases page](https://github.com/DashaDaymoon/DashaTweaksRepo/releases)
contains `latest.zip` (the packaged plugin).
