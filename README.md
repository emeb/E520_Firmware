# E520_Firmware
Firmware for the Synthesis Technology E520 Hyperion Stereo Effects Processor

## What is this?
This is firmware version 1.3b for the E520. The final published firmware version
on the Synthesis Technology website is version 1.3a, released in August 2023.
Since then a minor issue was reported with the Wet/Dry mix control which is
addressed by this late release in March 2025.

Find out more detail about the E520 at the
[Synthesis Technology website](https://synthtech.com/eurorack/E520/).

## Installation
0. Download the file [e520_fmw.bin](./e520_fmw.bin) <-- by clicking this link.
1. Copy the firmware file “e520_fmw.bin” onto a FAT32 formatted SD card of 32GB
or less.
2. Turn on the E520 and insert the SD card into your E520’s Micro SD card slot.
3. Navigate to the TOP→FILE→SYS SAVE menu page and save your current settings.
4. While holding in the encoder button, cycle power on the E520. When you see
the blue bootloader screen. If your firmware file was properly copied to the
SD card then you will be given the choice to install it.
5. Select “Yes” to begin installation.  This will take some time but you will
see progress information.
6. After flashing completes push the encoder button to restart the system.
There may be a wait of up to a minute with a black screen while the E520 resets
its EEPROM, but it should eventually start up normally with a splash screen that
then proceeds to the main screen.
7. Navigate to the TOP→FILE→SYS LOAD menu page and select the file you saved in
step 2 above. Answer “Y” to confirm you want to load the saved settings.
8. The E520 will provide a progress bar and status text telling you that it’s
converting. When it finishes you can navigate back to the Main menu and use it
normally.
