# DualBoot Images for Xiaomi Pad 5 (nabu)
This repository generates Zip Installer (for Magisk/Recovery) to enable dualbooting on Xiaomi Pad 5 using magnetic cover.

- If the tablet is (re)booted with the **magnetic cover closed -> Android** kernel will be started
- If the tablet is (re)booted with the **magnetic cover open -> UEFI** from [map220v](https://github.com/map220v/MU-sm8150pkg/tree/nabu-secureboot) will be started

**SB (SecureBoot enabled)** and **NOSB (SecureBoot disabled)** variants are generated.
## Installation ##
Download the Zip in the variant you need (SecureBoot enabled or not) and flash it using Magisk Manager or TWRP recovery.
## Credits
[DualBootKernelPatcher](https://github.com/Project-Aloha/DualBootKernelPatcher)

[UEFI](https://github.com/map220v/MU-sm8150pkg/tree/nabu-secureboot)

[SurfaceDuo-Guides](https://github.com/WOA-Project/SurfaceDuo-Guides/blob/main/Install/DualBoot.md)