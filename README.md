
<p align="center">
Coolpad Note 3- LineageOS 14.1 / AOSP 7.1.1

===============================================================

This branch is device for building of the LineageOS 14.1 and Android Nougat 7.1.1 AOSP ROMs.



# About Device

Coolpad Note 3(CP8676_I02)
![Coolpad Note 3](https://cdn2.gsmarena.com/vv/pics/coolpad/coolpad-note3-lite.jpg "Coolpad Note 3")

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | 1.3GHz Octa-Core MT6753
GPU     | Mali-T720
Memory  | 3GB RAM
Shipped Android Version | 5.1.1
Storage | 16GB
Battery | 3000 mAh
Display | 5.5" 1080 x 720 px DPI 320
Rear Camera | 13MP, Int.13MP 
Front Camera | 5MP, Int. 5MP

---

# Build Information

### Working
 * Wifi
 * Hotspot
 * Bluetooth
 * Vibration
 * Audio
 * Micro SD
 * RAM and ROM
 * Rotation
 * Camera rear/front (photographs only)
 * All sensors
 * Offline charging
 * RIL
 * Auto brightness
 * Screen Recording
 * Flashlight
 * Camera rear/front (video)
 * Fingerprint scanner
 * OTG
 * GPS

 ## Bugs
 * Video_Camera


### Thanks to:
 * LineageOS team
 * kuber_Sharma
 * Team M.A.D
 * Mohancm
 * Sam Grande
 * Sandpox
 * Ishant Vivek
 

 
 
To sync the tree with rom :-

    git clone https://github.com/sougata7684/android_device_coolpad_CP8676_I02 -b LineageOS-14.1 device/coolpad/CP8676_I02
	git clone https://github.com/sougata7684/android_vendor_coolpad_CP8676_I02 -b LineageOS-14.1 vendor/coolpad/CP8676_I02
	git clone https://github.com/sougata7684/android_kernel_coolpad_CP8676_I00 -b LineageOS-14.1 kernel/coolpad/CP8676_I02 
	
To apply the patches -

    sh device/coolpad/CP8676_I02/patches/install.sh
	sh device/coolpad/CP8676_I02/patches/uninstall.sh
