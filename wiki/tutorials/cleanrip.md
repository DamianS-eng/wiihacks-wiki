---
title: Wiki -> CleanRip Tutorial
redirect_from: "/tutorials/cleanrip.md"
---

# CleanRip

CleanRip is a Wii and Gamecube homebrew tool to create 1:1 backups of your Gamecube and Wii games on Wii and WiiU vWii.

For more information on CleanRip, you can read about it on the [WiiBrew Wiki](https://wiibrew.org/wiki/CleanRip) or their [GitHub page](https://github.com/emukidid/cleanrip).

## Installation

The WiiBrew Wiki should contain a zipped folder with all the required components to run the app in the Homebrew Channel. However, follow these directions to make sure the installation is intact:

1. Download [loader.dol](https://github.com/emukidid/cleanrip/releases) and, on your Wii SD card, put it in the `apps/CleanRip` folder as boot.dol.
1. Download the [meta.xml](https://github.com/emukidid/cleanrip/releases) file, and put that in `apps/CleanRip` as well.
1. Finally download and put the [icon.png](https://github.com/emukidid/cleanrip/releases) file in to `apps/CleanRip`.
1. Optionally, in the event that the DAT files fail to download during the rip, manually download the latest version of the "Datfiles, Cuesheets, and GDIs compilation" from [redump.org](http://redump.org/datfile/all/) or [GC Forever](https://gc-forever.com). Rename the files to wii.dat and gc.dat, and place them on the root of the SD card.
1. If you plan to rip the content to a USB storage device, insert it into the bottom USB port of the Wii before booting to the Homebrew Channel to launch the app.

*Note:* This app can run on the Gamecube and Wii, and is considered the old method to make Gamecube game rips.

## Ripping your Gamecube Games

In order to rip Gamecube games, your storage device (SD card or USB) must have at least 1.35GB free space.
- Start the app.
- Choose the storage medium you would like to send the rip, then insert your Gamecube disc. The process should start automatically.

## Ripping your Wii Games

In order to rip Wii games, your storage device (SD card or USB) must have at least 4.7GB free space.
- Start the app.
- Choose the storage medium you would like to send the rip, then insert your Wii disc.
- After the disc is read, there should be several options to toggle beore the rip. 
  - If the game is Dual-Layer (ie. Super Smash Bros. Brawl), toggle this on.
  - Choose to split the rip into parts or choose Max Chunk Size to export it as one file.
- The process should then run, approximate wait time is 10-15 minutes.

*Note*: NTFS was broken on versions 1.0.2 and 1.0.3 - but was fixed in 1.0.4. Make sure the CleanRip version you are using is 1.04 or later.

## Gamecube Image Directory Structure
Your Gamecube games need to be on either your FAT32 formatted SD card or a FAT32 formatted USB storage device.

Your Wii games can be placed on a NTFS formatted storage drive.

It is possible to split partitions on one external USB hard drive, one partition for Gamecube games at FAT32, the other for Wii games as NTFS. CleanRip will automatically export to the proper partition.
