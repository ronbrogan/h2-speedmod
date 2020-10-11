# Halo 2 SpeedMod Script Patches
This repo contains script patches that remove the boring parts of the game

## Changes
 - [Arbiter] Opens both doors at the end
 - [Oracle] Turns off kill volume below elevator
 - [Oracle] Removes 1 minute timer during lab fight
 - [Oracle] Removes the delay between cutting the three cables
 - [Oracle] Removes the pointless outdoor banshee section
 - [Regret] Speeds up underwater elevators by 2x
 - [Sacred Icon] Speeds up gap gondola by 2x
 - [Sacred Icon] Makes end flood spawns non-random, higher difficulties still spawn more waves
 - [Quarantine Zone] Skips end gondola ride
 - [Gravemind] Automatic prison skip
 - [High Charity] Prevent HC skip, requires starting final encounter to end the mission
 - [The Great Journey] Skip scarab section

## Applying the patches
The patches can be applied to maps using the MccBulkPatcher tool in the OpenH2 repository. This is already included in releases of this repo.

1. Download most recent release
2. Unzip to somewhere on your machine
3. Run OpenH2.MccBulkPatcher.exe
4. Copy your patched maps from the 'done' folder

If the patcher can't find your clean maps automatically, it will prompt for the directory they're in. Alternatively you can provide this on the command line:
```
OpenH2.MccBulkPatcher 1.0.0
Copyright (C) 2020 OpenH2.MccBulkPatcher

  --patches    The directory to pull patches from, defaults to 'patches'

  --maps       Source of clean maps, will auto detect windows store MCC installation folder

  --out        Destination of patched maps, will default to 'done' in current folder

  --help       Display this help screen.

  --version    Display version information.
```

## Opt-out
You can delete the patches that you don't want if you please. Each change is in its own subfolder.