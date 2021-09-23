# BFBBUW (SpongeBob Battle For Bikini Bottom Rehydrated Ultrawide Fix)
[![Build status](https://ci.appveyor.com/api/projects/status/xio5pfprnw7vk7p5?svg=true)](https://ci.appveyor.com/project/KingKrouch/bfbbuw/build/artifacts)

## About
An ASI Loader plugin which allows BFBBR to run on Ultrawide displays, and with even higher framerates.

## Compiling (For programmers)
1. Download and install [Visual Studio 2019](https://visualstudio.microsoft.com/downloads) alongside the [Microsoft .NET Framework 4.6.2 Developer Pack](https://www.microsoft.com/en-us/download/details.aspx?id=53321).
2. Open this repository in [GitHub Desktop](https://desktop.github.com/) (or manually clone with the Git command-line tool) to clone the repo.
3. Open [BFBBUW.sln](BFBBUW.sln) in Visual Studio, make sure the build setting is set to *"Release - Win64"*, then compile.
4. The compiled ASI plugin should be in the plugins folder contained in **"Binaries\Win64"**.

## Setup
Copy the plugins folder and dsound.dll (ASI Loader) into the **"\Pineapple\Binaries\Win64\"** directory of where the game is installed.

*Note: If you don't have any other Steam library locations set up, this will likely be **"C:\Program Files (x86)\Steam\SteamApps\Common\SpongeBob SquarePants Battle for Bikini Bottom - Rehydrated"**.*

## System Requirements
* A *Legitimate* fully updated copy of the game from Steam *(Due to the difference in memory offsets that can result with cracked/pirated versions, the fact that these versions are likely outdated builds, and the fact that I vehemently discourage piracy when there are convenient and accessible options available to support the developers, **I refuse** to provide technical support for these versions. That includes anyone without a mouse cursor icon next to their name on the Steam Discussion Boards).*<br />
[***The game is available for purchase on Steam.***](https://store.steampowered.com/app/969990/)<br />
**WARNING: This mod is incompatible with the GOG or Epic Games Launcher versions, due to different memory offsets!**

* Windows 10 or Windows 11 (Compatibility with Proton on Linux is undetermined). **64-Bit operating system is required.**

* [Microsoft Visual C++ Redistributables for Visual Studio 2019](https://aka.ms/vs/16/release/vc_redist.x64.exe)

## Download (For novices)
[Latest version can be downloaded here.](https://github.com/KingKrouch/BFBBUW/releases)

Download includes the latest version of [Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader).

## Legal Stuff
**BFBBUW (C) 2020 Bryce Q.**

**BFBBUW is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.**

**BFBBUW is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. [See the GNU General Public License for more details.](https://gitlab.com/KingKrouch/BFBBUW/-/blob/master/LICENSE)**
