# Dell-Vostro-14-5468-Hackintosh

EFI for Dell Vostro 14 5468 on OpenCore bootloader

## Specs

Type | Details
 ------ | --------------------------------
CPU     | Intel® Kaby Lake i5-7200U
iGPU    | Intel® HD Graphics 620
dGPU    | NVIDIA GeForce 940MX
Display | AU Optronics B140HTN (Dell R78M4) [14" LCD] FHD
RAM     | 8057 MB (DDR4 SDRAM)
Audio   | Realtek ALC256
WLAN    | Intel® Dual Band Wireless-AC 3165
LAN     | Realtek RTL8111
SSD     | SanDisk X400 M.2 2280 128GB (128 GB, SATA-III)
KB      | Standard PS/2 Keyboard
TP      | I2C HID Trackpad
SMBIOS  | MacBookPro 14,1
BIOS    | Dell Vostro 5468 1.20.0
Bootloader | OpenCore 0.9.3 DEBUG

Success on macOS Monterey 12.6.7

## What works and What doesn't or WIP

- [x] Intel® HD Graphics 620 iGPU eDP Output (with Backlight)
- [x] Intel® HD Graphics 620 iGPU HDMI Output(with HDMI Audio)
- [x] I2C Touchpad & PS/2 Keyboard
- [x] All USB Ports Type A (3xUSB 3.0 & 3xUSB 2.0)
- [x] ALC256 Internal Speakers & Mic
- [x] ALC256 Native Jack Output & Input
- [x] Internal Camera
- [x] Intel® 3165AC Wi-Fi (sometimes unstable & very slow, but it works)
- [x] Intel® Bluetooth Module
- [x] Sleep / Wake
- [x] ACPI Battery
- [x] NVRAM
- [ ] Realtek RTL8111 LAN (Did not check)

- [ ] 940MX dGPU (Not supported)

## Important Notes

- This is a **Work in Progress [WIP]**.
- Do not COPY & PASTE this and use on your installer or Mac disk's EFI Partition. This is to give you idea on what will work and a jump start to hackintosh this laptop.
- SMBIOS information are reset to default values... Apply your generated SMBIOS.
- All guides and very much needed information can be read in [Dortania's Guide](https://dortania.github.io/vanilla-laptop-guide/ "Overview - Dortania").

- Fixes for current problems are appreciated.

## To-do before installation

* Change the BIOS configuration in your laptop
* Generate your SMBIOS and put info in the 'Generic' part of config.plist.
* ![image](https://github.com/AGNAGAN/Dell-Vostro-14-5468-Hackintosh/assets/123486067/3d227ef2-c557-413a-9ffa-377f2793ff93)


## Credits
- [Apple](https://apple.com) for macOS;
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
