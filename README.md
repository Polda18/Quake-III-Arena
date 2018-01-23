# Quake-III-Arena
Fixing the Quake III arena source to compile and impl. automated testing.

* Now working with VC12 Visual Studio 2013 Community Edition.

## Infected game mode
I'm adding a new gametype to the game: Infected. It is supposed to be a remake of existing game mode Infected known from Quake Live, made available for vanilla Quake 3 players. In Quake Live, it is in fact a modification of another game mode: Red Rover. As with Quake 3 modification, it will be a completely standalone game mode, that is set by default (forcing a changed default g_gametype value). It should be compatible with TDM gametype (TDM backwards compatibility support fallback included), thus displaying like Team Deathmatch in baseq3 match browser. As much as I know, vanilla Quake 3 takes modification physics and functions to the vanilla client temporarily, enabling running extended game modes provided by backwards compatibility with vanilla game modes.

## Help appreciated
I'm a novice in modifying existing source code for game modification (installed in game root directory, using precompiled .qvm files or dynamic libraries for specific OS - Windows, Mac or Linux), so help is highly appreciated. You'll be credited in release readme, of course.
