# Acer-Swift3-SF31552G-2020-Hackintosh-Guide

This Hackintosh guide is for Acer swift 3 2018 model with intel UHD 620 Graphics.

## Specs

• CPU : Intel Core i5-8250U (Kabylake-R)

• Graphics : Intel UHD 620 + Nvidia mx150

• RAM : 8GB DDR4 2600Mhz (replaceable)

• SSD : 256GB (HFS256G39TD-N210A) (replaceable)

• Screen : 15-inch 1920 x 1080 IPS

• Ports : 1 x USB 3.1 Type-C, 2xUSB 3.0, 1xUSB 2.0, 1xHDMI, Audi Jack

• Wifi/Bluetooth : Intel AC-7265 Dual Band

• Audio : ALC256

• SD Card Reader : Realtel USB2.0-CRW

• Back-lit keyboard

• Fingerprint Sensor

• I2C Trackpad + PS2 keyboard

### What is working
• Wifi 
  - by default it's not working. Some kext files are required.
    You have to manually configure the BSSID and the Password.
• Bluetooth 
  - Working but some minor bugs.
  
• Graphics 
  - Have to inject the intel graphics from the clover configurator.

• Keyboard 
  - Pre-installed ACPI-managed working good.

• Trackpad 
  - Voodool2c needs to be add for the macOS Gestures.

• USB 
  - Not all the devices are supported. Tested ios 12 devices and some USB pen drive just work fine for        me.

• Webcam 
  - Photobooth working.

• Sleep/Wake 
  - Lid is working.

### What is not working?

• Fingerprint

• HDMI

• Audio 
  - Although the kext files are available for the ALC-256 for some reason didn't work for me.
  
• Nvidia Graphics

## Steps

### 1. Creating the bootable flash drive



* Hat tip to anyone whose code was used
* Inspiration
* etc

