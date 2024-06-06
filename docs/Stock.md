---
hide:
  - navigation
---
#**Flashing Stock Rom**
MIUI Official Fastboot ROM Flashing Method by
[@ChrisCatto](https://t.me/ChrisCatto)

**THIS GUIDE APPLIES ONLY ON OFFICIAL MIUI ROMS. NOT IN CUSTOM ROMS LIKE OPMOD,PAPER OS**

## Requirements:

• A PC/Laptop

• A USB cable

• Unlocked Bootloader

Getting the Fastboot Rom:

Get the latest fastboot ROM from the group by typing /fastboot xaga or from [here](https://xmfirmwareupdater.com/hyperos/xaga/) but make sure you're downloading a fastboot rom and not recovery.

!!! warning
    ROM must be extracted in C Drive without any subsequent sub folders.

## Installing Mi Flash Tool:

1. Download and unzip Mi Flash Tool, latest version from [here](https://xiaomiflashtool.com/)

2. Run Mi Flash Tool.

!!! warning
    If it shows this error then just make a log folder in the unzipped directory

![error ](https://xiaomi.eu/community/attachments/miflash-install-message-1-png.48046/)

## Flashing Process:

1. Reboot phone in fastboot mode by pressing power button and volume down button. 

2. Once phone is in fastboot mode, connect phone to PC / Laptop.

3. On the bottom right corner of Mi Flash Tool, there are 3 bullet marks. Each of them means the following:

***
=>**Clean all and lock - This will flash stock ROM, wipe data and relock bootloader.** 

=>**Clean all - This will wipe user data and flash stock ROM. This will not relock bootloader.** 

=>**Save User Data - This will flash stock ROM and keep existing user data. But will only work if ROM version is same as the one already flashed on your device.**

***

4. On the top left corner, click select, go to the extracted fastboot firmware folder, and click OK. 

5. Click refresh and your device should be detected. If it doesn't try installing drivers for your device on the driver section on top left.

6. Start flashing by tapping flash. The flashing process could take around 300-600 seconds. There have been times where it took longer but it should be fine as long as the device boots into system. If you choose to not lock the bootloader an error will pop up when flashing is done, just ignore. If you get a timeout error, install the 20181115 version of Mi Flash Tool.

If nothing happens, seek help from the group. 
[Telegram Group](https://t.me/XAGASupport)


**Report content on this page**