<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/16ebe19a-8b6c-470d-9ead-a50a31c4c969" />


## 📱 Axion AOSP v2.4 - SOLACE - QPR1
**Device:** Realme 8i / Narzo 50 (spaced)
**Build Date:** Feb 06, 2026
**Status:** Stable | Beta

---

## 📝 Description
This build brings Axion AOSP to the Realme Spaced with core hardware functionality now active. This release resolves the critical camera crash loop and includes kernel optimizations for improved system response.

## ✅ What's Working
- **System:** Successfully boots and passes initial setup.
- **Display:** Full graphics acceleration (Mali GPU).
- **Biometrics:** **Fingerprint sensor is operational** (Verified via BiometricService).
- **Camera:** **Fully Functional.** Fixed the `libbinder-v32` linker error that caused the camera service to crash.
- **Performance:** Integrated kernel header fixes (`sched.h`) and scheduling tweaks.
- **Connectivity:** Wi-Fi, Bluetooth, and RIL.

## ⚠️ Installation Instructions (Clean Flash Required)
A clean flash is mandatory to ensure all new vendor libraries load correctly.

1. **Reboot** to Custom Recovery.
2. **Format Data:** Go to Wipe -> **Format Data** -> type `yes`.
*(Required to handle new encryption and vendor paths)*.
3. **Wipe:** Cache and Metadata.
4. **Flash:** ROM `.zip`.
5. **Reboot:** System.

## 🪲 Known Bugs
- **Bugs:** You tell me and get logs.

## ✅ Changelogs
- **Kernel:** Switched to Nebula Prime+ by @HELLINFIX.
 - **Lag fix:** Adjusted blur resolution divisor for improved frame stability in heavy UI elements.
 -** Visuals:** Implemented Squircle-style Recents with a 32dp corner radius.
- **Power Management:** Enabled native battery percentage toggle in System Settings.
- **Stability:** Integrated core kernel header fixes for improved system response.

---
**Build Version:** 2.4-SOLACE-UNOFFICIAL
**Android Version:** 16 - QPR1
**Maintainer:** DEEZNUTZ

Credits: Huge thanks to @HELLINFIX for trees and tweaks! 🫡🔥
