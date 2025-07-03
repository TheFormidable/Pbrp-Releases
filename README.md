![Poco x6 pro](https://github.com/TheFormidable/Pbrp-Releases/blob/c69949a25dbd491607450ef70cff5ce1f1cb56fd/1718293287771.png)
============================================================
PBRP Device configuration for POCO X6 PRO (duchamp)
============================================================
Basic   | Specification Sheet
-------:|:-------------------------
CPU     | Octa-core CPU with 4X Arm Cortex-A715 and 4X Cortex-A510
CHIPSET | Mediatek Dimensity 8300 Ultra (4nm)
GPU     | Arm Mali-G615 MC6
Memory  | 8GB - 12GB
Shipped Android Version | 14
Storage | 256 GB UFS 4.0 + MCQ
Battery | Li-Po 5000 mAh, non-removable


Release Date | Apr 30, 2024

# PITCH BLACK RECOVERY PROJECT | RECOVERY TREE FOR POCO X6 PRO

## Features:

- Almost all PBRP features are expected to be working on decrypted roms like ELITE ROM (LITE, NEXTGEN)
- ## If you are on a different version of Hyperos maybe you need to go to the troubleshooting section 


## Bugs 
- Encryption (partial)
- Flash light 

## What's New?

- Sync latest 12.1 sources.
- running on new hyperos version 1.0.9.0

# installation
 If you are in elite rom with twrp perilouspike just install image on vendor_boot partition 

 optional: restart to recovery to see if everything works and then to system


 if you are in fasboot 
"fastboot flash vendor_boot vendor_boot.img"

 "fasboot reboot recovery

 then reboot the system if you see that everything works.

## Build Date 

- 30/05/2024

## Credits

-SHIBU SHAJI @perilouspike for TWRP device tree's

-The_Formidable for Compilation

# troubleshooting

# Fix for 0 Mb or Bootloop in PBRP Duchamp


•Note : This will wipe/format your Data partition and your data will be reset.

INSTRUCTIONS :

1. Reboot your device into PBRP Recovery.

2. Go to Wipe menu.

3. Go to Advanced Wipe.

4. Select Data and go to Repair or Change File System.

4. Go to Change File System.

5. Select exFAT and confirm.
 
6. Now change back to F2FS and confirm.

7. Now go back to backup and check if storage is displayed correctly / can be mount or not from Mount menu.

8. Go to Wipe 

9. Format Data > yes 

If it tells you that you must reboot to recovery to be able to use /Data again , reboot to recovery, format data and then reboot to System


# ©2024
