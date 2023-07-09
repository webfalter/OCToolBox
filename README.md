# OCToolBox

[![GitHub release](https://img.shields.io/github/release/webfalter/OCToolBox?include_prereleases=&sort=semver&color=blue)](https://github.com/webfalter/OCToolBox/releases/)
[![download-badge](https://img.shields.io/github/downloads/webfalter/OCToolBox/total.svg?style=flat-square "Download status")](https://github.com/webfalter/OCToolBox/releases/latest "Download status")
[![Donate](https://img.shields.io/badge/-Buy%20me%20a%20coffee-orange.svg)](https://www.paypal.com/paypalme/webfalter)
-----

### Calculate Tool for OpenCore

![](./img/info.png)

## Supported
### [![OpenCore version](https://img.shields.io/badge/OpenCore-0.7.4+-informational.svg)](https://github.com/acidanthera/OpenCorePkg) [![MacOS version](https://img.shields.io/badge/Bigsur-11.6.0+-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Monterey-12.0.0+-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Ventura-13.0.0+-informational.svg)](https://www.apple.com/macos) 

## Next Version v1.0.2
| Menü | | | | | 
| ------------------- | --------------------------------- | --------------------------------- | --------------------------------- | --------------------------------- |
| Debug |Target |DisplayLevel | | | 
| Patch |Audio |Grafik |Framebuffer |Connectors |
| OpenLinuxBoot | | | | |
| NVRAM |SIP |DarkWake | | |
| Picker Attributes | | | |  |
| Security |Scan Policy |Vault |~~OpenCore Menu Password~~ | |
| Expose Sensitive Data |  | | |  |
| Tools |SMBios |~~Calculator~~ |~~Logs~~ | |
| Kext |HibernationFixup | | | |

## Discussion
- 

## Quellen
https://github.com/acidanthera/OpenCorePkg/blob/master/Include/Acidanthera/Library/OcConfigurationLib.h
https://github.com/acidanthera/OpenCorePkg/blob/master/Include/Acidanthera/Library/OcBootManagementLib.h
https://github.com/acidanthera/OpenCorePkg/blob/master/Include/Apple/IndustryStandard/AppleCsrConfig.h
https://github.com/acidanthera/OpenCorePkg/blob/master/Platform/OpenLinuxBoot/LinuxBootInternal.h
https://github.com/acidanthera/OpenCorePkg/blob/master/Include/Acidanthera/Protocol/OcLog.h
https://opensource.apple.com/source/xnu/xnu-7195.121.3/bsd/sys/csr.h.auto.html
https://github.com/acidanthera/WhateverGreen/blob/master/Manual/IntelFramebuffer.bt
https://github.com/apple/darwin-xnu/blob/main/iokit/Kernel/IOPMrootDomain.cpp#L488
https://dortania.github.io/OpenCore-Post-Install/usb/misc/keyboard.html#method-3-configuring-darkwake ???
https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf


## Credits
* [Entwicklern von OpenCore](https://github.com/acidanthera) & [Clover](https://github.com/CloverHackyColor/CloverBootloader)
* [Entwicklern von gfxutil](https://github.com/acidanthera/gfxutil)
* [Entwicklern von macserial](https://github.com/acidanthera/OpenCorePkg/tree/master/Utilities/macserial)
* [Cobanramo](https://github.com/CobanRamo) für die Idee und Excel Datei zur SIP
* ITzTravelInTime für TINURecovery
* The OSx86-Gang beim Input & fleißigen Testen
