# TWRP Device configuration for Samsung Galaxy Tab A 9.7" WiFi (gt510wifi/SM-T550)

Copyright 2018/2020 - The OmniROM Project

For building TWRP for Samsung Galaxy Tab A 9.7" WiFi ONLY.

### Kernel Source
Check here: https://github.com/Galaxy-MSM8916/android_kernel_samsung_msm8916

### How to compile
ubuntu 20.04+ sudo apt install -y libncurses5 libtinfo5

export ALLOW_MISSING_DEPENDENCIES=true

source build/envsetup.sh

lunch omni_gt510wifi-eng

mka recoveryimage


### Device specifications
=====================================
Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Qualcomm MSM8916 Quad-core 1.2 GHz ARM® Cortex™ A53
CHIPSET | Qualcomm MSM8916 Snapdragon 410
GPU     | Adreno 306
Memory  | 1.5 GB
Shipped Android Version | 5.1.1
Storage | 16 GB
MicroSD | Up to 256 GB
Battery | 6000 mAh
Display | 1024 x 768, 9.7" (246.38mm)
Rear Camera  | 5.0 MP
Front Camera | 2.0 MP

