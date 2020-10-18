# Halo 2 SpeedMod Script Patches
This repo contains script patches that remove the boring parts of the game

## Changes
 - [Cairo] Resets marine aggression at the start of hangar 1 fight
 - [Cairo] Allow progression from Hanger 1 and 2 before dialog is finished
 - [Outskirts] Remove blinking sequence at mission start
 - [Outskirts] End level at the beginning of the shadow encounter
 - [Metropolis] [Skip bridge, spawn in tunnels before first wall](https://youtu.be/0yjBsorlJAA)
 - [Metropolis] Fix scarab deload
 - [Metropolis] Make enemies spawn in scarab earlier
 - [Arbiter] Reduce first air lock delay
 - [Arbiter] [Opens both doors at the end](https://www.youtube.com/watch?v=-hCa-Cgu7ew)
 - [Oracle] Turns off kill volume below elevator
 - [Oracle] Removes 1 minute timer during lab fight
 - [Oracle] Reduces delay for airlock after lab fight
 - [Oracle] [Removes the delay between cutting the three cables](https://www.youtube.com/watch?v=MBtXdP7CaBU)
 - [Oracle] Removes the pointless outdoor banshee section
 - [Delta Halo] Make title fade out quicker to bring HUD up earlier
 - [Regret] Speeds up underwater elevators by 2x
 - [Regret] Skips gondola 2
 - [Sacred Icon] [Speeds up gap gondola by 2x](https://www.youtube.com/watch?v=UhR3NBcD0vo)
 - [Sacred Icon] Makes end flood spawns non-random, higher difficulties still spawn more waves
 - [Quarantine Zone] Skips end gondola ride
 - [Gravemind] [Automatic prison skip](https://www.youtube.com/watch?v=XMUxfDEvqoA)
 - [Gravemind] Remove random delay in the council lift enemy spawn
 - [High Charity] Make trigger over slow lift check more frequently
 - [High Charity] Prevent HC skip, requires starting final encounter to end the mission
 - [The Great Journey] Remove `game_safe_to_save` check for scarab cutscene to start
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