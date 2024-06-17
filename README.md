# realtek_usblan_on_mcu
# This repo is introducting a method to bring up the Realtek Usb Lan devices on general micro-controller.
# Realtek Usb lan chip own at least 2 sets of usb configurations for a Usb host. 
# one is about the vendor mode which is used for the Realtek inhouse windows and linux driver.
# the other one is about the cdc_ecm configuration which is usually used for the PNP support for linux kernel based runtime devices.
# in this repo i will bring up the RTL8152B-VB-CG device via the cdc_ecm configuration(#2) with the micro controller based on cortex m4 deivce.

# also the lwip stack will be porting into this repo as well to achieve the basic network support.


