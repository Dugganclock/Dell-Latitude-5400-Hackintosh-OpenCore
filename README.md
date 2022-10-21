# OpenCore EFI to run MacOS on Dell Latitude 5400 

---


**Foil or film, we shall enter The Kiln**


## Specification

| | |
|-|-|
|**Operating System**| MacOS 12.4 Monterey
|**SMBIOS**| MacBook Pro 15,4 (2019)
|**CPU**|Intel Core i5-8365U CPU (Whiskey Lake)|
|**RAM**|16GB DDR4 2666MHz|
|**IGPU**|Intel UHD 620|
|**SSD**|BC501 NVMe SK Hynix 256GB|
|**ETH**|Intel I219-LM|
|**WLAN+BT**|Intel 9560|
|**Audio**|Realtek ALC236|
|**Card Reader**|Dell RTS525A PCI Express Card Reader|


## Working

- Everything you would reasonably expect, highlights being:

- MicroSD reader
- Trackpad with full gestures

## Not working

- TrackPoint (or whatever Dell call it)

## Untested

- Display from USB-C Displayport
- Other versions of MacOS

## About

**A classic Davy B trade-in turned into a stable Hackintosh. Better than anything Apple are currently offering.**

Bought this stock with the specs above. Looked around for a fully working EFI and I suppose everyone thought it unreasonable to spend a few hours patching the holes. This baddy can now do everything within reason. Just download this repo, slam it on an installer USB and follow the usual steps. 

## Install notes

- BIOS settings = I followed the Dortania guide where applicable. 
- Make sure to generate your own SMBIOS values.
- Some nvme drives are either unsupported or require extra work. Luckily my one worked OOB.
- Touchpad acting odd? Go into the touchpad options and disable force click, enable silent clicking and tap to click.
- Brightness Keys = You can use Karabiner to map brightness keys if you really want them on the function row (by default you can alter brightness with fn+S and fn+B)
- Disable Hibernation and all the usual post-install Hackintosh steps.


