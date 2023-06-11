---
title: "How To Install Custom Rom In Oneplus 8"
date: 2023-06-08T23:50:35+05:30
draft: false
tags: ["tech","android"]
author: "Pratham Mishra"
tele_username: "Pratham_vai"
toc : true
---

# How To Install Custom Rom In Oneplus 8

## What You Need

 - [Fastboot & ADB Drivers](https://wiki.lineageos.org/adb_fastboot_guide)
 - [Unlocked Bootloader](/post/unlock-bootloader-oneplus8)
 - [Custom Rom and Custom Recovery](https://forum.xda-developers.com/f/oneplus-8-roms-kernels-recoveries-other-devel.10357/)



Installing a custom ROM on your OnePlus 8 involves several steps. Please note that the process may void your warranty and has the potential to damage your device if not done correctly. Make sure to back up your data before proceeding. Here's a general guide to installing a custom ROM on your OnePlus 8:

Note: Before starting, ensure that your OnePlus 8 is unlocked and you have TWRP (Team Win Recovery Project) custom recovery installed. Additionally, download the custom ROM and the corresponding GApps (Google Apps package) for your device from a trusted source.

1. Enable Developer Options: Go to Settings > About Phone and tap on the "Build number" seven times to unlock Developer Options.

2. Enable USB Debugging: In Developer Options, enable USB Debugging. This allows your device to communicate with your computer during the installation process.

3. Unlock the Bootloader: OnePlus devices require an unlocked bootloader to install custom ROMs. Visit the OnePlus website (oneplus.com) and follow their instructions to unlock the bootloader. Keep in mind that this process will wipe all data on your device.

4. Install TWRP Recovery: After unlocking the bootloader, download the TWRP image file for your OnePlus 8 from the official TWRP website (twrp.me/OnePlus/OnePlus8.html). Boot your device into fastboot mode by powering it off and then holding the Power button and Volume Up button simultaneously. Connect your device to your computer, open a command prompt or terminal window, and execute the following command:
```
fastboot flash recovery <twrp_image_filename.img>
```
Replace "<twrp_image_filename.img>" with the actual filename of the TWRP image file you downloaded. Once the process is complete, type "fastboot reboot" to reboot your device.

5. Backup your data: Boot your device into TWRP recovery mode by holding the Power button and Volume Down button simultaneously while the device is powered off. In TWRP, select "Backup" and choose the partitions you want to back up (recommended: Boot, System, Data). Swipe to confirm the backup process and wait for it to complete.

6. Wipe Data: In TWRP, select "Wipe" and then "Advanced Wipe." Check the boxes for Dalvik/ART Cache, System, Data, and Cache. Swipe to confirm the wiping process.

7. Install the Custom ROM: In TWRP, select "Install" and navigate to the location where you saved the custom ROM file. Select the ROM file and swipe to confirm the installation. Wait for the process to complete.

8. Install GApps: In TWRP, select "Install" again and navigate to the location where you saved the GApps package. Select the package and swipe to confirm the installation.

9. Reboot: Once the installation is complete, go back to the main menu in TWRP and select "Reboot" > "System." Your device will boot into the newly installed custom ROM.

Please note that the exact steps and options may vary slightly depending on the specific custom ROM and version of TWRP you are using. It's essential to follow the instructions provided by the custom ROM developer and ensure compatibility with your OnePlus 8 model.

Remember to do thorough research and proceed with caution when installing custom ROMs, as any mistakes can lead to potential issues with your device.




