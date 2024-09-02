---
layout: page
title: "Instructions"
permalink: /instructions/
---


# Flashing Instructions

- Flash Provided [ Recovery ](https://sourceforge.net/projects/kycii91-j4plus/files/Ginkgo/Recovery/TWRP-Unified-Ginkgo.img/download)  image using fastboot. Or flash using existing recovery.

```sh
fastboot flash recovery TWRP-Unified-Ginkgo.img
```

Ignore mount erros at this stage.

- Wipe cache, dalvik, system, vendor and format data.

- Reboot to recovery and flash [ dynamic partition converter ](https://sourceforge.net/projects/kycii91-j4plus/files/Ginkgo/Ginkgo_Retrofit_Dynamic_Partitions_Converter.zip/download) zip.

- Reboot to recovery and flash ROM.
- Reboot to system and enjoy.

