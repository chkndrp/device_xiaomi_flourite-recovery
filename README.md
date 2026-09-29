# device_xiaomi_flourite-recovery

Recovery tree for these Xiaomi devices:
- Xiaomi Redmi Note _15 Pro+_ 5G / POCO M8 Pro 5G (codename: `flourite`) (December 2025)

## Device specifications

Device                  | Redmi Note 15 Pro+ 5G / POCO M8 Pro 5G
:-----------------------|:-------------------------------------
SoC                     | Qualcomm Snapdragon® 7s Gen 4 (SM7635-AC)
Board                   | `volcano`                            
CPU                     | Octa-core (1x2.7 GHz Cortex-A720 & 3x2.4 GHz Cortex-A720 & 4x1.8 GHz Cortex-A520)
GPU                     | Adreno 810
Memory                  | 8/12/16 GB RAM
Shipped Android Version | 15.0 (HyperOS 2)
Storage                 | 256/512 GB (UFS 2.2)
MicroSD                 | No
Battery                 | Non-removable Li-Po 6500 mAh
Dimensions              | 163.3 x 78.3 x 8.2 mm
Display                 | 6.83" CrystalRes AMOLED, 120Hz, 1280x2772

## Checklist
- [x] ADB
- [x] Decryption
- [x] Touchscreen
- [x] FastbootD
- [x] Flashing
- [x] MTP
- [x] Sideload
- [x] Backups
- [x] Filesystems/Mounts
- [x] Slot switch
- [x] Haptics
- [x] Flashlight
- [x] Custom splash

## How to build
This recovery tree was initially made for `flourite`. For historical purposes,
build the `twrp_flourite` target

```shell
lunch twrp_flourite-bp2a-eng && mka adbd recoveryimage
```
