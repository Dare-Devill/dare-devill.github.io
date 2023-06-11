---
title: "How To Unlock Bootloader Oneplus 8"
date: 2023-06-07T12:05:45+05:30
tags: ["tech",android"]
author: "Pratham Mishra"
tele_username: "Pratham_vai"
draft: false
toc : true
---
# How To Unlock Bootloader Oneplus 8

## What You Need

 - [Fastboot & ADB Drivers](https://wiki.lineageos.org/adb_fastboot_guide)

To unlock the bootloader of your OnePlus 8, you need to follow the official procedure provided by OnePlus. Here are the general steps to unlock the bootloader:

1. Backup your data: Unlocking the bootloader will erase all data on your device, so it's crucial to back up any important files or data before proceeding.

2. Enable Developer Options: Go to Settings > About Phone and tap on the "Build number" seven times to unlock Developer Options.

3. Enable USB Debugging: In Developer Options, enable USB Debugging. This allows your device to communicate with your computer during the bootloader unlocking process.

4. Enable OEM Unlocking: In Developer Options, enable the "OEM unlocking" option. This step may be optional on some OnePlus devices.

5. Power off your device: Completely power off your OnePlus 8.

6. Boot into Fastboot Mode: Press and hold the Power button and Volume Up button simultaneously until the OnePlus logo appears. Release the buttons to enter Fastboot Mode.

7. Connect your device to your computer: Use a USB cable to connect your OnePlus 8 to your computer.

8. Install ADB and Fastboot: Download the Android SDK Platform Tools, which include ADB (Android Debug Bridge) and Fastboot. You can find the SDK Platform Tools on the Android Developers website or use a third-party source. Extract the downloaded file to a convenient location on your computer.

9. Open a Command Prompt or Terminal: Navigate to the location where you extracted the SDK Platform Tools. Open a Command Prompt (Windows) or Terminal (macOS/Linux) in that directory.

10. Verify device connectivity: In the Command Prompt or Terminal, enter the following command to verify that your device is properly connected:
```
fastboot devices
```
If your device is detected, you should see a device ID along with the "fastboot" message.

11. Unlock the bootloader: In the Command Prompt or Terminal, enter the following command to initiate the bootloader unlocking process:
```
fastboot oem unlock
```
This command will initiate the bootloader unlocking process on your OnePlus 8. A confirmation message will appear on your device's screen. Use the Volume buttons to highlight "Unlock the bootloader," and press the Power button to confirm. This step will wipe all data on your device.

12. Wait for the process to complete: The bootloader unlocking process may take a few minutes. Once it's finished, your device will reboot automatically.

After completing these steps, your OnePlus 8's bootloader should be successfully unlocked. You can then proceed with installing custom recoveries, custom ROMs, or other modifications on your device.

