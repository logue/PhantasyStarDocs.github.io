---
description: Archive tools for Phantasy Star Online 2
---

## NGS Packer
An alternative ICE unpack and repacking tool. Features a Japanese translation and the ability to unpack specific files based on a list rather than the whol

[Download :fontawesome-solid-download:](https://github.com/logue/NgsPacker/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/logue/NgsPacker){ .md-button target="_blank"}

## Zamboni
An ICE archive unpack and repacker, ICE being the majority of loose game files. Contains functionality for batch extraction and batch listing file contents. 
While internal file grouping is handled via extraction folder now, it is possible to use the older japanese ice.exe's method of setting group 1 files via a group1.txt if the files being packed are not in group folders. Has basic command line functionality. Almost every file in the current game build and past builds unpacks. 3 v3 ICE files are the exception to this rule right now (but they contain nothing special and may not be used now by the game).

[Download :fontawesome-solid-download:](https://github.com/Shadowth117/Zamboni/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/Shadowth117/Zamboni/){ .md-button target="_blank"}

## CriPakTools
Like most of the other 3d Phantasy Star games, Phantasy Star Online 2 uses Criware. This tool extracts its .cpk files and can also replace files inside them. For Phantasy Star Online 2, .cpk files should only contain audio related data, typically .hca in the final game.

[Download :fontawesome-solid-download:](https://github.com/esperknight/CriPakTools/tree/master/Build){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/esperknight/CriPakTools/){ .md-button target="_blank"}

## Sonic Audio Tools
Audio utilities for unpacking and reinserting Criware audio. PSO2 uses .acb files to store most of its sounds and so ACBEditor from this toolkit can be used to handle those. ACBFinder can be used to help match acbs to their paired awb files when necessary.

[Download :fontawesome-solid-download:](https://github.com/blueskythlikesclouds/SonicAudioTools/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/blueskythlikesclouds/SonicAudioTools){ .md-button target="_blank"}

## Fpk Tool
A tool for unpacking the .fpk file the game used during the middle of its lifespan until nearly the end. While originally stored in ICE files, now fpk files contain a number of important .lua files that define much of the game client logic. Somewhere towards the end of classic PSO2's life this format was retired and superceded by a newer variant with compression. PSO2 NGS has its own separate .fpk as well, since its release. The newer variant has no available unpacking tool

[Download :fontawesome-solid-download:](https://github.com/Shadowth117/FpkTool/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/Shadowth117/FpkTool){ .md-button target="_blank"}