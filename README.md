# Advan-X1
All of these are not mine and can be found in each creators page

⚠️ This setup is based on community tools and personal testing. Compatibility may vary depending on ROM/kernel version.

**Magisk:**
Requires Zygisk enabled
Compatible with most modules

**KernelSU Next:**
More system-level integration
Better stealth in some cases

Do NOT use Twrp (Team Win Recovery Project) for Advan X1 cause it sometime buggy and treats you like shit
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

Suggested Setup Order:
-Flash OrangeFox Recovery
-Install Magisk or KernelSU
-Enable Zygisk (if Magisk)
-Install Zygisk Next
-Configure Shamiko / DenyList
-Add Play Integrity Fix (If you want to use Tricky Store you must reconfigure Play Fix)
Optional: Tricky Store / HMA-OSS
Reboot & test integrity

🚫 Known Risks
Module conflicts if overstacked
Bootloops if improper flashing sequence
Integrity break after Play Services updates
Detection by apps using advanced root detection

⚠️Disclaimer
This project is for educational and research purposes.
Use at your own risk.