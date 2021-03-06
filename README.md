# creaTive Deathmatch client source code by barney
Please note that most of the code in this repository is NOT original and is developed mostly by https://github.com/YaLTeR. I have included the original OpenAG readme. This repo contains all source code necasarry for editing and building the creaTive Deathmatch client DLL, required for the creaTive Deathmatch Player.
I will add more detailed notes on building soon.

# Cloning
It is NOT reccomended that you clone this repo from this website if you plan on editing the code. Use Git Bash and cd to where you want to clone the repo, and then type
 "git clone http://www.github.com/classictourneys/creativedeathmatch" without the quotation marks.
 
 ## Navigating the repo
 The root of this repo is the original OpenAG repo. The modified creaTive Deathmatch version (which includes the VS2017 solutions) is in the build folder.
 
 # WARNING: THE SOURCE CODE ON HERE ISN'T COMPLETED YET. I WILL COMPLETE IT OVER THE WEEKEND.

# OpenAG
======================
[![Build Status](https://travis-ci.org/YaLTeR/OpenAG.svg?branch=master)](https://travis-ci.org/YaLTeR/OpenAG)
[![Build Status](https://ci.appveyor.com/api/projects/status/o758yugwuavrt9qi?svg=true)](https://ci.appveyor.com/project/YaLTeR/openag)
[![Chat on Discord](https://discordapp.com/api/guilds/252168904359542784/widget.png)](https://discord.gg/jCYhYNH)

OpenAG is an open-source client of the Half-Life promod Adrenaline Gamer, completely rewritten from scratch on latest Half-Life SDK. It adds new features, bugfixes and other tweaks over the original mod, while maintaining the ability to play on all currently existing servers.

# Building
## Windows
1. Get Visual Studio 2017 and CMake.
2. `git submodule update --init`
3. `mkdir build`
4. `cd build`
5. `cmake ..`
6. `cmake --build . --config Release`

## macOS
1. Install Xcode.
2. Install CMake via Homebrew.
3. `git submodule update --init`
4. `mkdir build`
5. `cd build`
6. `cmake ..`
7. `cmake --build . --config Release`

## Linux
1. Get a 32-bit/multilib **gcc** (6 and above) or **clang** (3.9 and above) build environment set up, as well as CMake.
2. `git submodule update --init`
3. `mkdir build`
4. `cd build`
5. `cmake ..`
6. `cmake --build . --config Release`

Half Life 1 SDK LICENSE
======================

Half Life 1 SDK Copyright© Valve Corp.  

THIS DOCUMENT DESCRIBES A CONTRACT BETWEEN YOU AND VALVE CORPORATION (“Valve”).  PLEASE READ IT BEFORE DOWNLOADING OR USING THE HALF LIFE 1 SDK (“SDK”). BY DOWNLOADING AND/OR USING THE SOURCE ENGINE SDK YOU ACCEPT THIS LICENSE. IF YOU DO NOT AGREE TO THE TERMS OF THIS LICENSE PLEASE DON’T DOWNLOAD OR USE THE SDK.

You may, free of charge, download and use the SDK to develop a modified Valve game running on the Half-Life engine.  You may distribute your modified Valve game in source and object code form, but only for free. Terms of use for Valve games are found in the Steam Subscriber Agreement located here: http://store.steampowered.com/subscriber_agreement/ 

You may copy, modify, and distribute the SDK and any modifications you make to the SDK in source and object code form, but only for free.  Any distribution of this SDK must include this license.txt and third_party_licenses.txt.  
 
Any distribution of the SDK or a substantial portion of the SDK must include the above copyright notice and the following: 

DISCLAIMER OF WARRANTIES.  THE SOURCE SDK AND ANY OTHER MATERIAL DOWNLOADED BY LICENSEE IS PROVIDED “AS IS”.  VALVE AND ITS SUPPLIERS DISCLAIM ALL WARRANTIES WITH RESPECT TO THE SDK, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, IMPLIED WARRANTIES OF MERCHANTABILITY, NON-INFRINGEMENT, TITLE AND FITNESS FOR A PARTICULAR PURPOSE.  

LIMITATION OF LIABILITY.  IN NO EVENT SHALL VALVE OR ITS SUPPLIERS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF BUSINESS PROFITS, BUSINESS INTERRUPTION, LOSS OF BUSINESS INFORMATION, OR ANY OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR INABILITY TO USE THE ENGINE AND/OR THE SDK, EVEN IF VALVE HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  
 
 
If you would like to use the SDK for a commercial purpose, please contact Valve at sourceengine@valvesoftware.com.


Half-Life 1
======================

This is the README for the Half-Life 1 engine and its associated games.

Please use this repository to report bugs and feature requests for Half-Life 1 related products.

Reporting Issues
----------------

If you encounter an issue while using Half-Life 1 games, first search the [issue list](https://github.com/ValveSoftware/halflife/issues) to see if it has already been reported. Include closed issues in your search.

If it has not been reported, create a new issue with at least the following information:

- a short, descriptive title;
- a detailed description of the issue, including any output from the command line;
- steps for reproducing the issue;
- your system information.\*; and
- the `version` output from the in‐game console.

Please place logs either in a code block (press `M` in your browser for a GFM cheat sheet) or a [gist](https://gist.github.com).

\* The preferred and easiest way to get this information is from Steam's Hardware Information viewer from the menu (`Help -> System Information`). Once your information appears: right-click within the dialog, choose `Select All`, right-click again, and then choose `Copy`. Paste this information into your report, preferably in a code block.

Conduct
-------


There are basic rules of conduct that should be followed at all times by everyone participating in the discussions.  While this is generally a relaxed environment, please remember the following:

- Do not insult, harass, or demean anyone.
- Do not intentionally multi-post an issue.
- Do not use ALL CAPS when creating an issue report.
- Do not repeatedly update an open issue remarking that the issue persists.

Remember: Just because the issue you reported was reported here does not mean that it is an issue with Half-Life.  As well, should your issue not be resolved immediately, it does not mean that a resolution is not being researched or tested.  Patience is always appreciated.
