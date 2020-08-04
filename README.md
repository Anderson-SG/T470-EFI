## EFI folder for booting Thinkpad T470 i5-7300u
![obligatory neofetch](https://preview.redd.it/lfmpdx6czgb51.jpg?width=1920&format=pjpg&auto=webp&s=90092648c0f9f9cde211975729bb5d252834ba81)

## Supported OS
 - MacOS Mojave [✔️] Completely tested.
 - MacOS Catalina [✔️] Completely tested.
 - MacOS Big Sur [❌] Does not work

## Supported Bot Loaders
 - Clover [✔️] 
 - OpenCore [❌] 

## Working
 - Boot [✔️] 
 - Intel HD620 [✔️] 
 - Audio (Local and External) [✔️] 
 - NVMe [✔️] 
 - Brightness control [✔️] 
 - Wake from sleep [✔️] 
 - Shutdown [✔️] 
 - Fan and Temp [✔️] 
 - Wifi [❌] You will need to change the wifi adapter for a supported one or use a usb wifi adapter

## Bios Settings
 - Security Chip = Disabled
 - Memory Protection -> Execution Prevention = Enabled
 - Virtualization = Disabled
 - Anti Theft = Disabled
 - Secure Boot = Disabled
 - UEFI/LegacyBoot = Both
 - UEFI/LegacyBoot Priority = UEFI First
 - CSM Support = YES

## Clover Boot Options
 - Boot Args = (Add a "-v" on end of line) this will enable verbose/debug mode.
 - Graphics Injector > PlataformId = 0x12345678

## DiskUtils Guide
 - Click on Erase Disk and select APFS on format.
 - On name you can chose a custom one. 

## Credit
 - https://github.com/RehabMan
 - https://www.tonymacx86.com/,
 - http://www.insanelymac.com/
  
