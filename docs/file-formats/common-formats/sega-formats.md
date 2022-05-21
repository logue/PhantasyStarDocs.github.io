---
description: Sega Formats - A brief overview of common structures in Sega game formats.
---

# Sega Formats
Across the years, Sega has worked on a number of proprietary game libraries across various platforms.
Phantasy Star games have been entangled in most of them in one way or another.
While most of the games don't share specific formats, there are specific things that are commonly found in them.

## Ninja Formats
All direct attachments to the first PSO use the formalized version of Sega's Ninja libraries from the Dreamcast. 
The term 'formalized' is used since unlike the Sonic Adventure titles, Phantasy Star games used the standardized header and footer data for ninja which was seen in most usages of the format.
In PSO, ninja related files will have a magic such as 'NJCM' at the very start, describing the format, followed by a file size of all data after the size until the footer. These first 8 bytes will ALWAYS be little endian regardless of platform.
In some cases, ninja files will be laid out in sequence in a single file, typically with an NJTL texture list followed by a model, possibly animations, and possibly textures.

The footer will have a POF0 magic. Some games will instead use a variation with POF1, but POF0 should be expected in PSO1. The footer includes a table of encoded offsets in the file to pointers in order to update them at runtime.
A basic tool for this which outlines the masking system in its source can be found here:

[Download :fontawesome-solid-download:](https://github.com/Shadowth117/POF0Reader/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/Shadowth117/POF0Reader){ .md-button target="_blank"}

## Sega NN and Aqua
Sega's NN formats are a successor to its earlier Ninja. PSU, the Phantasy Star Portable games, and Phantasy Star Zero use a variation of these formats. While PSO2 uses a different, later branch of the format called Aqua, identifying aspects are similar to the aforementioned NN.
These formats all have brief 0x20 byte headers, the magic in them always in reference to their particular platform. Most NN games also feature a NOF0 footer. Unlike POF0, these NOF0s do not feature encoded offsets and are simply all standard 32 bit offsets. Following the NOF0, there may be a NEND as well.
Curiously, PSU and the Phantasy Star Portable series NN data lacks the NOF0 and instead uses an offset table attached to the end of their respective NBL archives. This may be why their formats have slightly different naming, ex. (PSU PC) .xnj vs (Xbox 360 little endian NN).xno.

A parser similar to the NOF0 parser above can be used to dump NOF0 data from PSO2 Aqua formats (and possibly standard NN) in Aqua Model Tool's Debug options. These options will require you to compile the tool as Debug instead of Release.

[Download :fontawesome-solid-download:](https://github.com/Shadowth117/PSO2-Aqua-Library/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/Shadowth117/PSO2-Aqua-Library/){ .md-button target="_blank"}
