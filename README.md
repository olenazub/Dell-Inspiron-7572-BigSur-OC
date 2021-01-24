# OpenCore EFI configuration for Dell Inspiron 7572 
## Note: This EFI file is applicable to run Big Sur

This EFI configuration is based on @iXeor - [https://github.com/iXeor/Dell-Inspiron-7572-BigSur-OC]

* Computer Model: Notebook Dell Inspiron 7572
* BIOS: 1.5.3
* OSs: MacOS Big Sur 11.1 / Windows 10 Professional
* Processor: Intel Core i5-8250U @1.80GHz 4/8
* RAM: 16 GB DDR4 2400MHz - XPG
* Hard Disk 1:	128 GB NVME SSD - Patriot
* Hard Disk 2:	360 GB SSD - Kingspeac
* Graphics 1:	Intel HD Graphics 620 (4 GB video memory reserved)
* Graphics 2:	NVIDIA MX 150 4G (Disabled)
* Monitor:	BOE NV156FHM-H61 FHD 1920x1080 (15.6 inches)
* Sound card:	ALC256 (layout-id:2/56)
* Network/BT card:	Fenvi BCM94360NG [https://abre.ai/b3eh]
* OpenCore version:	OpenCore-0.6.5-RELEASE

[![big_sur_7572.png](https://i.postimg.cc/BnzbxXkZ/big-sur-7572.png)](https://postimg.cc/qN8prMpW)

## What works? 
* Almost everything...
* Hardware acceleration
* External HDMI with audio
* Internal audio/mic
* ComboJack with audio/mic see here [https://github.com/hackintosh-stuff/ComboJack]
* Keyboard with backlight and hotkeys
* Touchpad with gestures
* WIFI/BT works natively
* AirPlay works natively
* Handoff works natively
* Sleep/wake

## Currently known problems and solutions:
* It is normal for occasional screens to appear in the second and third stages of the installation, wait for it to restart automatically
* Sometimes when increasing and decreasing the volume the audio stops working
* DRM doesn't work, it was already expected
* Send files with Airdrop doesn't work either
* Battery drains fast

## Credits and links
* [OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/)
* [ic005k](https://github.com/ic005k/DELL7472)
* [iXeor](https://github.com/iXeor/Dell-Inspiron-7572-BigSur-OC)
