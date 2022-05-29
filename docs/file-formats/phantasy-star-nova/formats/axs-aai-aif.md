---
description: AXS, AAI, and AIF formats. Graphics formats which are all technically the same.
---

# AXS, AAI, and AIF
These are all actually the same format, but are differentiated by what they store. 
AXS files are model files and can contain textures as well. Node hierarchies exist directly within these. 
AIF files are purely for textures. Textures appear to all be DDS, but with Playstation swizzling.
AAI files are for animations and effects. 
As Phantasy Star Nova was developed by tri-Ace, these formats are similar to what might be found in games such as the Star Ocean series, albeit not quite the same as any of those. 
In many cases, PSO2 files seem to have been converted rather directly to these formats, although it's unclear if they were converted from their source versions or not.

Aqua Model Tool can convert most of the AXS and AIF files. AAI files are partly implemented, but unfortunately the keyeframes are read in an unusual way. Without further analysis, it is not possible to convert these.

[Download :fontawesome-solid-download:](https://github.com/Shadowth117/PSO2-Aqua-Library/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/Shadowth117/PSO2-Aqua-Library/){ .md-button target="_blank"}
