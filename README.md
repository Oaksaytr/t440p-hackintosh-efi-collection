Contains the efi folder needed to boot macos sonoma 14.4+ on your thinkpad t440p. Make sure to generate your own serial number using [gensmbios](https://github.com/corpnewt/GenSMBIOS) for MacBookPro16,1 after downloading, as that is the smbios the usb map is for

The sd card reader will not work as I haven't found a compatible kext

Note: if you want to use this efi folder with versions other than 14.4+, install a compatible version of [airportitlwm/itlwm](https://github.com/OpenIntelWireless/itlwm), and modify the usb map as well as the config.plist if necessary

Use [OCPL](https://github.com/dortania/OpenCore-Legacy-Patcher) to make your experience usable, as sonoma doesn't support haswell igpus

ACPI patches by [valnoxy](https://github.com/valnoxy)

