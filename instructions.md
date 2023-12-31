---
layout: page
title: "About"
permalink: /about/
---


# Flashing Instructions

1. Flash Provided [ Recovery ](https://sourceforge.net/projects/win-abs/files/ginkgo/Teamwin%20Recovery/recovery_FbeV2.img/download)  image using fastboot.

```sh
fastboot flash recovery recovery_FbeV2.img
```
Or flash using existing recovery.
Ignore mount erros at this stage.

2. Wipe cache, dalvik, system, vendor and format data.

3. Reboot to recovery and flash flash [ dynamic partition converter ](https://sourceforge.net/projects/kycii91-j4plus/files/Ginkgo/Ginkgo_Retrofit_Dynamic_Partitions_Converter.zip/download) zip.

4. Reboot to recovery and flash ROM.
4. Reboot to system and enjoy.

