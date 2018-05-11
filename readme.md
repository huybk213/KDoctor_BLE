1. Bootloader file: release/bootloader.hex
2. Application file: release/app.hex
3. Key: release/private.key, release/public_key.c
4. Crypo library: release/micro_ecc_lib_nrf51
5. Everytime private.key or publish_key.c was changed, please rebuild project
6. Step by step to program
+ Program softdevice
+ Program bootloader
+ Copy app_dfu_package.zip to mobile, and use NRF Toolbox in playstore to transfer firmware, must not program app.hex directly from programer or debugger.
HuyTV