android_device_lge_lgl21
==========================

CyanogenMod 11.0 device tree for LGL21 (KDDI Optimus G) 

Working:
* Graphics
* Sound
* Wifi
* Bluetooth
* Sensors
* GPS
* Camera
* Video
* Vibrator

Unknown working
* Phone
* 3G
* LTE
* NFC

Notes:
1. Proprietary files is LS970-CM11

2. WLAN Driver 
   Source is from Mako's Old Source 
   #define QWLAN_VERSIONSTR               "3.1.7.11"
   WCNSS_qcom_wlan_nv.bin                 LGL21 4.0 firmware     

3. overlay/ ... /config.xml 
   modified config_autoBrightnessLevels, config_autoBrightnessLcdBacklightValues

Tree:
device/lge/lgl21
device/lge/lgl21-common
device/lge/gproj-common-lgl21
kernel/lge/kbc_geehdc_kddi
vendor/lge/lgl21

