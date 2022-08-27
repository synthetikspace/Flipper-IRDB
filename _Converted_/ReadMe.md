# Flipper-IRDB  

A **maintained** collective of different IR filess for the Flipper!<br>
_(Maintainers/Major contributors include: [Lucaslhm](https://github.com/Lucaslhm), [UberGuidoZ](https://github.com/UberGuidoZ), [DedHedZed](https://github.com/dedhedzed), [ezod](https://github.com/ezod), [E_Surge](https://github.com/ESurge), [Zecred](https://github.com/bussardrobbie), [SkeletonMan](https://github.com/SkeletonMan03/), [jaroslavmraz](https://github.com/jaroslavmraz), and many others)_

## Organization  

The files within the "Converted" section are only organized by manufacturer name, separated out into 0-9 and A-Z categories for ease of browsing.

## To Install New Remotes On Your Flipper:   

1. Git clone this repo to your local PC. [Multiple options are explained here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).
2. Open the cloned repository in a File Explorer.
3. Connect your Flipper to your PC using a USB-C cable.
4. Open [QFlipper](https://flipperzero.one/update)
5. Verify that your Flipper shows "Connected"
6. Ensure your Flipper is fully up-to-date:
    1. Look for the green "Update" button near the middle-right of the application.
    2. Press "Update" and allow the Flipper to complete the Update process and then reboot before continuing.
7. Open the File Manager by selecting the "File Manager" icon (piece of paper) on the top left of the QFlipper application.
8. Select `SD Card`, then navigate to the `infrared` folder by double-clicking its icon.
9. Drag the .ir files you want on your Flipper from the File Explorer into the QFlipper File Manager.
10. Disconnect the Flipper from the PC and have fun!

NOTE: If you plan to copy them all, it's highly recommended to [dismount the SD card](https://docs.flipperzero.one/basics/sd-card#g4-removing-the-sd-card) and plug it into the computer directly.

## To Install power_all Remote On Your Flipper:  

1. Backup your current `tv.ir` asset from `/SD Card/infrared/assets/tv.ir` in [QFlipper](https://flipperzero.one/update) (Right Click `tv.ir` and click `Download..` 
2. Rename `power_all.ir` to `tv.ir`
3. Drag and Drop in [QFlipper](https://flipperzero.one/update) the new `tv.ir` inside the `/SD Card/infrared/assets` folder
4. Then open "Universal TV Remote" on your Flipper and press "POWER" button.

**NOTES:**
USE THIS WITH CAUTION!! This has the power functions for MULTIPLE DEVICES

This is a BIG file with around 26,000 lines so this will take a while to run.

Pressing anything other than the Power button will probably give you an error. (CH+/-, MUTE, VOL+/- WILL NOT WORK WITH power_all.ir!)
