# Advan-X1
All of these are not mine and can be found in each creators page

⚠️ This setup is based on community tools and personal testing. Compatible only with Stock ROM/Kernel

**Magisk:**
Requires Zygisk enabled
Compatible with most modules

**KernelSU Next:**
More system-level integration
Better stealth in some cases

Do NOT use Twrp (Team Win Recovery Project) for Advan X1 TWRP due to instability on some Advan X1 builds.
DO use OrangeFox For stability and easy installation from both Windows & Linux in release pack or Advan X1 telegram community

PLEASE use KsuWebUI to manage the Zygisk next

NOTES:
Disable Enforce DenyList if using Shamiko, Avoid stacking multiple overlapping hiding modules, and Do NOT mix conflicting root concealment layers blindly


When configured correctly, this setup may pass **Basic Intergrity, Device Intergrity, Strong Intergrity**

Note: Play Integrity is server-side and may change at any time.

| Module | Link | Purpose |
|:-------|:----:|:--------|
| Zygisk Next | https://github.com/Dr-TSNG/ZygiskNext | Provides Zygisk support and improves compatibility with other modules. |
| TrickyStore | https://github.com/5ec1cff/TrickyStore | Spoofs device properties to help pass integrity checks. |
| Play Integrity Fork | https://github.com/osm0sis/PlayIntegrityFork | Works alongside TrickyStore to improve Play Integrity compatibility. |
| Shamiko | https://github.com/LSPosed/LSPosed.github.io/releases/tag/shamiko-414 | Hides root-related modifications from selected apps without enforcing DenyList. |


What if you wanted to Lock the Bootloader again? its easy!

## Lock Bootloader

1. Make sure you're on **Stock ROM**.
   If not, your device may end up in an **eternal bootloop (soft brick)**.
2. Open your terminal (Windows/Linux).
3. Run:
   fastboot flashing lock
4. Confirm the bootloader lock on your phone using the Volume and Power buttons (if prompted).
5. The device may restart automatically.
   If it doesn't, reboot it manually and wait for it to boot.
6. If you are taken to Android Recovery and prompted to reset:
   Select Factory Data Reset to clear old files and caches.
7. Once the reset is complete, your device's bootloader is successfully locked.

🚫 Known Risks
Module conflicts if overstacked
Bootloops if improper flashing sequence
Integrity break after Play Services updates
Detection by apps using advanced root detection

⚠️Disclaimer
This project is for educational and research purposes.
Use at your own risk.

