---
description: ACB - Criware sound container, usually used for sound effects. Typically contains [HCA](./hca.md) or [ADX](./adx.md) audio.
---

# ACB
ACB is an audio container format found across many games which feature Criware usage. It's comparable to similarly ubiquitous CSB format by Criware which has essentially the same purpose.
PSO2 and Nova use these for every sound effect with the audio inside being .hca audio, encrypted with different keys depending on where it was found. 

## AWB
AWB files are companion files to ACB and sometimes contain the actual data for audio referenced within an ACB. These have AFS2 as their magic integer. ACBFinder in Sonic Audio Tools can be used to help locate these for their paired ACB.

## Editing
Sonic Audio Tools can be used to extract the contents of these files for editing. See [HCA](./hca.md) or [ADX](./adx.md) for audio clip editing. 
Some ACB files don't contain all of their actual audio data and one will need an accompanying AWB file for that. 

[Download :fontawesome-solid-download:](https://github.com/blueskythlikesclouds/SonicAudioTools/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/blueskythlikesclouds/SonicAudioTools){ .md-button target="_blank"}