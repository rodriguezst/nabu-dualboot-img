# DualBoot Images for Xiaomi Pad 5 (nabu)
This repository generates boot.img files for nabu with dualboot capability using [DualBootKernelPatcher](https://github.com/woa-msmnile/DualBootKernelPatcher).

- If the tablet is (re)booted with the **magnetic cover closed -> Android** (HyperOS) kernel will be started
- If the tablet is (re)booted with the **magnetic cover open -> UEFI** from [map220v](https://github.com/map220v/MU-sm8150pkg/tree/nabu-secureboot) will be started

Images are generated for Xiaomi HyperOS **EUROPE and GLOBAL** versions. For each of them **SB (SecureBoot enabled)** and **NOSB (SecureBoot disabled)** images are built.
## Credits
[DualBootKernelPatcher](https://github.com/woa-msmnile/DualBootKernelPatcher)

[UEFI](https://github.com/map220v/MU-sm8150pkg/tree/nabu-secureboot)

[SurfaceDuo-Guides](https://github.com/WOA-Project/SurfaceDuo-Guides/blob/main/Install/DualBoot.md)