---
description: Tools for Phantasy Star Nova
---

## CriPakTools
Like most of the other 3d Phantasy Star games, Phantasy Star Nova uses Criware. This tool extracts its .cpk files and can also replace files inside them.

[Download :fontawesome-solid-download:](https://github.com/esperknight/CriPakTools/tree/master/Build){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/esperknight/CriPakTools/){ .md-button target="_blank"}

## Aqua Model Tool
Primarily made for Phantasy Star Online 2, Aqua Model Tool has limited support for Phantasy Star Nova .axs models and .aif textures. .aai animation is a similar format to the former two and while partly implemented cannot convert these files due to confusion regarding the keyframe formatting. 

[Download :fontawesome-solid-download:](https://github.com/esperknight/CriPakTools/tree/master/Build){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/esperknight/CriPakTools/){ .md-button target="_blank"}

## Sonic Audio Tools
Audio utilities for unpacking and reinserting Criware audio. PSO2 uses .acb files to store most of its sounds and so ACBEditor from this toolkit can be used to handle those. ACBFinder can be used to help match acbs to their paired awb files when necessary.

[Download :fontawesome-solid-download:](https://github.com/blueskythlikesclouds/SonicAudioTools/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/blueskythlikesclouds/SonicAudioTools){ .md-button target="_blank"}

## Google Sheets (No seriously)
Interestingly, rather than storing them in binary files, much of the metadata that was copied from PSO2 is stored in Unicode .csv spreadsheets. As this format is primarily text, a text editor such as [Notepad++](https://notepad-plus-plus.org/downloads/) may also be desirable, though harder to parse and compare entries with. Microsoft Excel can also handle these, but note that you will have to import the file as Unicode if you don't wish Japanese text to be garbled.

[Google Sheets link](https://docs.google.com/spreadsheets/u/0/?tgif=d)

## unluac
unluac is a lua 5.x decompiler. Phantasy Star Online 2 and Phantasy Star Nova use a hefty amount of .lua and should work well with this. An example .bat that decompiles ALL .lua files in its own folder and all folders below it can be found here, but must be edited to refereonce your PC's Java install directory. [decompall.bat](../../../assets/common/decompall.bat)

[Download :fontawesome-solid-download:](https://sourceforge.net/projects/unluac/){ .md-button .md-button--primary target="_blank"}
[Source Forge Repo](http://hg.code.sf.net/p/unluac/hgcode/branches){ .md-button target="_blank"}