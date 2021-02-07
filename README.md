# Hackintosh on CometLake Z490 PC with OpenCore

<img src="https://github.com/18520339/Hackintosh-CometLake-Z490-OpenCore/blob/master/demo.png" />

OS Version: MacOS Catalina 10.15.6

Current Bootloader: [OpenCore 0.6.0](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.0)

## Hardware

-   CPU: Intel Core i9 10th Gen (_Comet Lake_)
-   Mainboard: Gigabyte Z490 Gaming X
-   iGPU: Intel UHD Graphics 630 (_used for MacOS_)
-   dGPU: NVIDIA RTX 2080 Super (_used for Windows_)

## Bios Settings

### Disable:

-   Fast Boot
-   Secure Boot
-   CSM Support
-   Intel Platform Trust
-   VT-d

### Enable:

-   Internal Graphics
-   Above 4G decoding
-   Hyper-Threading

### Others:

-   Windows 10 Feautures: Other
-   DVMT Pre-Allocated (iGPU Memory): 64MB
-   Initial Display Ouput: IGFX (for using Internal graphics)

## Many thanks to

-   https://dortania.github.io/OpenCore-Install-Guide/
-   https://github.com/SchmockLord/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D
-   https://github.com/SwimmingPig/Hackintosh-Intel-i5-10400-Gigabyte-Z490M-Gaming-X
-   https://www.youtube.com/watch?v=a9rA0F6g61s
