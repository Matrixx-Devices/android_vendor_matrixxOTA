⚠️ Pixel 6 series ⚠️
1. Reboot to bootloader
2. Get ready to flash using these commands
fastboot flash boot boot.img
fastboot flash dtbo dtbo.img
fastboot flash vendor_boot vendor_boot.img
fastboot reboot recovery

3. While in recovery, navigate to Factory reset -> Format data/factory reset and confirm to format the device.(clean flash only)
4. When done formatting, go back to the main menu and then navigate to Apply update -> Apply from ADB
5. adb sideload rom.zip (replace "rom" with actual filename)
6 (optional). Reboot to recovery (fully) to sideload any add-ons (e.g magisk)
7. Reboot to system
