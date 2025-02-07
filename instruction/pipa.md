![Installation Guide For Project Matrixx](https://github.com/ProjectMatrixx/android/raw/refs/heads/15.0/Banner.png)
### Installation Guide For Project Matrixx on Xiaomi Pad 6 - pipa
 
# Clean flash
• If you already have aosp recovery installed, u can skip the next step, or keep following
• Download boot (https://surl.li/puxwrs) and vendor_boot (https://surl.li/vtooxn) [only if u dont have aosp recovery installed]
• Now connect tab to PC, boot to fastboot mode, open cmd, type fastboot flash boot boot.img & fastboot flash vendor_boot vendor_boot.img 
• Now reboot to matrixx aosp recovery
• Format all partition and data through recovery 
• Then go to install & adb sideload
• Run adb sideload rom.zip
• If need gapps, flash bitgapps core via sideload, also addons if needed
• Finally reboot to system!

# Dirty flash
• You should receive OTA when new build is released it will auto update everything
• If not, just sideload the new rom zip and reboot [dont wipe or format anything except cache]
