# hackintosh-asus-x550ln

![Screenshot](http://i66.tinypic.com/311ukat.png)

This is a working set of kexts and configurations for running macOS Mojave on an Asus x550ln i5 laptop. 

## Status
 - Current version: macOS Mojave 10.14.2
 - Bootloader: Clover EFI
 - Working: CPU steps, sleep/shutdown, audio, USB, wifi(replaced with atheros9285), intel hd4400.
 - Not working: nvidia graphic (had been disabled), card reader.
 
 probably some minor works needs to be done on acpi files but no problem for daily driver with this status. 
 
 ## Fix
- Shutdown/Sleep/Restart issues was fixed! Check the [**Management-Engine-Firmware**] https://github.com/anhbinhvodanh/Dell-5547-Hackintosh/tree/master/Management-Engine-Firmware
(This fix worked on my asus x550ln for all operating systems.(windows/linux/macos sleep shudown issue)
