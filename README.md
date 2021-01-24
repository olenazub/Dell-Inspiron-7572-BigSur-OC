# OpenCore EFI configuration for Dell Inspiron 7572 notebook
# Note: This EFI file is applicable to run Big Sur version.

This EFI configuration is based on @iXeor - [https://github.com/iXeor/Dell-Inspiron-7572-BigSur-OC]

* Computer Model: Notebook Dell Inspiron 7572
* BIOS: 1.5.3
* OSs: MacOS Big Sur 11.1 / Windows 10 Professional
* Processor: Intel Core i5-8250U @1.80GHz quad-core eight threads
* RAM: 16 GB DDR4 2400MHz - XPG
* Hard Disk 1:	120 GB NVME SSD - Patriot
* Hard Disk 2:	360 GB SSD - Kingspeac
* Graphics 1:	Intel HD Graphics 620 (4 GB video memory reserved)
* Graphics 2:	NVIDIA MX 150 4G (Disabled)
* Monitor:	BOE NV156FHM-H61 FHD 1920x1080 (15.6 inches)
* Sound card:	ALC256 (layout-id:2/56)
* Network/BT card:	Fenvi BCM94360NG [https://abre.ai/b3eh]
* OpenCore version	OpenCore-0.6.5-RELEASE

What works? 
* Almost everything...
* Hardware acceleration
* External HDMI with audio
* Internal audio/mic
* ComboJack with audio/mic see here [https://github.com/hackintosh-stuff/ComboJack]
* Keyboard with backlight and hotkeys
* Touchpad with gestures
* WIFI/BT works natively
* AirPlay works natively - Tested with Samsung 4K TV
* Handoff works natively - Tested with Ipad Mini 5

Currently known problems and solutions:
* 
* It is normal for occasional screens to appear in the second and third stages of the installation, wait for it to restart automatically
* Sometimes when increasing and decreasing the volume the audio stops working
* DRM doesn't work, it was already expected
* Send files with Airdrop doesn't work either
