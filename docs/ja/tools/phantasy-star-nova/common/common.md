---
description: ファンタシースターノヴァ向けツール
---

# ファンタシースターノヴァ向けツール

## CriPakTools

他のほとんどの 3D ファンタシー スター ゲームと同様に、ファンタシー スター ノヴァは Criware を使用しています。 このツールは、その .cpk ファイルを抽出し、その中のファイルを置き換えることもできます。

[Download :fontawesome-solid-download:](https://github.com/esperknight/CriPakTools/tree/master/Build){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/esperknight/CriPakTools/){ .md-button target="_blank"}

## Aqua Model Tool

Aqua Model Toolは、主にファンタシースターオンライン２向けに作成されたツールですが、ファンタシースターノヴァでも限定的ながら、.axs形式のモデルと.aif形式のテスクチャで使用することができます。.aai形式のファイルのアニメーションは、前述の２つと同様の形式であり、部分的に実装されていますが、キーフレームの形式に違いがあるため変換はできません。

[Download :fontawesome-solid-download:](https://github.com/esperknight/CriPakTools/tree/master/Build){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/esperknight/CriPakTools/){ .md-button target="_blank"}

## Sonic Audio Tools

Criwareで使用されているオーディオ向けのアンパック及び再割り当てツールです。PSO2では、殆どの音声データは.acb形式になっています。そこで、このツールキットのACBEditorを使用することで処理することができます。また、必要に応じてACBFinderを使用することで、acbファイルとペアになっているawbファイルを探し出すことができます。

[Download :fontawesome-solid-download:](https://github.com/blueskythlikesclouds/SonicAudioTools/releases){ .md-button .md-button--primary target="_blank"}
[GitHub Repository :fontawesome-brands-github:](https://github.com/blueskythlikesclouds/SonicAudioTools){ .md-button target="_blank"}

## Google Sheets (No seriously)

Interestingly, rather than storing them in binary files, much of the metadata that was copied from PSO2 is stored in Unicode .csv spreadsheets. As this format is primarily text, a text editor such as [Notepad++](https://notepad-plus-plus.org/downloads/) may also be desirable, though harder to parse and compare entries with. Microsoft Excel can also handle these, but note that you will have to import the file as Unicode if you don't wish Japanese text to be garbled.

[Google Sheets link](https://docs.google.com/spreadsheets/u/0/?tgif=d)

## unluac

unlurcはLua 5.xのデコンパイラです。ファンタシースターオンライン２及びファンタシースターノヴァでは、大量の.luaを使用しておりうまく動くはずです。独自のフォルダーとその下のすべてのフォルダーにあるすべての .lua ファイルを逆コンパイルする .bat の例はここにありますが、PC の Java インストール ディレクトリを参照するように編集する必要があります。 [decompall.bat](../../../assets/common/decompall.bat)

[Download :fontawesome-solid-download:](https://sourceforge.net/projects/unluac/){ .md-button .md-button--primary target="_blank"}
[Source Forge Repo](http://hg.code.sf.net/p/unluac/hgcode/branches){ .md-button target="_blank"}
