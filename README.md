## Twenty is Plenty

-=- [Readme](README.md)
-=- [Gameplay](GAMEPLAY.md)
-=- [Changelog](CHANGELOG.md) -=-

<!-- TOC -->

- [Twenty is Plenty](#twenty-is-plenty)
    - [Preamble](#preamble)
    - [System Requirements](#system-requirements)
    - [Installation](#installation)
        - [Pre-Installation](#pre-installation)
            - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
            - [Installing Microsoft .Net Framework 5.0 Runtime](#installing-microsoft-net-framework-50-runtime)
            - [Steam Config](#steam-config)
                - [Disable the Steam Overlay](#disable-the-steam-overlay)
            - [Set the Game language to English](#set-the-game-language-to-english)
            - [Clean Skyrim](#clean-skyrim)
            - [Start Skyrim](#start-skyrim)
        - [Using Wabbajack](#using-wabbajack)
            - [Preparations](#preparations)
            - [Downloading and Installing](#downloading-and-installing)
                - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Post-Installation](#post-installation)
        - [Game Folder](#game-folder)
        - [ENB](#enb)
    - [The video game has been modified](#the-video-game-has-been-modified)
    - [How to start up Twenty is Plenty](#how-to-start-up-Twenty is Plenty)
    - [Updating](#updating)
    - [Creating your Character](#creating-your-character)
    - [In-Game MCM Options](#in-game-mcm-options)
        - [Optional Survival Config](#optional-survival-config)
    - [Other Post Installation FAQ](#other-post-installation-faq)
        - [Ultrawide Options](#ultrawide-options)
        - [Tweaking the Game Settings](#tweaking-the-game-settings)
        - [Zoomed in Display](#zoomed-in-display)
        - [Removing the Modlist](#removing-the-modlist)
    - [Credits and Thanks](#credits-and-thanks)
    - [Contact](#contact)
    - [Contributing](#contributing)
    - [Changelog](#changelog)

<!-- /TOC -->

## Preamble

Tired of all those 90gb modlists? Think 800 mods is to many? Me too, I think that Twenty is Plenty.

This modlist has a simple goal: Improve Skyrim in as many ways as possible, with only 20 mods*

* not including stability/patch/utility/bugfix mods

THIS MODLIST REQUIRES THE ANNIVERSARY EDITION CONTENT TO FUNCTION

## System Requirements

If you can run vanilla Skyrim on max settings with a stable framerate, you can almost certainly run this.

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Installing Microsoft .Net Framework 5.0 Runtime

This package is required for the mod Scrambled Bugs to work. Without this installed, the game would not launch. Download and install the x64 version under "Run desktop apps" from [Microsoft](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime). [Direct Link](https://download.visualstudio.microsoft.com/download/pr/2bfb80f2-b8f2-44b0-90c1-d3c8c1c8eac8/409dd3d3367feeeda048f4ff34b32e82/windowsdesktop-runtime-5.0.13-win-x64.exe)

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Set the Game language to English

I cannot provide support to people without an English game, so this step is neccessary.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting its contents.
A fully updated Skyrim is required. Do not run the Downgrade Patcher or the list will not install.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will overwrite these graphics settings.
Start the game. Log in to the Creation Club and download all of the Creation Club content.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Programme Files folder. It's best to create a Wabbajack folder near the root level of your drive, e.g. `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack.
2. Click on browse Modlists and select Twenty is Plenty.
3. Set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Programme Files, Desktop. Put it somewhere easy like `C:/Modlists/Twenty is Plenty`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend restarting Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

This could occur from one of the larger mods failing to download. If thats the case, try downloading them manually and placing them in the downloads folder.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Path is a zero length string error**:

This error occurs when you don't specify an installation folder in the installation before hitting run.

## Post-Installation

### Game Folder

The installation will create a copy of your Skyrim Special Edition game in `Installation Folder/Game Root`. This will then contain all the necessary files such as SKSE. There is no need to copy anything to your Steam version of Skyrim as we will be running SKSE from within this folder to play the game.

### ENB

Twenty is Plenty doesn't come with an ENB, or with ENB binaries, you'll have to intall them yourself. Just remember that the game is running out of `Installation Folder/Game Root`, so you'll want to put ENB files there.

Please note that Twenty is Plenty doesn't have any weather or lighting mods, so your choices might be slim.

## The video game has been modified

While there aren't a lot of mods in this list, the game still has some important differences see [Gameplay] (GAMEPLAY.md) for details.

## How to start up Twenty is Plenty

Navigate to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to "Run Twenty is Plenty" by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

### Removing the Modlist

You can just remove the MO2 folder and be done with it.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you

## Contact

**Please do not DM me on Discord, I will not respond.**

## Changelog

See [Changelog](CHANGELOG.md).
