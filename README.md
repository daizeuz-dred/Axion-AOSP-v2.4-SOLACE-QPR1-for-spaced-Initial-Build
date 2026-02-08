<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/16ebe19a-8b6c-470d-9ead-a50a31c4c969" />


📱 Axion AOSP v2.4 - SOLACE - QPR1

Device: Realme 8i / Narzo 50 (spaced)

Build Date: Feb 07, 2026

Status: Stable | Beta

✅ What's Working
- System: Successfully boots and passes initial setup.
- Display: Full graphics acceleration (Mali GPU).
- Biometrics: Fingerprint sensor is operational** (Verified via BiometricService).
- Camera: Fully Functional. Fixed the `libbinder-v32` linker error that caused the camera service to crash.
- Performance: Integrated kernel header fixes and scheduling tweaks.
- Connectivity: Wi-Fi, Bluetooth, and RIL.

⚠️ Installation Instructions (Clean Flash Required)
A clean flash is mandatory to ensure all new vendor libraries load correctly.

1. Reboot to Custom Recovery.
2. Format Data: Go to Wipe -> Format Data -> type `yes`.
(Required to handle new encryption and vendor paths)
3. Wipe: Cache and Metadata.
4. Flash: ROM `.zip`.
5. Reboot: System.

 🪲 Known Bugs
- Whatsapp & Snapchat not working: Still haven't found any fix for this.
-  If there's more then you tell me and send me proper logs.**

 ✅ Changelogs
- Kernel is integrated with KernelSU Next v1
- Kernel: Switched to Nebula Prime+ by @HELLINFIX.
- Lag fix: Adjusted blur resolution divisor for improved frame stability in heavy UI elements.
- Ram Management: Improve the ram management.
- Stability: Integrated core kernel header fixes for improved system response.


Build Version: 2.4-SOLACE-UNOFFICIAL
Android Version: 16 - QPR1
Maintainer: DEEZNUTZ

Credits: Huge thanks to @HELLINFIX for trees and tweaks! 🫡🔥

RECOMMENDED KERNEL IS ALSO UPLOADED!
Nebula Prime +
