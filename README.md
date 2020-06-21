macOS Catalina & Mojave & High Sierra on XiaoMi NoteBook Pro 2019 & 2020

![[Tenten Guide] Xiaomi Mi Notebook Pro MX250 2020 - 10.15 Catalina Hackintosh](https://i.imgur.com/UpNM1h6.png)


## Spec (Chinese)
- 小米笔记本Pro 15 (小米笔记本Pro 15 增强版)
- 第十代英特尔® 酷睿™ i7-10510U处理器
- NVIDIA® GeForce® MX250 独立显卡
- 2GB GDDR5 显存
- 16GB DDR4 双通道内存
- 1TB PCle SSD 存储
- 深空灰
- 指纹解锁

![Tenten Mibook Pro Hackintosh - 2020](https://i.imgur.com/kJcT4Oi.png)

## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Xiaomi NoteBook Pro 15.6 - 2020 (MX250/GTX)      |
| Processor           | i7-10510U Processor     |
| Memory              | 8GB/16GB Samsung DDR4 2400MHz              |
| Hard Disk           | Intel 660P 1TB    |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Monitor             | BOE NV156FHM-N61 FHD 1920x1080 (15.6 inch) |
| Sound Card          | Realtek ALC298 (layout-id:30/99)           |
| Wireless Card       | Intel Wireless 8265                        |
| SD Card Reader      | Realtek RTS5129/RTS5250S                   |


### First-time installation

- Please refer to the following installation tutorials
  - [Xiaomi Mi Notebook Pro High Sierra 10.13.6](https://www.tonymacx86.com/threads/guide-xiaomi-mi-notebook-pro-high-sierra-10-13-6.242724)
  - [Xiaomi Mi Notebook Pro MacOS Catalina Installation Guide || ENGLISH](https://bit.ly/34biTqw)
- or video tutorials
  - [Xiaomi NoteBook PRO HACKINTOSH INSTALLATION GUIDE !!!](https://www.youtube.com/watch?v=72sPmkpxCvc)
  - [GUIA HACKINTOSH ESPAÑOL 2020 || Instalación de macOS Catalina Xiaomi Mi Notebook Pro](https://www.youtube.com/watch?v=rfG4sGwhE2g)
- If the trackpad doesn't work during the installation, please plug a wired mouse or a wireless mouse projector before the installation. After the installation completes, open `Terminal.app` and run `sudo kextcache -i /`. Wait for the process ending and restart the device. Enjoy your trackpad!
- Complete EFI packs are available in the [releases](https://github.com/daliansky/XiaoMi-Pro-Hackintosh/releases) page.
 - Please don't clone or download the master branch for daily use.
 

## Benchmark with Apple Macbook Pro
![Xiaomi MiBook Pro Mx250 2020 - CPU Geenbenck with MacBook Pro (13-inch Mid 2019)](https://i.imgur.com/AcnGOTg.png)

## FAQ

#### My touchpad isn't working after update.

You need to rebuild the kext cache after every system update. Use `Kext Utility.app` or type `sudo kextcache -i /` in `Terminal.app`. Then restart. If this still doesn't work, try to press F9.



## Credits
- [daliansky / XiaoMi-Pro-Hackintosh](https://github.com/daliansky/XiaoMi-Pro-Hackintosh)
- Thanks to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [NVMeFix](https://github.com/acidanthera/NVMeFix), [OcBinaryData](https://github.com/acidanthera/OcBinaryData), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooInput](https://github.com/acidanthera/VoodooInput), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [apianti](https://sourceforge.net/u/apianti), [blackosx](https://sourceforge.net/u/blackosx), [blusseau](https://sourceforge.net/u/blusseau), [dmazar](https://sourceforge.net/u/dmazar), and [slice2009](https://sourceforge.net/u/slice2009) for providing [Clover](https://github.com/CloverHackyColor/CloverBootloader).
- Thanks to [daliansky](https://github.com/daliansky) for providing [OC-little](https://github.com/daliansky/OC-little).
- Thanks to [FallenChromium](https://github.com/FallenChromium), [jackxuechen](https://github.com/jackxuechen), [Javmain](https://github.com/javmain), [johnnync13](https://github.com/johnnync13), [Menchen](https://github.com/Menchen), [Pasi-Studio](https://github.com/Pasi-Studio), [qeeqez](https://github.com/qeeqez), and [Bat.bat](https://github.com/williambj1) for valuable suggestions.
- Thanks to [hieplpvip](https://github.com/hieplpvip) and [syscl](https://github.com/syscl) for providing sample of DSDT patches.
- Thanks to [RehabMan](https://github.com/RehabMan) for providing [EAPD-Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander), [EFICheckDisabler](https://github.com/RehabMan/hack-tools/tree/master/kexts/EFICheckDisabler.kext), [OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config), [OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet), and [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- Thanks to [zxystd](https://github.com/zxystd) for providing [IntelBluetoothFirmware](https://github.com/zxystd/IntelBluetoothFirmware).



## Support and discussion

- tonymacx86.com:
  - [[Guide] Xiaomi Mi Notebook Pro High Sierra 10.13.6](https://www.tonymacx86.com/threads/guide-xiaomi-mi-notebook-pro-high-sierra-10-13-6.242724)
- Tenten venture studio
 - [小米 Book Pro 黑苹果 - Clover EFI 安装 (小米笔记本PRO)](https://university.tenten.co/t/topic/228)
 - [Boardcom Wifi of Hackintosh Xiaomi Book Pro](https://university.tenten.co/t/topic/220)
 - [Xiaomi Pro Hackintosh Build (10.13 High Sierra / 10.14 Mojave)](https://university.tenten.co/t/topic/51)

## Support and discussion
