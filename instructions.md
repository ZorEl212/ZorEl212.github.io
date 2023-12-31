---
layout: page
title: "Instructions"
permalink: /instructions/
---


# Flashing Instructions

-> Flash Provided [ Recovery ](https://sourceforge.net/projects/win-abs/files/ginkgo/Teamwin%20Recovery/recovery_FbeV2.img/download)  image using fastboot. Or flash using existing recovery.

```sh
fastboot flash recovery recovery_FbeV2.img
```

Ignore mount erros at this stage.

-> Wipe cache, dalvik, system, vendor and format data.

-> Reboot to recovery and flash flash [ dynamic partition converter ](https://sourceforge.net/projects/kycii91-j4plus/files/Ginkgo/Ginkgo_Retrofit_Dynamic_Partitions_Converter.zip/download) zip.

-> Reboot to recovery and flash ROM.
4. Reboot to system and enjoy.

