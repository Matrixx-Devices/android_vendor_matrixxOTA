# **Flashing Guide for 8/8T (Dynamic Partitions ROM)**

## **Recovery Requirement**
- Recommended Recovery: **TWRP**  
  - [Download TWRP](https://sourceforge.net/projects/kycii91-j4plus/files/Ginkgo/Recovery/TWRP-Unified-Ginkgo.img/download)

## **Important Notes**
- **Do not switch to any other kernel.**
- **Clean Flash Required If:**
  - Coming from a different ROM or MIUI.
  - Upgrading from a previous Android version.
  - Moving from a Non-Retrofit Dynamic ROM.
- **Clean flash involves formatting data**, which means all internal storage data will be lost. SD Card data should remain unaffected. Back up important files beforehand.
- **Dirty Flash / Update**: No data should be lost, but backups are strongly recommended.

---

## **Flashing Instructions**

### **Preparation**
1. **Wipe Partitions:**
   - System
   - Vendor
   - Data
   - Dalvik Cache
   - Cache
   - Metadata

2. **Install Recovery:**
   - **Choose one:**
     - [TWRP Unified](https://sourceforge.net/projects/kycii91-j4plus/files/Ginkgo/Recovery/TWRP-Unified-Ginkgo.img/download)
     - [OrangeFox r12.1 Dynamic](https://t.me/BreakdownsCloud/668) **(For Vanilla builds only)**
   - **Reboot to Recovery**

3. **Recovery Settings:**
   - Open **Settings** in Recovery.
   - **Untick** "Unmount System before installing a ZIP".

---

### **Flashing Process**
1. **Flash** [Retrofit Dynamic Partition Converter](https://sourceforge.net/projects/kycii91-j4plus/files/Ginkgo/Ginkgo_Retrofit_Dynamic_Partitions_Converter.zip/download).
2. **Flash Firmware:**
   - **Ginkgo:** [Download](https://t.me/BreakdownsCloud/529)
   - **Willow:** [Download](https://t.me/BreakdownsCloud/679)
3. **Flash ROM.**
4. **(If Vanilla ROM)** Flash **GApps** from [Here](https://sourceforge.net/projects/nikgapps/files/Releases/Android-15/04-Nov-2024/NikGapps-core-arm64-15-20241104-signed.zip/download).
   - **NOTE:** If you encounter errors while flashing, **reboot to Recovery and flash GApps again**.
5. **Format Data.**
6. **Reboot System** (Ignore the "No OS Installed" warning).

---
