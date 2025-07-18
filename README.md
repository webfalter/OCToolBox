# OCToolBox
[![GitHub release](https://img.shields.io/github/release/webfalter/OCToolBox?include_prereleases=&sort=semver&color=blue)](https://github.com/webfalter/OCToolBox/releases/)
[![Github Releases (by release)](https://img.shields.io/github/downloads/webfalter/OCToolBox/1.1.2/total.svg)](https://GitHub.com/webfalter/OCToolBox/releases/)
[![Github Releases (by release)](https://img.shields.io/github/downloads/webfalter/OCToolBox/1.1.4/total.svg)](https://GitHub.com/webfalter/OCToolBox/releases/)
[![download-badge](https://img.shields.io/github/downloads/webfalter/OCToolBox/total.svg?style=flat-square "Download status")](https://github.com/webfalter/OCToolBox/releases/latest "Download status")
#### If you would like to send me a small thank you, you can do so via PayPal: [Spende](https://www.paypal.com/paypalme/webfalter)
#### Wer mir ein kleines Dankeschön senden möchte, kann das über PayPal tun: [Spende](https://www.paypal.com/paypalme/webfalter)

## Supported
### [![OpenCore version](https://img.shields.io/badge/OpenCore-0.7.4+-informational.svg)](https://github.com/acidanthera/OpenCorePkg) [![MacOS version](https://img.shields.io/badge/Bigsur-11.6.0+-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Monterey-12.0.0+-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Ventura-13.0.0+-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Sonoma-14.0.0+-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Sequoia-15.0.0+-informational.svg)](https://www.apple.com/macos)


### Calculate Tool for OpenCore
![](./img/info.png)

Lengende mit Symbolen die sich durch jeden Tab ziehen
## Beispiel Anhand Target
### mit Hand
![](./img/variante_4.png)
1. Wert bestimmen 
2. Click berechnen
### Default (nach Vorgabe)
![](./img/variante_3.png)
1. Click Default Wert
2. Wert lassen oder ändern 
3. Click berechnen
### mit Wert
![](./img/variante_5.png)
1. Wert eintragen
2. Click Wert prüfen (rot/grün)
3. Wert lassen oder ändern 
4. Click berechnen
### mit Config.plist
![](./img/variante_6.png)
1. Config Wert laden (nur bei geladener plist)
2. Click Wert prüfen (rot/grün)
3. Wert lassen oder ändern  
4. Click berechnen
   
## Zusätzlich
### Löschen
![](./img/variante_1.png)
1. Löscht alle Eingaben
### Kopieren
![](./img/variante_7.png)
1. Berechneter Wert
2. Lädt Wert in die Zwischenablage
### Schreiben
![](./img/variante_2.png)
1. Berechneter Wert
2. Click Schreibt bei geladener plist 

## Next Version v1.0.8
| Menü | | | | | 
| ------------------- | --------------------------------- | --------------------------------- | --------------------------------- | --------------------------------- |
| Debug |Target |Display & HaltLevel | | | 
| Patch |Audio |Grafik |Framebuffer |Connectors |
| OpenLinuxBoot | | | | |
| NVRAM |SIP |DarkWake | | |
| Picker Attributes | | | | |
| Security |Scan Policy |Vault | | |
| Expose Sensitive Data | | | |  |
| PlattformInfo |SMBios |StartupPowerEvents |~~Calculator~~ | | 
| Kext |HibernationFixup |AMFI | | |

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
* [ITzTravelInTime](https://github.com/ITzTravelInTime) für TINURecovery
* [Steffan Andrews](https://github.com/orchetect) für seine Swift Tools
* The OSx86-Gang beim Input & fleißigen Testen
