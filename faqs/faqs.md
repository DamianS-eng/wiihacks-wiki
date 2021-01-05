---
title: Wiki -> F.A.Q.s
description: A wiki maintained by the r/WiiHacks community.
redirect_from: "/faqs/faqs.md"
---

## Regarding the subreddit.

### My post keeps getting flagged for Rule #4, why?

  There are two types of posts that get flagged for Rule #4. Help requests or questions that are regularly asked are removed, as well as ones that ask vague questions and/or provide vague information.

  People are less likely to respond to a help request if the first thing they need to do is ask you to provide the proper information.

### How can I get my post to not get removed by Rule #4?

  Always research the issue in the forum before you post. 98% of all questions asked are asked and answered regularly. If your post was removed because of this, you really didn't need to post to begin with.

  Provide enough information for the person to troubleshoot your issue;

  * Your post should have a title that briefly, but accurately describes the issue.
  
  * In the body, included should be a full description of the issue.
  
  * Include your hardware setup. What Wii are you using? The model and size of SD and USB device is often relevant, include it too. Do you have an original Wiimote, or a motion plus?
  
  * Include your software setup. A syscheck is almost always helpful. Paste the results into a pastebin and include it in your body. Like [this](https://pastebin.com/agpxtvXz).
  
  * Include everything you've done up until that point including links to tutorials you've followed and try to describe the results as best as you can.
  
  * The more information you provide, the less chance of the post getting removed as well as the more chance you have of getting someone to help you resolve your issue.

----

## Modding the Wii.

### My games aren't (showing up or loading) in USB Loader GX? Black Screen, Blank List, etc

  * The staff team has compiled a list of 6 reasons why your USB/SD loader isn't working.

  * Wrong USB port. The only USB port that can run game backups is the one on the edge of the Wii, unless you are using d2x beta53-alt cIOS, which is not recommended as it is not as compatible.

  * cIOS is not set up correctly (follow https://wii.guide/cios). We can only confirm it is done right with a syscheck (follow https://wii.guide/syscheck). Keep in mind that some games that use accessories will require a different IOS to run.

  * Image is bad/corrupted. Testable in Dolphin Emulator. Make sure it's wbfs or iso (not nkit) if you're trying to play a Wii game.

  * Use the latest version of your loader, use default settings and name the games as such for Wii games> USB:/wbfs/GameName [GameID]/GameID.wbfs

  * USB isn't compatible. That is most likely to happen with flash drives. HDDs are always the best way to store games on the Wii.

  * Don't use a forwarder. Launch the app directly from the Homebrew Channel.

### How do I mod my Wii?

  * [wii.guide](https://wii.guide/)

  * This is the current approved guide for modding your Wii.

  * Please read and perform every step. Do not skip steps.

  * Do not delete any folders/files that will be generated during the mod process or after.


### What extra hardware do I need?

  * An SD Card, an SD Card Reader, and some form of USB Storage, if you want to minimize risk, a hard drive that isn't powered by the USB.


### Can I do it without an SD Card and or USB Hard Drive/Memory Stick?

  * You can mod your Wii without an SD card. Eventually you will need some form of storage to store your homebrew applications, and your games, whether they be Wii, GameCube, or emulator roms.

### What size should my SD Card be?

  * Anything from 512mb (yeah, I still have one) to 32gb and above have been known to work just fine. You want to make sure it's large enough to accommodate everything you want to put on it, which you can easily figure out by gathering it all together and prepping it on your computer.

### How about the size of my USB storage?

  * Wii games can range from larger than the size of a single DVD and down. If you're a casual player and only have a few games, 100GB would do just fine. However the larger/newer the drives get, the more incompatibilities you might experience.

### How do I know the current mod state of my Wii?

  * Currently [SysCheck](http://www.wii.guide/syscheck) is recommended. Though be warned, there are certain kit-installers that can change your IOSes without changing the version number, thereby preventing your Wii from being modified. 

### Can I Un-MOD my Wii? Will formatting it remove the mods?

  * Sure. However first warning; you're looking at a procedure far more complex than what you did to mod your Wii.

  * Formatting the Wii will only remove user data. Removing/deleting the SD Card or USB Device will remove all homebrew and games.

  * If you can; updating the Wii might remove *most* of the modified software. Been wanting to make that jump from 4.1 to 4.3? Now's your chance. Just fair warning, this has the potential to brick your Wii.

  * If you were lucky enough to not be able to use an upgrade, you'll want to download all of the stock IOS and replace all of the modified ones with originals. Of course you'll still need your homebrew to do this with... The suggested tool would be the NUS Downloader.

  * Seriously, there's no good reason to un-mod a Wii. You probably won't get more thorough help than this in doing so because no one does. However if you insist, please direct your questions toward GBATemp, as these posts never go anywhere in r/WiiHacks.

### I want to change a different SD Card / USB Device, can I just copy everything over?

  * Yes. You can use normal filecopy operations of your OS to move files from one location to the other, with no issue.
  
  * If you're moving to an SD Card remember that USB Loader GX will have to be replaced with something that will play Wii games off a SD Card.

### Ripping games using USB Loader GX isn't working.

  * USB Loader GX has a habit of stopping in the middle of a rip and never completing, if it works at all.

  * After this issue appearing in the subreddit numerous time, the general public consensus is to not use it to rip games. It doesn't do it reliably, or accurately.
  
  * Use [CleanRip](https://wii.guide/cleanrip) instead. It's more recently maintained and works much better.

### Homebrew Browser

  * If you're going to use it, please make sure you're using the newer repository, [OSC, which can be found here](https://oscwii.org).
  
  * Here at r/WiiHacks, we recommend that you install the software yourself as software like this doesn't have a track record for reliability, and eventually you'll probably want to know how to install it yourself.

  * Lastly, if you do choose to use either, please take your issue(s) to the RC24 discord, or their recommended support path, as we will not provide support for it at r/WiiHacks due to the fact that we don't recommend it and it causes disruptive discussions in submissions that ask for help with it.

### How do I manage my virtual Wii game library?

  * One of our moderators has made a guide to organasing your games without a special programme

  * The first step is making a "wbfs" folder on the root of your USB device if there isn't already one. If there already is one, then you're already one step ahead.

  * Inside the "wbfs" folder will be game folders, once you've made them. For example, inside that "wbfs" folder, Wii Sports would look like this:

  * /USB drive/wbfs/Wii Sports [RSPE01]/RSPE01.wbfs

  * If you're using .iso files instead of .wbfs files, make sure to change them using this tool here. It's a far superior way of storing games on external storage.

  * https://isotowbfs.com/

  * That 6 digit code after the name of the game is called the game ID. You can find them here by searching the game's name and copying that code.

  * https://gametdb.com/

  * After you have the game folder, which is inside the "wbfs" folder, plop your file inside. It must be named like the example above.

  * And congratulations, you just added a Wii game to your USB device manually. You'll get faster the more you do it.

### How do I get WADs and Channel forwarders onto my Wii?

  * [Wii Mod Lite](https://wii.guide/wiimodlite) is a great way to easily install wad files and channel forwarders.

----

## Helping out...

  * If you have any corrections, additions or suggestions, please message the moderators. We'd be glad to hear it.
