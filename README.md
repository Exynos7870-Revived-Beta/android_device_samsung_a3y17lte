# TWRP for the Samsung Galaxy A3 2017

TWRP device tree for Samsung Galaxy A3 2017 (`a3y17lte`), based on the TWRP AOSP 12.1 manifest.

## Build
```bash
source build/envsetup.sh
lunch twrp_a3y17lte-eng
mka recoveryimage
```
The recovery image is `out/target/product/a3y17lte/recovery.img`.
