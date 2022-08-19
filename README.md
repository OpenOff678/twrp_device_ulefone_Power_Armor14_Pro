Device Tree for Umidigi Bison Pro - mt6768 - MT6769T
--------------------------------------------------------
# TWRP device tree for Oukitel WP5 Pro
## MT6762_65 - A10 - updated to A11
---------------
- Firmware version: OUKITEL_WP5_Pro_EEA_A11_V05_20210915
Status: testing

recovery-WP5_Pro_EEA_R-A11-nnnnnnn.img => Working?? Not Working???
------------------------------------
## Device specifications
Basic   | Specification Sheet
-------:|:-------------------------
Release Date | October 16, 2021
Shipped Android Version | 11
Chipset | Mediatek Helio G80
CPU     | Octa-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)
GPU     | Mali-G52 MC2
Memory  | 4/8GB
Storage | 128 GB
MicroSD | Up to 512 GB
Battery | Li-Po 5000 mAh, non-removable
Display | 1080 x 2340 pixels, 6.3"
Rear Camera  | 48 & 16 MP
Rear Depth Sensor  | 5 MP
Front Camera | 24 MP LED flash, HDR
Features| Fingerprint (side-mountedn sensor), accelerometer, proximity, compass, IR Thermometer

![Umidigi Bison Pro](https://cdn-files.kimovil.com/default/0006/34/thumb_533552_default_big.jpeg)

## What's the history?

- 21/05/2022 TWRP booted--> boot-BISON_Pro-A11-20220520-1538.img;

## Credits

- [stalkerc from 4pda](https://4pda.to/forum/index.php?showuser=5093778) - For testing & photos of TWRP.<br/>
- [2mkl from 4pda](https://4pda.to/forum/index.php?showuser=254002) - For testing of TWRP.<br/>





![Oukitel WP5 Pro](https://cdn-files.kimovil.com/default/0004/85/thumb_384707_default_big.jpeg)

## Big thanks to:
- [2mkl from 4pda](https://4pda.to/forum/index.php?showuser=254002) - For testing of TWRP.<br/>
- [TeamWin](https://github.com/TeamWin) for TWRP SC.
* TWRP version 3.6.2_11 *

                  ####### generated by lopestom #######
================================
# TWRP Pictures
## ©2022
-------------
![Initial Menu](https://github.com/lopestom/twrp_device_umidigi_BISON_Pro/blob/android-11.0/.pictures/TWRP3.6.1_11-UMIDIGI%20BISON%20Pro_RU-20220521_103640.jpg?raw=true)
![Backup Partitions](https://github.com/lopestom/twrp_device_umidigi_BISON_Pro/blob/android-11.0/.pictures/TWRP3.6.1_11-UMIDIGI%20BISON%20Pro_RU-20220521_104739.jpg?raw=true)

## To build with minimal twrp AOSP
```
export ALLOW_MISSING_DEPENDENCIES=true
export LC_ALL=C
export USE_NINJA=false
. build/envsetup.sh
lunch twrp_WP5_Pro_EEA_R-eng
mka bootimage
```

