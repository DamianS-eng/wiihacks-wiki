---
title: Wiki -> cIOS Tutorial
redirect_from: "/tutorials/cIOS.md"
---

# cIOS

cIOS stands for "custom IOS". Custom IOS is a third-party IOS file installed on the Wii's internal memory. The IOS is the operating system on which the Wii's Starlet coprocessor runs. 
cIOS is also referred to as a "patched IOS". 
It is created using a base IOS already existing on the console and then modified with extra features, 
such as USB2 support and access permissions, to install to a different unused slot. Officially, the Wii updates its operating system with a different IOS slot,
either downloaded from Nintendo's *(now defunct)* update servers or from newer Wii game discs.

cIOS is required to load games with a USB loader, and it can allow users to launch and run homebrew apps better than using the Wii's default IOS.
This method can work on both the Wii and the Wii U's vWii.

For more information on cIOS, you can read about it on the [WiiBrew Wiki](https://wiibrew.org/wiki/cIOS) or the [Wii Guide](https://wii.guide/cios.html).

## Installation

This installation uses d2x cIOS Installer on a Wii with the Homebrew Channel. You can use ModMii to prepare the SD card with the installer or download the installer directly from [code.google.com](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/d2x-cios-installer/d2x%20cIOS%20Installer%20v3.1.zip).

The following tutorial will configure the Wii wiith cIOS on slot 249 base 56, slot 250 base 57, and slot 251 base 58.

1. Download the d2x cIOS Installer using ModMii or from [the Google backup site](https://sites.google.com/site/completesg/backup-launchers/installation/d2x-cIOS-Installer-Wii.zip?attredirects=0&d=1).
2. Place the downloaded folder in the apps folder on your SD card or USB drive. Ensure the folder contains three files:
  * icon.png
  * meta.xml
  * The app's .dol loader file
3. If you plan to launch the installer from a USB storage device, insert it into the bottom USB port of the Wii before booting to the Homebrew Channel to find the app in the Homebrew Channel list.
4. Set the options to the following, then press A on the Wii Remote or Gamecube Controller to install:
> Select cIOS: v10 beta52 d2x-v10-beta52 \
Select cIOS base: 56 \
Select cIOS slot: 249 \
Select cIOS version: 65535
5. When completed, press A to return, set the options to the following, then press A to install:
> Select cIOS: v10 beta52 d2x-v10-beta52 \
Select cIOS base: 57 \
Select cIOS slot: 250 \
Select cIOS version: 65535
6. When completed, once more return and then set the options to the following, then press A to install:
> Select cIOS: v10 beta52 d2x-v10-beta52 \
Select cIOS base: 58 \
Select cIOS slot: 251 \
Select cIOS version: 65535

## USB Loader GX

After installing the cIOS on the three slots, you can now use a USB loader application usch as USB Loader GX or WiiFlow. 
