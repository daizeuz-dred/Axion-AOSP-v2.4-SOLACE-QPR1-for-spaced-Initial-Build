## Overview
This is the second unofficial test build of Axion AOSP v2.4-SOLACE for the Realme Spaced. This release marks a significant milestone in device bring-up, with core hardware components now operational.

## What's Working
- ✅ **System Boot:** Successfully boots to home screen.
- ✅ **Display:** Full graphics acceleration active.
- ✅ **Camera:** Hardware initialized and operational.
- ✅ **GPU:** Mali GLES drivers functioning.

## ⚠️ Installation Instructions (Clean Flash Required)
To ensure system stability and avoid library conflicts, a **clean flash is mandatory** for this build.

1. **Reboot** to your preferred custom recovery.
2. **Flash the ROM:** Sideload or install the `axion-2.4-SOLACE-20260203-UNOFFICIAL-GMS-spaced.zip`.
3. **Format Data:** You must navigate to `Wipe` > `Format Data` and type `yes`. 
   * *Note: This will erase all internal storage. Back up your files!*
4. **Reboot to System.**

## Known Issues & Notes
- **Performance:** Minor UI stutters may occur during 4K recording due to ongoing `libperfmgr` permission tuning.
- **Initial Setup:** The first boot may take 2-5 minutes as the system initializes.
- **Reporting:** Please provide a full logcat if you encounter crashes.

---
**Build Type:** Unofficial Initial Build
**Android Version:** 16 - QPR1
**Security Patch:** February 3,2026
