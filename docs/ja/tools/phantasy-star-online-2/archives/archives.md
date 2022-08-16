---
description: Archive tools for Phantasy Star Online 2
---

# ファンタシースターオンライン２向けアーカイブツール

## NGS Packer

代替 ICE アンパックおよびリパック ツール。 日本語の翻訳と、全体ではなくリストに基づいて特定のファイルを解凍する機能を備えています

[Download :fontawesome-solid-download:](https://github.com/logue/NgsPacker/releases){ .md-button .md-button--primary target="\_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/logue/NgsPacker){ .md-button target="\_blank"}

## Zamboni

ICE アーカイブのアンパックとリパッカーであり、ICE は通常のゲームファイルの大部分を占めています。 バッチ抽出およびゲームファイル内のファイルリスト取得機能が含まれます。

現在、内部ファイルのグループ化は抽出フォルダーを介して処理されますが、パックされるファイルがグループフォルダーにない場合、予め定義された`group1.txt`を介して group1 ファイルを設定するという、古い日本の ice.exe の方法を使用することができます。 基本的なコマンド ライン機能を備えています。 現在のゲーム ビルドと過去のビルドのほぼすべてのファイルをアンパックすることができます。v3 の ICE ファイルは、現時点ではこのルールの例外です。（ただし、特別なものは何も含まれていないため、現在ゲームで使用されていない可能性があります)

[Download :fontawesome-solid-download:](https://github.com/Shadowth117/Zamboni/releases){ .md-button .md-button--primary target="\_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/Shadowth117/Zamboni/){ .md-button target="\_blank"}

## CriPakTools

Like most of the other 3d Phantasy Star games, Phantasy Star Online 2 uses Criware. This tool extracts its .cpk files and can also replace files inside them. For Phantasy Star Online 2, .cpk files should only contain audio related data, typically .hca in the final game.

[Download :fontawesome-solid-download:](https://github.com/esperknight/CriPakTools/tree/master/Build){ .md-button .md-button--primary target="\_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/esperknight/CriPakTools/){ .md-button target="\_blank"}

## Sonic Audio Tools

Audio utilities for unpacking and reinserting Criware audio. PSO2 uses .acb files to store most of its sounds and so ACBEditor from this toolkit can be used to handle those. ACBFinder can be used to help match acbs to their paired awb files when necessary.

[Download :fontawesome-solid-download:](https://github.com/blueskythlikesclouds/SonicAudioTools/releases){ .md-button .md-button--primary target="\_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/blueskythlikesclouds/SonicAudioTools){ .md-button target="\_blank"}

## Fpk Tool

A tool for unpacking the .fpk file the game used during the middle of its lifespan until nearly the end. While originally stored in ICE files, now fpk files contain a number of important .lua files that define much of the game client logic. Somewhere towards the end of classic PSO2's life this format was retired and superceded by a newer variant with compression. PSO2 NGS has its own separate .fpk as well, since its release. The newer variant has no available unpacking tool

[Download :fontawesome-solid-download:](https://github.com/Shadowth117/FpkTool/releases){ .md-button .md-button--primary target="\_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/Shadowth117/FpkTool){ .md-button target="\_blank"}
