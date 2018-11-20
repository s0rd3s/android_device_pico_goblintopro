# android_device_pico_goblintopro
Tree for building TWRP for Pico G2PRO

## To compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_goblintopro-eng

mka adbd recoveryimage

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (4x2.45 GHz Kryo & 4x1.9 GHz Kryo)
Chipset | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 4 GB RAM
Shipped Android Version | 8.1
Storage | 64 GB & SD Card Slot
Battery | Li-Po 3500 mAh battery
Display | 1440 × 1600 pixels(per eye), 90 Hz refresh rate


## Device picture

![Pico G2PRO](https://holographica.space/wp-content/uploads/2018/08/picture-of-g2-products-at-the-conference.jpg "Pico G2PRO")
