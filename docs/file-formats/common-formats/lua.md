---
description: LUA - A scripting language used to make life easier for programmers in a number of games.
---

# LUA
LUA is a scripting language found in a number of games. PSO2 and PS Nova use it rather frequently for much of the client logic. 
While most of it is compiled in both games, PSO2 does feature a lot of uncompiled LUA and sometimes allows uncompiled LUA to be used in place of compiled LUA.
As far as editing LUA code, there are countless resources on the web for this and it would seem best to allow the reader to enact their own judgement on which to use.

## unluac
unluac is a lua 5.x decompiler. Phantasy Star Online 2 and Phantasy Star Nova use a hefty amount of LUA and should work well with this. An example .bat that decompiles ALL .lua files in its own folder and all folders below it can be found here, but must be edited to refereonce your PC's Java install directory. [decompall.bat](../../../assets/common/decompall.bat)

[Download :fontawesome-solid-download:](https://sourceforge.net/projects/unluac/){ .md-button .md-button--primary target="_blank"}
[Source Forge Repo](http://hg.code.sf.net/p/unluac/hgcode/branches){ .md-button target="_blank"}